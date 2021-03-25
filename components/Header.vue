<template>
    <div>
    <header id="header">
        <a class="logo" href="index.html">Industrious</a>
        <nav>
            <a href="#menu" @click.prevent="isVisible = !isVisible">Menu</a>
        </nav>
    </header>
    
			<nav id="menu" :class="{'is-menu-visible':isVisible}">
				<ul class="links ">
					<li><a href="index.html">Home</a></li>
					<li><a href="elements.html">Elements</a></li>
					<li><a href="generic.html">Generic</a></li>
				</ul>
			</nav>
    </div>
</template>
<script>
export default{
    data(){
        return {
            isVisible:false
        }
    }
}
</script>