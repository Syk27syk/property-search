<template>
  <div>
    <header class="grid grid-cols-2 py-2 bg-black text-white">
      <div id="logo" class="flex flex-row">
        <img src="/logo.png" class="h-16 w-16 m-5" alt="logo" />
        <p class="my-auto text-3xl font-bold"> Property Search </p>
      </div>
      <div id="navigation" class="grid grid-cols-4 my-auto text-2xl font-bold">
        <span>nav item 1</span>
        <span>nav item 2</span>
        <span>nav item 3</span>
        <span>nav item 4</span>
      </div>
    </header>
    <div class="flex h-screen h-[100vh] bg-[url('/hero-bg.jpg')] bg-cover bg-center align-middle text-white text-center">
      <div class="m-auto px-12 py-10 bg-white bg-opacity-20 backdrop-blur rounded-md shadow-lg shadow-black">
        <h1 class="text-5xl font-bold text-red-500">Property Search</h1>
        <p class="mt-5 text-3xl font-bold text-red-500">Find new and secondary properties for sale and for rent</p>
      </div>
      <div>
        <img src="/mag-glass.png" class="h-2/3 w-2/3 absolute right-0 bottom-0" alt="">
      </div>
    </div>
    <footer class="bg-black text-white text-3xl font-bold m-auto">
      <p class="p-5">footer</p>
    </footer>
  </div>
</template>
