<template>
    <section class="bg-gray-100 py-6 px-4 md:px-10 rounded-lg shadow-md max-w-sm mx-auto my-10 border border-gray-200">
        <h2 class="font-bold text-4xl text-gray-800 mb-2 text-center">Contact Us</h2>
        <form class="space-y-4">
            <div>
                <label for="name" class="block text-gray-700 font-medium mb-1 text-sm">Name</label>
                <input id="name" type="text" placeholder="Your name" class="w-full border border-gray-300 bg-white rounded px-3 py-2"/>
            </div>
      
            <div>
                <label for="email" class="block text-gray-700 font-medium mb-1 text-sm">Email</label>
                <input id="email" type="email" placeholder="Your email" class="w-full border border-gray-300 bg-white rounded px-3 py-2"/>
            </div>
      
            <div>
                <label for="message" class="block text-gray-700 font-medium mb-1 text-sm">Message</label>
                <input id="message" rows="3" placeholder="Your message" class="w-full border border-gray-300 bg-white rounded px-3 py-2">
            </div>
      
            <button type="submit" class="w-full bg-blue-400 hover:bg-gray-400 text-white font-medium py-2">Send</button>
        </form>
    </section>
</template>


<script setup>

</script>

<style scoped>

</style>
