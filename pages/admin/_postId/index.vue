<template>
    <div class="admin-post-page">
        <section class="update-form">
            <AdminPostForm :post="loadedPost"/>
        </section>
    </div>
</template>
<script>
    import AdminPostForm from '@/components/Admin/AdminPostForm'

    export default {
        components:{
            AdminPostForm
        },
        data()
        {
          return{
            loadedPost:{
              author:'Maximilian',
              title:'My awesome post',
              content:'Super amazing',
              thumbnailLink:'lol'
            }
          }
        }

    }
</script>
