<template>
    <div class="posts-page">
      <PostList/>
    </div>
</template>
<script scoped>
    import PostList from '@/components/Posts/PostList'
    export default {
        components:{
            PostList
        }
    }
</script>
<style scoped>
    .posts-page{
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .post-list {
        display: flex;
        padding: 20px;
        box-sizing: border-box;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
    }

</style>