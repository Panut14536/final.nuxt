<template>
  <div class="m-5 md:flex bg-gray-700 rounded-xl p-8 md:p-0">
    <img
      class="md-flex md:p-0 h-70 w-70 rounded-xl"
      :src="users.image"
      alt=""
    />

    <div class="pt-6 md:p-8 text-center md:text-left space-y-4">
      <div class="text-3xl font-medium text-white">" Profile "</div>
      <div class="text-xl mt-3 text-gray-300">
        รหัสนิสิต : {{ users.username }}
      </div>
      <div class="text-xl mt-3 text-gray-300">
        ชื่อ : {{ users.firstname }} {{ users.lastname }}
      </div>
      <div class="text-xl mt-3 text-gray-300">เพศ : {{ users.sex }}</div>
      <div class="text-xl mt-3 text-gray-300">
        วันเกิด : {{ users.birthday }}
      </div>
      <div class="text-xl mt-3 text-gray-300">อายุ : {{ users.age }}</div>
      <div class="text-xl mt-3 text-gray-300">
        สถานศึกษา : {{ users.study }}
      </div>
      <div class="text-xl mt-3 text-gray-300">
        ที่อยู่ : {{ users.home }}
      </div>
      <div class="text-xl mt-3 text-gray-300">
        สิ่งที่ชอบ : {{ users.like }}
      </div>
    </div>
  </div>
</template>

<script>
import user from "@/static/user.json";
export default {
  data: () => {
    return {
      users: user,
    };
  },
};
</script>

<style>
</style>