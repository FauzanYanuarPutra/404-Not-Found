<template>
<div class="w-full h-[100vh] bg-[#FFF] ">
  <h1 class="text-lg m-3 font-semibold z-20 lg:fixed lg:mx-20">404 NOT FOUND</h1>
  <div class="lg:flex justify-center items-center  w-full h-full lg:px-20 ">
      <div class="lg:w-[50%] " >
      <img :src="'Scarecrow.png'" alt="" class="w-[300px] lg:w-[400px] mx-auto my-10">
      
      </div>
      <div class="mx-5 lg:w-[50%]  ">
        <h1 class="text-3xl lg:text-5xl  font-bold">I have bad news for you</h1>
        <h1 class="text-xl  font-medium my-10">The page you are looking for might be removed or is temporarily unavailable</h1>
        <button class="w-[200px] h-[50px] text-white bg-[#333] text-sm font-bold">BACK TO HOMEPAGE</button>
      </div>
<div class="h-[90px] lg:hidden"></div>

  </div>
</div>
</template>

<style>
* {
  color: #333;
  background-color: #FFF;
}
</style>
