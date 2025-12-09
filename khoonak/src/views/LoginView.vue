<template>
  <div class="flex justify-eve items-center flex-col">
    <form
      action=""
      class="w-[350px] h-[400px] bg-[#A67B5B] p-10 rounded-lg shadow-2xl flex justify-between items-center flex-col"
    >
      <h1 class="text-2xl text-[#FFF8EA]">ورود</h1>
      <span class="w-full h-1 bg-[#FFF8EA] rounded-3xl"></span>
      <div
        class="flex justify-between items bg-center text-xl text-[#A67B5B] rounded-lg h-10"
      >
        <label
          class="text-[#A67B5B] font-bold p-[1.5px] bg-[#f7c390] w-[60px] rounded-r-lg border-black text-sm flex justify-center items-center"
          >نام کاربری</label
        >
        <input
          type="text"
          class="rounded-l-lg outline-none p-2 text-[#A67B5B] bg-[#FFF8EA]"
        />
      </div>
      <div
        class="flex justify-between items bg-center text-xl text-[#A67B5B] rounded-lg h-10"
      >
        <label
          class="text-[#A67B5B] font-bold p-[1.5px] bg-[#f7c390] w-[60px] rounded-r-lg border-black text-sm flex justify-center items-center"
          >رمز</label
        >
        <input
          type="password"
          class="rounded-l-lg outline-none p-2 text-[#A67B5B] bg-[#FFF8EA]"
        />
      </div>
      
      <button
        type="submit"
        class="text-xl text-[#FFF8EA] bg-[#f7c390] flex items-center justify-center w-full px-5 py-3 rounded-lg"
      >
        ورود
      </button>

      <p class="text-[#FFF8EA] bg-[#A67B5B] p-2 border-black text-md">
        حساب ندارید
        <a href="" class="text-[#FFF8EA] hover:text-[#d3c3a3]">پس بسازید</a>
      </p>
    </form>
  </div>
</template>

<script>
export default {};
</script>
