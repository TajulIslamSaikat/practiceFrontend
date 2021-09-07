<template>
  <div class="container mx-auto">
    <MainProfile />
    <CreatePost />
    <SubMenu />
    <PostVews />
    <PostVews />
    <PostVews />
    <PostVews />
  </div>
</template>

<script>
import MainProfile from '@/components/profile/MainProfile.vue'
import CreatePost from '@/components/profile/CreatePost.vue'
import SubMenu from '@/components/profile/SubMenu.vue'
import PostVews from '@/components/profile/PostVews.vue'
export default {
  layout: 'profile',
  components: {
    MainProfile,
    CreatePost,
    SubMenu,
    PostVews,
  },
}
</script>

<style scoped>
</style>