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
                        <img class="w-full h-full max-w-2xl" src="https://scontent.fkrt3-1.fna.fbcdn.net/v/t1.6435-0/s526x395/165241187_473599713777544_5065120083423228563_n.jpg?_nc_cat=111&ccb=1-3&_nc_sid=09cbfe&_nc_eui2=AeFfoPQkdzw5DbCrkddTJl50jC15bLu6mZqMLXlsu7qZmhEp6v3iGpq1XbLC29kZTh2U_Xjw2dmdqIj0I3WeMHk-&_nc_ohc=bll6QZAM_O4AX92doy2&_nc_ht=scontent.fkrt3-1.fna&tp=7&oh=2af77a90fe673dc8f1fe3741240a0f91&oe=60A8BD8F" alt="">
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