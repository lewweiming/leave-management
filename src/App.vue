<template>
    <div id="app">

        <div class="container mx-auto max-w-xl">

            <!-- Start -->
            <div class="font-bold text-xl text-center my-4 border-b-2 border-black">
                Leave Management System
            </div>
            
            <!-- Info Dashboard -->
            <div class="font-light text-xl my-6 border-b">
                Remaining Leave: 60 days
            </div>
            
            <!-- Features -->
            <div class="my-6 border-b">
                <div class="uppercase border-b-2 border-black">
                    Features
                </div>
                <ol class="list-disc">
                    <li>
                        Keeps a record of leaves taken
                    </li>
                </ol>
            </div>

            <!-- Datepicker -->
            <form class="w-full max-w-lg">
                <div class="flex flex-wrap -mx-3 mb-6">
                    <div class="w-1/2 px-3">
                        <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-last-name">
                            Date Start
                        </label>
                        <input class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="Doe">
                    </div>
                    <div class="w-1/2 px-3">
                        <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-last-name">
                            Date End
                        </label>
                        <input class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="Doe">
                    </div>
                </div>
            </form>

            <!-- Action, Row -->
            <div class="py-3 text-center">

                <div class="border-2 border-gray-400 px-3 py-1 rounded-full inline-block text-gray-500">
                    Apply for Leave
                </div>
            </div>



        </div>

    </div>
</template>

<script>
    //import HelloWorld from './components/HelloWorld.vue'

    export default {
        name: 'app',
        components: {

        }
    }

</script>
