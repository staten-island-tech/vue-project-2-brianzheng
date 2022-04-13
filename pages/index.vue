<template>
  <div class="body">
    <Header />
    <div class="web">
      <section class="text"></section>
      <section class="blogs"></section>
    </div>
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
.text{
  width: 50%;
}
.blogs{
  width: 50%;
}
.body{
  height: 100%;
  background-color: var(--blue);
  background-image: linear-gradient(var(--black-grey),var(--blue));
}
</style>