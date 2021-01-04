<template>
  <div class="relative bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6">
        <div class="flex justify-between items-center border-b-2 border-gray-100 py-6 md:justify-start md:space-x-10">
        <div class="flex justify-start lg:w-0 lg:flex-1">
            <a href="#">
            <span class="sr-only">Workflow</span>
            <img class="h-8 w-auto sm:h-10" src="../assets/images/funnel.svg" alt="">
            </a>
        </div>
        <div class="hidden md:flex items-center justify-end md:flex-1 lg:w-0">
            <a href="#" class="ml-8 whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-medium text-white bg-pink-500 hover:bg-pink-700">
            Suggest
            </a>
        </div>
        </div>
    </div>
    <div class="absolute top-0 inset-x-0 p-2 transition md:hidden">
        <div class="rounded-lg shadow-lg bg-white flex w-full justify-between">
            <div class="py-6 px-5">
                <a href="#">
                <img class="h-8 sm:h-10" src="../assets/images/funnel.svg" alt="amass">
                </a>
            </div>
            <div class="py-6 px-5">
                <a href="#" class="flex justify-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-medium text-white bg-pink-500 hover:bg-pink-700">
                Suggest
                </a>
            </div>
        </div>
    </div>
  </div>
</template>