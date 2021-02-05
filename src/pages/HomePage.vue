<template>
  <div class="container-fluid">
    <div class="row text-left">
      <div class="col-2">
      </div>
    </div>
    <div class="row">
      <div class="col-2">
        <navbar-component />
      </div>
    </div>
    <div class="row justify-content-center gif">
      <div class="col-3 ">
        <img src="..\assets\img\HeadShot1.jpg" alt="" class="img-fluid  border pic mt-3">

        <h1 class="text-light pl-4">
          Trevor Douty
        </h1>
        <h3 class="text-light pl-4">
          Software Developer
        </h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: { },
  name: 'Home',
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">

.gif{
  background-image: url("https://2.bp.blogspot.com/-zO8hwvt7iMk/XAVxt4aoQvI/AAAAAAAAwa0/_01xZj87g04GvxpSEKEGRVBEWggW-fC5gCLcBGAs/s1600/7T9364v.gif");
  background-repeat: no-repeat;
  background-size: cover;
}

.pic{
  border-radius: 50%;
}
</style>
