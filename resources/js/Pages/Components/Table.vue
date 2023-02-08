<template>
    <!-- component -->
    <div class="overflow-hidden rounded-lg border border-gray-200 shadow-md m-5">
        <table class="w-full border-collapse bg-white text-left text-sm text-gray-500">
            <thead class="bg-gray-50">
            <tr>
                <th scope="col" class="px-6 py-4 font-medium text-gray-900">Name</th>
                <th scope="col" class="px-6 py-4 font-medium text-gray-900">Price</th>
                <th scope="col" class="px-6 py-4 font-medium text-gray-900">Discount %</th>
                <th scope="col" class="px-6 py-4 font-medium text-gray-900">Amount</th>
                <th scope="col" class="px-6 py-4 font-medium text-gray-900"></th>
            </tr>
            </thead>
            <tbody class="divide-y divide-gray-100 border-t border-gray-100">
            <tr class="hover:bg-gray-50">
                <th class="flex gap-3 px-6 py-4 font-normal text-gray-900">
                    <div class="text-sm">
                        <div class="font-medium text-gray-700">Kit Katakjcaasjncaosjncao</div>
                    </div>
                </th>
                <td class="px-6 py-4">
          <span
              class="inline-flex items-center gap-1 rounded-full bg-green-50 px-2 py-1 text-xs font-semibold text-green-600"
          >
            <span class="h-1.5 w-1.5 rounded-full bg-green-600"></span>
            20TJS
          </span>
                </td>
                <td class="px-6 py-4">0</td>
                <td class="px-6 py-4">
                    <div class="flex gap-2">
                        <div
                            class="flex flex-row border h-10 w-24 rounded-lg border-gray-400 relative"
                        >
                            <button
                                class="font-semibold border-r bg-blue-400 hover:bg-red-600 text-white border-gray-400 h-full w-20 flex rounded-l focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">-</span>
                            </button>
                            <input
                                type="hidden"
                                class="md:p-2 p-1 text-xs md:text-base border-gray-400 focus:outline-none text-center"
                                readonly
                                name="custom-input-number"
                            />
                            <div
                                class="bg-white w-24 text-xs md:text-base flex items-center justify-center cursor-default"
                            >
                                <span>2</span>
                            </div>

                            <button
                                class="font-semibold border-l  bg-blue-400 hover:bg-blue-600 text-white border-gray-400 h-full w-20 flex rounded-r focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">+</span>
                            </button>
                        </div>
                    </div>
                </td>
                <td class="px-6 py-4">
                    <div class="flex justify-end gap-4">
                        <a x-data="{ tooltip: 'Delete' }" href="#">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor"
                                class="h-6 w-6"
                                x-tooltip="tooltip"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"
                                />
                            </svg>
                        </a>

                    </div>
                </td>
            </tr>
            <tr class="hover:bg-gray-50">
                <th class="flex gap-3 px-6 py-4 font-normal text-gray-900">
                    <div class="text-sm">
                        <div class="font-medium text-gray-700">Kit Kat</div>
                    </div>
                </th>
                <td class="px-6 py-4">
          <span
              class="inline-flex items-center gap-1 rounded-full bg-green-50 px-2 py-1 text-xs font-semibold text-green-600"
          >
            <span class="h-1.5 w-1.5 rounded-full bg-green-600"></span>
            20TJS
          </span>
                </td>
                <td class="px-6 py-4">0</td>
                <td class="px-6 py-4">
                    <div class="flex gap-2">
                        <div
                            class="flex flex-row border h-10 w-24 rounded-lg border-gray-400 relative"
                        >
                            <button
                                class="font-semibold border-r bg-blue-400 hover:bg-red-600 text-white border-gray-400 h-full w-20 flex rounded-l focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">-</span>
                            </button>
                            <input
                                type="hidden"
                                class="md:p-2 p-1 text-xs md:text-base border-gray-400 focus:outline-none text-center"
                                readonly
                                name="custom-input-number"
                            />
                            <div
                                class="bg-white w-24 text-xs md:text-base flex items-center justify-center cursor-default"
                            >
                                <span>2</span>
                            </div>

                            <button
                                class="font-semibold border-l  bg-blue-400 hover:bg-blue-600 text-white border-gray-400 h-full w-20 flex rounded-r focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">+</span>
                            </button>
                        </div>
                    </div>
                </td>
                <td class="px-6 py-4">
                    <div class="flex justify-end gap-4">
                        <a x-data="{ tooltip: 'Delete' }" href="#">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor"
                                class="h-6 w-6"
                                x-tooltip="tooltip"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"
                                />
                            </svg>
                        </a>

                    </div>
                </td>
            </tr>
            <tr class="hover:bg-gray-50">
                <th class="flex gap-3 px-6 py-4 font-normal text-gray-900">
                    <div class="text-sm">
                        <div class="font-medium text-gray-700">Kit Kat</div>
                    </div>
                </th>
                <td class="px-6 py-4">
          <span
              class="inline-flex items-center gap-1 rounded-full bg-green-50 px-2 py-1 text-xs font-semibold text-green-600"
          >
            <span class="h-1.5 w-1.5 rounded-full bg-green-600"></span>
            20TJS
          </span>
                </td>
                <td class="px-6 py-4">0</td>
                <td class="px-6 py-4">
                    <div class="flex gap-2">
                        <div
                            class="flex flex-row border h-10 w-24 rounded-lg border-gray-400 relative"
                        >
                            <button
                                class="font-semibold border-r bg-blue-400 hover:bg-red-600 text-white border-gray-400 h-full w-20 flex rounded-l focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">-</span>
                            </button>
                            <input
                                type="hidden"
                                class="md:p-2 p-1 text-xs md:text-base border-gray-400 focus:outline-none text-center"
                                readonly
                                name="custom-input-number"
                            />
                            <div
                                class="bg-white w-24 text-xs md:text-base flex items-center justify-center cursor-default"
                            >
                                <span>2</span>
                            </div>

                            <button
                                class="font-semibold border-l  bg-blue-400 hover:bg-blue-600 text-white border-gray-400 h-full w-20 flex rounded-r focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">+</span>
                            </button>
                        </div>
                    </div>
                </td>
                <td class="px-6 py-4">
                    <div class="flex justify-end gap-4">
                        <a x-data="{ tooltip: 'Delete' }" href="#">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor"
                                class="h-6 w-6"
                                x-tooltip="tooltip"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"
                                />
                            </svg>
                        </a>

                    </div>
                </td>
            </tr>
            <tr class="hover:bg-gray-50">
                <th class="flex gap-3 px-6 py-4 font-normal text-gray-900">
                    <div class="text-sm">
                        <div class="font-medium text-gray-700">Kit Kat</div>
                    </div>
                </th>
                <td class="px-6 py-4">
          <span
              class="inline-flex items-center gap-1 rounded-full bg-green-50 px-2 py-1 text-xs font-semibold text-green-600"
          >
            <span class="h-1.5 w-1.5 rounded-full bg-green-600"></span>
            20TJS
          </span>
                </td>
                <td class="px-6 py-4">0</td>
                <td class="px-6 py-4">
                    <div class="flex gap-2">
                        <div
                            class="flex flex-row border h-10 w-24 rounded-lg border-gray-400 relative"
                        >
                            <button
                                class="font-semibold border-r bg-blue-400 hover:bg-red-600 text-white border-gray-400 h-full w-20 flex rounded-l focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">-</span>
                            </button>
                            <input
                                type="hidden"
                                class="md:p-2 p-1 text-xs md:text-base border-gray-400 focus:outline-none text-center"
                                readonly
                                name="custom-input-number"
                            />
                            <div
                                class="bg-white w-24 text-xs md:text-base flex items-center justify-center cursor-default"
                            >
                                <span>2</span>
                            </div>

                            <button
                                class="font-semibold border-l  bg-blue-400 hover:bg-blue-600 text-white border-gray-400 h-full w-20 flex rounded-r focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">+</span>
                            </button>
                        </div>
                    </div>
                </td>
                <td class="px-6 py-4">
                    <div class="flex justify-end gap-4">
                        <a x-data="{ tooltip: 'Delete' }" href="#">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor"
                                class="h-6 w-6"
                                x-tooltip="tooltip"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"
                                />
                            </svg>
                        </a>

                    </div>
                </td>
            </tr>
            <tr class="hover:bg-gray-50">
                <th class="flex gap-3 px-6 py-4 font-normal text-gray-900">
                    <div class="text-sm">
                        <div class="font-medium text-gray-700">Kit Kat</div>
                    </div>
                </th>
                <td class="px-6 py-4">
          <span
              class="inline-flex items-center gap-1 rounded-full bg-green-50 px-2 py-1 text-xs font-semibold text-green-600"
          >
            <span class="h-1.5 w-1.5 rounded-full bg-green-600"></span>
            20TJS
          </span>
                </td>
                <td class="px-6 py-4">0</td>
                <td class="px-6 py-4">
                    <div class="flex gap-2">
                        <div
                            class="flex flex-row border h-10 w-24 rounded-lg border-gray-400 relative"
                        >
                            <button
                                class="font-semibold border-r bg-blue-400 hover:bg-red-600 text-white border-gray-400 h-full w-20 flex rounded-l focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">-</span>
                            </button>
                            <input
                                type="hidden"
                                class="md:p-2 p-1 text-xs md:text-base border-gray-400 focus:outline-none text-center"
                                readonly
                                name="custom-input-number"
                            />
                            <div
                                class="bg-white w-24 text-xs md:text-base flex items-center justify-center cursor-default"
                            >
                                <span>2</span>
                            </div>

                            <button
                                class="font-semibold border-l  bg-blue-400 hover:bg-blue-600 text-white border-gray-400 h-full w-20 flex rounded-r focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">+</span>
                            </button>
                        </div>
                    </div>
                </td>
                <td class="px-6 py-4">
                    <div class="flex justify-end gap-4">
                        <a x-data="{ tooltip: 'Delete' }" href="#">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor"
                                class="h-6 w-6"
                                x-tooltip="tooltip"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"
                                />
                            </svg>
                        </a>

                    </div>
                </td>
            </tr>
            <tr class="hover:bg-gray-50">
                <th class="flex gap-3 px-6 py-4 font-normal text-gray-900">
                    <div class="text-sm">
                        <div class="font-medium text-gray-700">Kit Kat</div>
                    </div>
                </th>
                <td class="px-6 py-4">
          <span
              class="inline-flex items-center gap-1 rounded-full bg-green-50 px-2 py-1 text-xs font-semibold text-green-600"
          >
            <span class="h-1.5 w-1.5 rounded-full bg-green-600"></span>
            20TJS
          </span>
                </td>
                <td class="px-6 py-4">0</td>
                <td class="px-6 py-4">
                    <div class="flex gap-2">
                        <div
                            class="flex flex-row border h-10 w-24 rounded-lg border-gray-400 relative"
                        >
                            <button
                                class="font-semibold border-r bg-blue-400 hover:bg-red-600 text-white border-gray-400 h-full w-20 flex rounded-l focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">-</span>
                            </button>
                            <input
                                type="hidden"
                                class="md:p-2 p-1 text-xs md:text-base border-gray-400 focus:outline-none text-center"
                                readonly
                                name="custom-input-number"
                            />
                            <div
                                class="bg-white w-24 text-xs md:text-base flex items-center justify-center cursor-default"
                            >
                                <span>2</span>
                            </div>

                            <button
                                class="font-semibold border-l  bg-blue-400 hover:bg-blue-600 text-white border-gray-400 h-full w-20 flex rounded-r focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">+</span>
                            </button>
                        </div>
                    </div>
                </td>
                <td class="px-6 py-4">
                    <div class="flex justify-end gap-4">
                        <a x-data="{ tooltip: 'Delete' }" href="#">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor"
                                class="h-6 w-6"
                                x-tooltip="tooltip"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"
                                />
                            </svg>
                        </a>

                    </div>
                </td>
            </tr>
            <tr class="hover:bg-gray-50">
                <th class="flex gap-3 px-6 py-4 font-normal text-gray-900">
                    <div class="text-sm">
                        <div class="font-medium text-gray-700">Kit Kat</div>
                    </div>
                </th>
                <td class="px-6 py-4">
          <span
              class="inline-flex items-center gap-1 rounded-full bg-green-50 px-2 py-1 text-xs font-semibold text-green-600"
          >
            <span class="h-1.5 w-1.5 rounded-full bg-green-600"></span>
            20TJS
          </span>
                </td>
                <td class="px-6 py-4">0</td>
                <td class="px-6 py-4">
                    <div class="flex gap-2">
                        <div
                            class="flex flex-row border h-10 w-24 rounded-lg border-gray-400 relative"
                        >
                            <button
                                class="font-semibold border-r bg-blue-400 hover:bg-red-600 text-white border-gray-400 h-full w-20 flex rounded-l focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">-</span>
                            </button>
                            <input
                                type="hidden"
                                class="md:p-2 p-1 text-xs md:text-base border-gray-400 focus:outline-none text-center"
                                readonly
                                name="custom-input-number"
                            />
                            <div
                                class="bg-white w-24 text-xs md:text-base flex items-center justify-center cursor-default"
                            >
                                <span>2</span>
                            </div>

                            <button
                                class="font-semibold border-l  bg-blue-400 hover:bg-blue-600 text-white border-gray-400 h-full w-20 flex rounded-r focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">+</span>
                            </button>
                        </div>
                    </div>
                </td>
                <td class="px-6 py-4">
                    <div class="flex justify-end gap-4">
                        <a x-data="{ tooltip: 'Delete' }" href="#">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor"
                                class="h-6 w-6"
                                x-tooltip="tooltip"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"
                                />
                            </svg>
                        </a>

                    </div>
                </td>
            </tr>
            <tr class="hover:bg-gray-50">
                <th class="flex gap-3 px-6 py-4 font-normal text-gray-900">
                    <div class="text-sm">
                        <div class="font-medium text-gray-700">Kit Kat</div>
                    </div>
                </th>
                <td class="px-6 py-4">
          <span
              class="inline-flex items-center gap-1 rounded-full bg-green-50 px-2 py-1 text-xs font-semibold text-green-600"
          >
            <span class="h-1.5 w-1.5 rounded-full bg-green-600"></span>
            20TJS
          </span>
                </td>
                <td class="px-6 py-4">0</td>
                <td class="px-6 py-4">
                    <div class="flex gap-2">
                        <div
                            class="flex flex-row border h-10 w-24 rounded-lg border-gray-400 relative"
                        >
                            <button
                                class="font-semibold border-r bg-blue-400 hover:bg-red-600 text-white border-gray-400 h-full w-20 flex rounded-l focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">-</span>
                            </button>
                            <input
                                type="hidden"
                                class="md:p-2 p-1 text-xs md:text-base border-gray-400 focus:outline-none text-center"
                                readonly
                                name="custom-input-number"
                            />
                            <div
                                class="bg-white w-24 text-xs md:text-base flex items-center justify-center cursor-default"
                            >
                                <span>2</span>
                            </div>

                            <button
                                class="font-semibold border-l  bg-blue-400 hover:bg-blue-600 text-white border-gray-400 h-full w-20 flex rounded-r focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">+</span>
                            </button>
                        </div>
                    </div>
                </td>
                <td class="px-6 py-4">
                    <div class="flex justify-end gap-4">
                        <a x-data="{ tooltip: 'Delete' }" href="#">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor"
                                class="h-6 w-6"
                                x-tooltip="tooltip"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"
                                />
                            </svg>
                        </a>

                    </div>
                </td>
            </tr>
            <tr class="hover:bg-gray-50">
                <th class="flex gap-3 px-6 py-4 font-normal text-gray-900">
                    <div class="text-sm">
                        <div class="font-medium text-gray-700">Kit Kat</div>
                    </div>
                </th>
                <td class="px-6 py-4">
          <span
              class="inline-flex items-center gap-1 rounded-full bg-green-50 px-2 py-1 text-xs font-semibold text-green-600"
          >
            <span class="h-1.5 w-1.5 rounded-full bg-green-600"></span>
            20TJS
          </span>
                </td>
                <td class="px-6 py-4">0</td>
                <td class="px-6 py-4">
                    <div class="flex gap-2">
                        <div
                            class="flex flex-row border h-10 w-24 rounded-lg border-gray-400 relative"
                        >
                            <button
                                class="font-semibold border-r bg-blue-400 hover:bg-red-600 text-white border-gray-400 h-full w-20 flex rounded-l focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">-</span>
                            </button>
                            <input
                                type="hidden"
                                class="md:p-2 p-1 text-xs md:text-base border-gray-400 focus:outline-none text-center"
                                readonly
                                name="custom-input-number"
                            />
                            <div
                                class="bg-white w-24 text-xs md:text-base flex items-center justify-center cursor-default"
                            >
                                <span>2</span>
                            </div>

                            <button
                                class="font-semibold border-l  bg-blue-400 hover:bg-blue-600 text-white border-gray-400 h-full w-20 flex rounded-r focus:outline-none cursor-pointer"
                            >
                                <span class="m-auto">+</span>
                            </button>
                        </div>
                    </div>
                </td>
                <td class="px-6 py-4">
                    <div class="flex justify-end gap-4">
                        <a x-data="{ tooltip: 'Delete' }" href="#">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke-width="1.5"
                                stroke="currentColor"
                                class="h-6 w-6"
                                x-tooltip="tooltip"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0"
                                />
                            </svg>
                        </a>

                    </div>
                </td>
            </tr>
            </tbody>
        </table>
    </div>

</template>

<script>
export default {
    name: "Table"
}
</script>

<style scoped>

</style>
