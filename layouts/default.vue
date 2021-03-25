<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>


<script>
export default {
  head:{
    link:[
      { rel: 'stylesheet', href: '/css/main.css' }
    ],
    
  }
}
</script>