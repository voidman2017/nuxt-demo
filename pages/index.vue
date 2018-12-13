<template>
  <section class="container">
    <div>
      <nuxt-link to="/list">列表页</nuxt-link>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
  asyncData(){
    return { name: 'World' }
    setTimeout(()=>{
    },3000)
  },
  components: {
    Logo,
  },
  layout(context){
    return 'dark';
  },
  head () {
    return {
      title: "主页",
      meta: [
        { hid: 'description', name: 'description', content: "this is app page index" },
        { hid: 'keywords', name: 'keywords', content: 'pageIndex' }
      ]
    }
  }
}
</script>

<style>

</style>
