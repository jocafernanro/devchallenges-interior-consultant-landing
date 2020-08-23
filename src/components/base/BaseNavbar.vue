<template>
  <nav class="flex items-center justify-between flex-wrap mb-40 montserrat">
    <div
      class="crimson-pro inline-block border-solid border-2 uppercase py-2 px-3 text-sm"
    >
      This interior
    </div>
    <ul class="hidden md:flex text-md mr-4">
      <li class="lg:ml-24 md:ml-16 hover:text-gray-500 font-bold">Home</li>
      <li class="lg:ml-24 md:ml-16 hover:text-gray-500">Collection</li>
      <li class="lg:ml-24 md:ml-16 hover:text-gray-500">About</li>
      <li class="lg:ml-24 md:ml-16 hover:text-gray-500">Contact</li>
    </ul>
    <i class="material-icons md:hidden">menu</i>

    <!-- Menu Modal -->
    <div class="hidden bg-black w-full h-full top-0 left-0">
      <i class="material-icons fixed right-0 m-8">close</i>
      <div class="w-full h-full flex flex-col justify-center">
        <ul class="flex flex-col justify-center items-center text-center">
          <li class="mb-6 font-bold">Home</li>
          <li class="mb-6 ">Collection</li>
          <li class="mb-6 ">About</li>
          <li class="mb-6 ">Contact</li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped></style>
