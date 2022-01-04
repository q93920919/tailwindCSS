<template>
  <div class="home">
    <div class="space-y-4">
      <div class="w-96 bg-white shadow rounded">w-96</div>
      <div class="w-80 bg-white shadow rounded">w-80</div>
      <div class="w-72 bg-white shadow rounded">w-72</div>
      <div class="w-64 bg-white shadow rounded">w-64</div>
      <div class="w-60 bg-white shadow rounded">w-60</div>
      <div class="w-56 bg-white shadow rounded">w-56</div>
      <div class="w-52 bg-white shadow rounded">w-52</div>
      <div class="w-48 bg-white shadow rounded">w-48</div>
    </div>
    <button
      class="bg-red-500 shadow-2xl hover:bg-red-700 text-white rounded-sm p-0.5"
    >
      Hover me
    </button>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "Home",
  components: {
    // HelloWorld
  },
};
</script>
