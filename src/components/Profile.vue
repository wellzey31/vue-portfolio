<template>
  <div class="bg-gray-700 justify-center flex flex-col content-center">
    <div class="flex justify-around flex-col">
      <img class="rounded-full h-auto w-auto m-6 shadow-md"
      alt="Picture of me!" src="..\assets\professionalPic.png">
      <h2 class="text-white mb-6 text-lg font-extrabold">Junior Software Developer</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Profile',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  height: 300px;
  width: 300px;
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>
