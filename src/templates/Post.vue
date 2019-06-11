<template>
  <Layout>
    <h1>{{ $page.post.title }}</h1>
    <div v-html="$page.post.content" />
  </Layout>
</template>

<page-query>
query Post($path: String!) {
  post(path: $path) {
    title
    date (format: "MMMM D, Y")
    content
  }
}
</page-query>

<script>
export default {
  name: 'Post',
  metaInfo() {
    return {
      title: this.$page.post.title
    }
  }
}
</script>

<style scoped>

</style>
