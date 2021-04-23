<template>
    <div id="home" class="m">
        
        <header class="bg-white dark:bg-gray-800">
        

            <div class=" shadow-lg px-6 py-16 mx-full my-4">
                <div class="items-center md:flex">
                    <div class="w-full md:w-1/2">
                        <div class="max-w-lg">
                            <h1 style="font-family: serif;" class="text-4xl font-bold text-gray-800 dark:text-white md:text-5xl">Hi,<br> I'am <span class="text-indigo-500">Mohamed</span> Web Developer And Designer</h1>
                            <button @click="contact()" class="px-3 py-2 mt-4 text-sm font-medium text-white bg-indigo-500 rounded-md hover:bg-indigo-600 hover:shadow-lg focus:outline-none focus:bg-indigo-600">Contact</button>
                        </div>
                    </div>
            
                    <div class="flex items-center justify-center w-full mt-6 md:mt-0 md:w-1/2">
                        <img class="w-full h-full max-w-2xl" src="https://avatars.githubusercontent.com/u/50184103?s=400&u=a4a7e9ae59f8c710292028ac8eb8629801a25bd4&v=4" alt="">
                    </div>
                </div>
            </div>
        </header>
    </div>
</template>

<script>
export default {
    methods: {
        contact(){
            alert("Contact Me At +249999881841");
        }
    }
}
</script>