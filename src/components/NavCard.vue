<template>

    <div id="nav">
        
        <nav class="fixed w-full bg-white shadow-lg dark:bg-gray-800">
            <div class=" px-6 py-3 mx-full md:flex md:justify-between md:items-center">
                <div class="flex items-center justify-between">
                    <div>
                        <a class="text-2xl font-bold text-indigo-500 dark:text-white md:text-2xl hover:text-indigo-400 dark:hover:text-indigo-300" href="#">
                            <img src="../assets/Untitled-2.png" class="w-12 h-5 md:w-16 md:h-6">
                        </a>
                    </div>
                    
                    <!-- Mobile menu button -->
                    <div class="flex md:hidden">
                        

                        <button @click="toggle" class="px-2 text-gray-500 hover:text-black focus:outline-none focus:text-black">
                            <svg class="h-6 w-6 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                            <path v-if="isOpen" fill-rule="evenodd" clip-rule="evenodd" d="M18.278 16.864a1 1 0 0 1-1.414 1.414l-4.829-4.828-4.828 4.828a1 1 0 0 1-1.414-1.414l4.828-4.829-4.828-4.828a1 1 0 0 1 1.414-1.414l4.829 4.828 4.828-4.828a1 1 0 1 1 1.414 1.414l-4.828 4.829 4.828 4.828z"/>
                            <path v-if="!isOpen" fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"/>
                            </svg>
                        </button>
                    </div>
                </div>

                <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
                <div class=" items-center md:flex" :class="{'hidden': !isOpen, 'block': isOpen }">
                    <div class="flex flex-col md:flex-row md:mx-6">
                        <a class="my-1 text-sm font-medium text-gray-700 dark:text-gray-200 hover:text-indigo-500 dark:hover:text-indigo-400 md:mx-4 md:my-0" href="#home">Home</a>
                        <a class="my-1 text-sm font-medium text-gray-700 dark:text-gray-200 hover:text-indigo-500 dark:hover:text-indigo-400 md:mx-4 md:my-0" href="#about">About</a>
                        <a class="my-1 text-sm font-medium text-gray-700 dark:text-gray-200 hover:text-indigo-500 dark:hover:text-indigo-400 md:mx-4 md:my-0" href="#skills">Skills</a>
                    </div>
                </div>
               
            </div>
        </nav>

        <!-- <div @click="isOpen = !isOpen" class="md:hidden" :class="{'absolute bg-gray-400 w-full h-full': isOpen, 'block': !isOpen }"></div> -->
    </div>

         

    
</template>

<script>
export default {
    data(){
        return{
            isOpen: false
        }
    },
    methods: {
        toggle(){
            this.isOpen = !this.isOpen
        }
    }
}
</script>