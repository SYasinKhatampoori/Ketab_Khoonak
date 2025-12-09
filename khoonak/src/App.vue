<template>
  <div class="flex justify-evenly flex-col items-center h-screen">
    <header class="absolute top-0 flex justify-evenly items-center w-full h-18 gap-x-10 bg-[#A67B5B] rounded-b-lg">
      <div class="cursor-pointer border border-black rounded-full p-3 bg-[#f7c390]">
        <img src="./assets/menu-svgrepo-com.svg" class="w-6" alt="">
      </div>
      <div>

      </div>
      <div class="bg-[#f7c390] px-2 py-3 rounded-lg shadow-[0_4px_10px_#f7c390] cursor-pointer duration-75 hover:px-3 hover:py-3.5">
        <router-link to="/login" class=""><span>ورود و ثبت نام</span></router-link>
      </div>
      
    </header>

    

    <router-view></router-view>
  </div>
</template>

<script>
export default {
  
}
</script>