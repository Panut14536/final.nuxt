<template >
  <div class="w-full h-15 mx-auto px-20 py-3 bg-gray-900 flex flex-wrap justify-center items-center">
      <div class="w-1/3">
        <a href="https://github.com/Panut14536" class="ml-4 text-lg font-medium text-white">Github</a>
     </div>
     <div class="w-1/3 flex justify-center items-center" @click="$router.push('/')">
        <button class="text-3xl font-medium text-white">เกียร์เดริเวอร์รี่</button>
     </div>
     <div class="w-1/3 flex justify-end" @click="$router.push('/Profile')">
        <button class="mr-4 text-lg font-medium text-white ">Profile</button>

     </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>