<script setup>

</script>

<template>
    <section id="connect" class="container mx-auto  border-t-2 mt-11  flex items-center md:p-10">
        <form action="#" class="w-full flex p-7 flex-col gap-4 md:w-3/4 h-1/2">
            <div class="flex flex-col gap-4">
                <h1 class="text-3xl font-medium">Sign up for our Classes</h1>
                <h2 class="text-lg">To be invited to the nearest Cali centerand get free physical advice to learn more about the program.</h2>
            </div>
            <div class="flex flex-col gap-4">
                <div class="flex flex-col gap-4 md:flex-row  lg:w-3/4">
                    <input type="text" placeholder="First Name" class="p-3 rounded-3xl border-2 border-gray-300 active:border-gray-300 lg:w-full">
                    <input type="text" placeholder="Last Name" class="p-3 rounded-3xl border-2 border-gray-300 lg:w-full">
                </div>
                <div class="flex flex-col gap-4 md:flex-row  lg:w-3/4">
                    <input type="email" placeholder="Your Email" class="p-3 rounded-3xl border-2 border-gray-300 lg:w-full">
                    <input type="tel" placeholder="Phone number" class="p-3 rounded-3xl border-2 border-gray-300 lg:w-full">
                </div>
            </div>
            <div class="flex">
                <textarea name="" id="" cols="30" rows="10" placeholder="Message" class="p-5 rounded-3xl border-2 border-gray-300 w-full resize-none lg:w-3/4"></textarea>
                <div class="hidden lg:flex justify-center items-center -ml-8"><Icon name="system-uicons:arrow-up" class="bg-gradient-to-br from-[#f1a879] to-[#e97163] text-6xl p-4 rounded-full"/></div>
            </div>
            <button class="bg-gradient-to-br from-[#f1a879] to-[#e97163] flex justify-center py-3 rounded-3xl font-bold text-xl lg:w-1/4">GET STARTED</button>
        </form>
    </section>
</template>

<style lang="postcss" scoped>
    
</style>