<template>
  <div class="body">
    <Header />
    <h1 class="color">Welcome</h1>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    };
  },
}
</script>

<style>

</style>