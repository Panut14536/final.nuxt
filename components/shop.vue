<template>
  <div class="flex bg-gray-800 w-18 p-4 rounded-full">
     
      <h1 class="text-red-400">{{count}}</h1>
  </div>
</template>

<script>
export default {
    props:{
        count:{
            default:0
        }
    }

}
</script>

<style>

</style>