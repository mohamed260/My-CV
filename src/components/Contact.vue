<template>
    <div id="contact" class="mt-3">
       <h1 class="text-2xl font-semibold text-indigo-500 text-center md:text-3xl" style="font-family: serif;">Contact</h1> 
    <section class="w-full max-w-2xl px-6 py-4 mx-auto mb-3 bg-white rounded-md md:shadow-lg dark:bg-gray-800">
        <h2 style="font-family: serif;" class="text-3xl font-semibold text-center text-gray-800 dark:text-white">Get In Touch</h2>
        <p class="mt-3 text-center text-gray-600 dark:text-gray-400">Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
        
        <div class="grid grid-cols-1 gap-6 mt-6 sm:grid-cols-2 md:grid-cols-3">
            <a href="https://www.google.com/maps/place/%D8%A3%D9%85%D8%A8%D8%AF%D8%A9%D8%8C+%D8%A7%D9%84%D8%B3%D9%88%D8%AF%D8%A7%D9%86%E2%80%AD/@15.7534999,32.4570593,11z/data=!3m1!4b1!4m13!1m7!3m6!1s0x168e8bf303b5ade3:0xffa2d3531b1ae48f!2z2KPZhSDYr9ix2YXYp9mG2Iwg2KfZhNiz2YjYr9in2YY!3b1!8m2!3d15.6475782!4d32.4806894!3m4!1s0x168e5fb15d0b919f:0x1fb29949403bc746!8m2!3d15.6858485!4d32.310791?hl=ar&authuser=0" class="flex flex-col items-center px-4 py-3 text-gray-700 rounded-md dark:text-gray-200 hover:bg-blue-200 dark:hover:bg-blue-500">
                <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                    <path fill-rule="evenodd" d="M5.05 4.05a7 7 0 119.9 9.9L10 18.9l-4.95-4.95a7 7 0 010-9.9zM10 11a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd" />
                </svg>

                <span class="mt-2">121 Street, KH</span>
            </a>

            <a href="https://api.whatsapp.com/send?phone=249999881841" class="flex flex-col items-center px-4 py-3 text-gray-700 rounded-md dark:text-gray-200 hover:bg-blue-200 dark:hover:bg-blue-500">
                <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                    <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z" />
                </svg>

                <span class="mt-2">+249999881841</span>
            </a>

            <a href="https://mail.google.com/mail/u/0/#inbox/FMfcgxwLtkQsspnzRcnpdGTTgLcQcXGb?compose=new" class="flex flex-col items-center px-4 py-3 text-gray-700 rounded-md dark:text-gray-200 hover:bg-blue-200 dark:hover:bg-blue-500">
                <svg class="w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
                    <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z" />
                    <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z" />
                </svg>

                <span class="mt-2">wwwalboss10@gmail.com</span>
            </a>
        </div>
        
        <div class="mt-6 ">
            <div class="items-center -mx-2 md:flex">
                <div class="w-full mx-2">
                    <label class="block mb-2 text-sm font-medium text-gray-600 dark:text-gray-200">Name</label>
                
                    <input class="block w-full px-4 py-2 text-gray-700 bg-white border border-gray-300 rounded-md dark:bg-gray-800 dark:text-gray-300 dark:border-gray-600 focus:border-blue-500 dark:focus:border-blue-500 focus:outline-none focus:ring" type="text">
                </div>

                <div class="w-full mx-2 mt-4 md:mt-0">
                    <label class="block mb-2 text-sm font-medium text-gray-600 dark:text-gray-200">E-mail</label>

                    <input class="block w-full px-4 py-2 text-gray-700 bg-white border border-gray-300 rounded-md dark:bg-gray-800 dark:text-gray-300 dark:border-gray-600 focus:border-blue-500 dark:focus:border-blue-500 focus:outline-none focus:ring" type="email">
                </div>
            </div>

            <div class="w-full mt-4">
                <label class="block mb-2 text-sm font-medium text-gray-600 dark:text-gray-200">Message</label>

                <textarea class="block w-full h-40 px-4 py-2 text-gray-700 bg-white border border-gray-300 rounded-md dark:bg-gray-800 dark:text-gray-300 dark:border-gray-600 focus:border-blue-500 dark:focus:border-blue-500 focus:outline-none focus:ring"></textarea>
            </div>

            <div class="flex justify-center mt-6">
                <button class="px-4 py-2 text-white transition-colors duration-200 transform bg-indigo-600 rounded-md hover:bg-indigo-500 focus:outline-none focus:bg-indigo-500">Send Message</button>
            </div>
        </div>
    </section>
    </div>
</template>

<!--
<script src="https://smtpjs.com/v3/smtp.js"></script>
<script>
export default {
    data() {
       return{
            name: '',
            email: '',
            message: ''
       }
        
    
    },

    methods: {
        sendEmail(){
            Email.send({
            SecureToken : "329596b9-fe92-4901-819b-202364c6dfa6", 
            Host : "smtp.gmail.com",
            Username : "foxfox2600@gmail.com",
            Password : "0999881841m",
            To : "foxfox2600@gmail.com",
            From : this.email,
            Subject : this.name,
            Body : this.message,
            }).then(
                message => alert(message)
            );

           
        }
    }
}
</script>

-->