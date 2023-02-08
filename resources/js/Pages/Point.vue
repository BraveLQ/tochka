<template>
    <div class="bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500">
        <div class="py-6">
            <img class="mx-auto h-14" src="/image/point-logo.svg"/>
        </div>
        <div class="flex py-4 pb-6">
            <h1 class="text-white text-3xl md:text-6xl mx-auto"><span class="font-bold">Total Cost:</span> 230TJS</h1>
        </div>
    </div>
<!--Search-->
    <div class="px-8 py-4">
        <form>
            <label for="default-search" class="mb-2 text-sm font-medium text-gray-900 sr-only">Search</label>
            <div class="relative">
                <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                    <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                </div>
                <input type="search" id="default-search" class="block w-full p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500  " placeholder="Search for Products..." required>
                <button type="submit" class="text-white absolute right-2.5 bottom-2.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2">Search</button>
            </div>
        </form>
    </div>
<!--Search-->

    <div class="flex bg-gray-50 grid grid-cols-1 lg:grid-cols-2">
        <div class=" flex flex-col  justify-between">
            <!--            Card-->
            <div class="flex h-28 gap-x-6 px-28 mt-3 mb-auto">
                <div class="rounded-lg p-4 bg-purple-700 flex flex-col w-48">
                    <div>
                        <h5 class="text-white text-xl font-bold leading-none">
                            Tendered
                        </h5>
                        <span class="text-xs text-white leading-none">Lorem ipsum</span>
                    </div>
                    <div class="flex items-center">
                        <div class="text-lg text-white font-light">
                            <div>
                                <input type="text" id="first_name" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full" placeholder="Somoni" required>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="rounded-lg p-4 bg-amber-300 flex flex-col w-48">
                    <div>
                        <h5 class="text-white text-xl font-bold leading-none">
                            Last Sale
                        </h5>
                        <span class="text-xs text-white leading-none">Lorem ipsum</span>
                    </div>
                    <div class="flex items-center">
                        <div class="text-lg text-white font-light">
                            170TJS
                        </div>
                    </div>
                </div>
                <div class="rounded-lg p-4 bg-red-400 flex flex-col w-48">
                    <div>
                        <h5 class="text-white text-xl font-bold leading-none">
                            Change
                        </h5>
                        <span class="text-xs text-white leading-none">Lorem ipsum</span>
                    </div>
                    <div class="flex items-center">
                        <div class="text-lg text-white font-light">
                            30TJS
                        </div>
                    </div>
                </div>
            </div>
            <!--            Card-->

            <div class="relative">
                <button @click="isOpen = true" type="button" class="absolute inset-x-0 bottom-0 inline-block px-8 py-4 bg-green-500 text-white font-medium text-2xl leading-tight uppercase rounded shadow-md hover:bg-green-600 hover:shadow-lg focus:bg-green-600 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-green-700 active:shadow-lg transition duration-150 ease-in-out">Check Out</button>
            </div>


        </div>
        <div class="w-full overflow-y-scroll flex-none z-10 pr-4" style="height: 530px">
                <Table></Table>
        </div>
    </div>
</template>

<script setup>
import Table from "@/Pages/Components/Table.vue";
import { ref } from "vue";

const isOpen = ref(false);
</script>

<style scoped>
div::-webkit-scrollbar {
    display: none;
}
</style>
