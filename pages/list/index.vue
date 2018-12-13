<template>
  <section class="container">
    <div>
        总列表页
    </div>
    <nuxt-link to="/list/11111">list 1111</nuxt-link>
  </section>
</template>

<script>
export default {
  layout(context){
    return 'dark';
  },
  head () {
    return {
      title: "列表页",
      meta: [
        { hid: 'description', name: 'description', content: "this is app page list" },
        { hid: 'keywords', name: 'keywords', content: 'pageList' }
      ]
    }
  }
}
</script>

<style>

</style>
