<template>
    <div class="max-h-screen">
        <div class="flex bg-gradient-to-r from-pink-600  to-purple-900 sticky top-0 z-30">
            <div class="flex-none my-auto py-4 px-4">
                <img class="h-7" src="/image/point-logo.svg"/>
            </div>
            <div class="w-full">
                <search></search>
            </div>
        </div>


        <div class="grid grid-cols-1 md:grid-cols-2">

            <div class=" pl-4 ">
                <div>
                    <qr-code></qr-code>
                </div>
                <div class="flex mb-auto">
                    <div class="flex bg-blue-100 p-5 w-full border-l-4 border-blue-500 rounded-lg">
                        <h1 class="flex-1 leading-tight text-xl text-blue-700 font-bold">Total</h1>
                        <h1 class="font-bold text-2xl">230 <span class="font-bold">TJS</span></h1>
                    </div>
                </div>
                <div class="flex py-36 " @click="isOpen = true">
                    <button  class="flex gap-6 mx-auto text-2xl my-auto bg-green-500 hover:bg-green-700 text-white font-bold py-10 px-60 rounded">
                        <img class="h-16" src="icons/check-out.svg">
                        <h1 class="my-auto">Check out</h1>
                    </button>
                </div>
            </div>
            <div class="overflow-y-scroll">
                <Table></Table>
            </div>


        </div>
    </div>
    <div v-show="isOpen" class="modal h-screen w-full fixed left-0 top-0 flex justify-center items-center bg-black bg-opacity-50 px-40">
        <!-- modal -->
        <div class="bg-white rounded shadow-lg">
            <!-- modal header -->
            <div class="border-b px-4 py-2 flex justify-between items-center">
                <h3 class="font-semibold text-lg">Checking Out</h3>
                <button class="text-black close-modal">&cross;</button>
            </div>
            <!-- modal body -->
            <div class="p-3">
                <div class="flex bg-gray-50">
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
                    </div>
                </div>
            </div>
            <div class="flex justify-end items-center w-100 border-t p-3">
                <button @click="isOpen=false" class="bg-red-600 hover:bg-red-700 px-3 py-1 rounded text-white mr-1 close-modal">Cancel</button>
                <button class="bg-blue-600 hover:bg-blue-700 px-3 py-1 rounded text-white">Done</button>
            </div>
        </div>
    </div>
</template>

<script setup>
import Search from "@/Pages/Components/Search.vue";
import Table from "@/Pages/Components/Table.vue";
import QrCode from "@/Pages/Components/QrCode.vue";

import {ref} from "vue";


const isOpen = ref(false);
</script>

<style scoped>

</style>
