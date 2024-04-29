<template>
  <div>
    <div class="w-100 p-5 border-2 border-solid border-red-500 flex justify-center items-center flex-col gap-5">
         <h1 style="font-size: 2rem;">Dropdown-Task</h1>
         <div class="hs-dropdown relative inline-flex">
                <button id="hs-dropdown-default" type="button" class="hs-dropdown-toggle py-3 px-4 inline-flex items-center gap-x-2 text-sm font-medium rounded-lg border border-gray-200 bg-white text-black-500 shadow-sm hover:bg-gray-50 disabled:opacity-50 disabled:pointer-events-none white:bg-neutral-900 dark:border-neutral-400 dark:text-black-500 white:hover:bg-neutral-800">
                    Select Category
                    <svg class="hs-dropdown-open:rotate-180 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                </button>

                <div class="hs-dropdown-menu transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-60 bg-white shadow-md rounded-lg p-2 mt-2 white:bg-neutral-800 dark:border dark:border-neutral-700 dark:divide-neutral-700 after:h-4 after:absolute after:-bottom-4 after:start-0 after:w-full before:h-4 before:absolute before:-top-4 before:start-0 before:w-full" aria-labelledby="hs-dropdown-default">
                   
                    <div class="m-1 hs-dropdown relative " data-hs-dropdown-auto-close="inside">
                        <button id="hs-dropdown-item-checkbox" type="button" class="hs-dropdown-toggle py-3 px-4 inline-flex items-center gap-x-2 text-sm font-medium rounded-lg  bg-none text-gray-800 shadow-sm hover:bg-gray-50 disabled:opacity-50 disabled:pointer-events-none  dark:hover:bg-neutral-800  dark:hover:text-white w-full" >
                            Account Details
                        </button>

                        <div class="hs-dropdown-menu z-10 transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-96 bg-white shadow-md rounded-lg p-2 mt-2 white:bg-neutral-800 dark:border dark:border-neutral-700" aria-labelledby="hs-dropdown-item-checkbox">
                            <div class=" w-full relative flex  justify-between  py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Account Details</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Brokerage & Account Balance</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Funds & Account Balance</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">IPO, OFS</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Margin Pledge & margin Trading Facility</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Mutual Funds</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Onboarding</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Order Related</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Portfolio & Corporate Action</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Research Recommendations</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Statements</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                        </div>
                    </div>

                    <div class="m-1 hs-dropdown relative " data-hs-dropdown-auto-close="inside">
                        <button id="hs-dropdown-item-checkbox" type="button" class="hs-dropdown-toggle py-3 px-4 inline-flex items-center gap-x-2 text-sm font-medium rounded-lg  bg-none text-gray-800 shadow-sm hover:bg-gray-50 disabled:opacity-50 disabled:pointer-events-none  dark:hover:bg-neutral-800  dark:hover:text-white w-full">
                            Brokerage & Other charges
                        </button>

                        <div class="hs-dropdown-menu z-10 transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-96 bg-white shadow-md rounded-lg p-2 mt-2 white:bg-neutral-800 dark:border dark:border-neutral-700" aria-labelledby="hs-dropdown-item-checkbox">
                            <div class=" w-full relative flex  justify-between  py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Account Details</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Brokerage & Account Balance</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Funds & Account Balance</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">IPO, OFS</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Margin Pledge & margin Trading Facility</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Mutual Funds</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Onboarding</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Order Related</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Portfolio & Corporate Action</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Research Recommendations</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Statements</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                        </div>
                    </div>

                    <div class="m-1 hs-dropdown relative " data-hs-dropdown-auto-close="inside">
                        <button id="hs-dropdown-item-checkbox" type="button" class="hs-dropdown-toggle py-3 px-4 inline-flex items-center gap-x-2 text-sm font-medium rounded-lg  bg-none text-gray-800 shadow-sm hover:bg-gray-50 disabled:opacity-50 disabled:pointer-events-none  dark:hover:bg-neutral-800  dark:hover:text-white w-full">
                            Funds & Account Balance
                        </button>

                        <div class="hs-dropdown-menu z-10 transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-96 bg-white shadow-md rounded-lg p-2 mt-2 white:bg-neutral-800 dark:border dark:border-neutral-700" aria-labelledby="hs-dropdown-item-checkbox">
                            <div class=" w-full relative flex  justify-between  py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Account Details</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Brokerage & Account Balance</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Funds & Account Balance</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">IPO, OFS</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Margin Pledge & margin Trading Facility</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Mutual Funds</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Onboarding</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Order Related</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Portfolio & Corporate Action</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Research Recommendations</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Statements</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                        </div>
                    </div>
                   
                    <div class="m-1 hs-dropdown relative " data-hs-dropdown-auto-close="inside">
                        <button id="hs-dropdown-item-checkbox" type="button" class="hs-dropdown-toggle py-3 px-4 inline-flex items-center gap-x-2 text-sm font-medium rounded-lg  bg-none text-gray-800 shadow-sm hover:bg-gray-50 disabled:opacity-50 disabled:pointer-events-none  dark:hover:bg-neutral-800  dark:hover:text-white w-full">
                            IPO, OFS
                        </button>

                        <div class="hs-dropdown-menu z-10 transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-96 bg-white shadow-md rounded-lg p-2 mt-2 white:bg-neutral-800 dark:border dark:border-neutral-700" aria-labelledby="hs-dropdown-item-checkbox">
                            <div class=" w-full relative flex  justify-between  py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Account Details</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Brokerage & Account Balance</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Funds & Account Balance</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">IPO, OFS</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Margin Pledge & margin Trading Facility</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Mutual Funds</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Onboarding</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Order Related</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Portfolio & Corporate Action</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Research Recommendations</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                            <hr>
                            <div class="relative flex items-start py-3 px-3 rounded-lg hover:bg-gray-100 dark:hover:bg-neutral-700">
                            <div class="w-full">
                                <label for="hs-dropdown-item-radio-delete">
                                <span class="block text-sm font-semibold text-gray-800 dark:text-black-300 dark:hover:text-white">Statements</span>
                                </label>
                            </div>
                            <div class="flex items-center  mt-1">
                                <input id="hs-dropdown-item-radio-delete" name="hs-dropdown-item-radio" type="radio" class="shrink-0 border-gray-200 rounded-full text-blue-600 focus:ring-blue-500 disabled:opacity-50 disabled:pointer-events-none dark:bg-neutral-800 dark:border-neutral-700 dark:checked:bg-blue-500 dark:checked:border-blue-500 dark:focus:ring-offset-gray-800" aria-describedby="hs-dropdown-item-radio-delete-description" checked>
                            </div>
                            </div>
                        </div>
                    </div>
                </div>
         </div>
    </div>
    <div class="w-100 p-5 border-2 border-solid border-red-500 flex justify-center items-center flex-col gap-5">
        <h1 style="font-size: 2rem;">Viwe PDF File</h1>
          <NuxtLink to="/gowtham.pdf" class="bg-red-400 rounded text-white p-2" external>
            View CV
          </NuxtLink>
    </div>
    <div class="w-100 p-5 border-2 border-solid border-red-500 flex justify-center items-center flex-col gap-5">
        <h1 style="font-size: 2rem;"> PDF File</h1>
        <iframe :src="pdfUrl" width="100%" height="600px"></iframe>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      pdfUrl:'/gowtham.pdf' 
    }
  }
}
</script>

<style>

</style>