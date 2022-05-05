<template>
<Header />
<div class="container h-screen bg-[#f0f9ff]" >
  <RouterView  />
  </div>
</template>

<script>
 import Header from './components/Header.vue';
 





export default {
  components: {
    Header,
  

  },
}
</script>

