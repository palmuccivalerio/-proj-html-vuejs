<script>
import AppCardMarketing from "../HomeComponents/AppCardMarketing.vue"
export default {
  components: {
    AppCardMarketing,
  },
  data() {
    return {
      ListMarketingArray: [
        {
          image: "https://avada.website/marketing-consultant/wp-content/uploads/sites/142/2020/06/blog-posts-6.jpg",
          text: "Marketing Tips And Tricks For Your Website",
        },
        {
          image: "https://avada.website/marketing-consultant/wp-content/uploads/sites/142/2020/06/blog-posts-5.jpg",
          text: "How To Write Stunning Blog Post Titles",
        },
        {
          image: "https://avada.website/marketing-consultant/wp-content/uploads/sites/142/2020/06/blog-posts-4.jpg",
          text: "Techniques To Reduce Facebook Ads Speed",
        },
      ],
    }
  }
}
</script>
<template>
  <div class="wrapper">
  <div class="container">
    <div class="row mb-4">
      <div class="col-md-4" v-for="(item, index) in ListMarketingArray" :key="index">
        <AppCardMarketing :image="item.image" :text="item.text" />
      </div>
    </div>
  </div>

  </div>

</template>

<<<<<<< HEAD
<style scoped lang="scss">
.wrapper{
  background-color: #F6F6F8;
}


</style>
=======
<style scoped lang="scss"></style>
>>>>>>> 23a1ab96e6b2462942b0ff1dd2ac000f3cbadabf
