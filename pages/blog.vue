<template>
  <section>
    <div>
      <h1 class="title">
        nuxt-blog-pwa
      </h1>
      <blog-post-list />
    </div>
  </section>
</template>

<script>
import BlogPostList from '~/components/BlogPostList.vue'

export default {
  components: {
    BlogPostList
  }
}
</script>

<style />
