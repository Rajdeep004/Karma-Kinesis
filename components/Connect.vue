<template>
    <section id="connect" class="container mx-auto border-t-2 mt-11  flex items-center justify-center md:p-10">
        <form action="#" class="w-full flex p-7 flex-col items-center gap-4 md:w-3/4 h-1/2 relative">
            <SvgDil class="lg:absolute right-16 top-4"/>
            <h1 class="text-4xl font-medium">Sign up for our Classes</h1>
            <div class="flex flex-col gap-4 w-full items-center ">
                <div class="flex flex-col gap-4 md:flex-row lg:w-3/4 w-full">
                    <input type="text" placeholder="First Name" class="p-3 rounded-3xl border-2 border-gray-300 active:border-gray-300 lg:w-full">
                    <input type="text" placeholder="Last Name" class="p-3 rounded-3xl border-2 border-gray-300 lg:w-full">
                </div>
                <div class="flex flex-col gap-4 md:flex-row lg:w-3/4 w-full relative">
                    <input type="email" placeholder="Your Email" class="p-3 rounded-3xl border-2 border-gray-300 lg:w-full">
                    <input type="tel" placeholder="Phone number" class="p-3 rounded-3xl border-2 border-gray-300 lg:w-full">
                    
                </div>
            </div>
            <div class="flex w-full justify-center relative">
                <SvgLeaf class="hidden lg:block absolute !bottom-0 !right-64 -z-20"/>
                <SvgLeaf2 class="hidden lg:block absolute !bottom-0 left-60 -z-20" />
                <textarea name="" id="" cols="20" rows="10" placeholder="Message" class="p-5 rounded-3xl border-2 border-gray-300 w-full resize-none lg:w-3/4 lg:absolute"></textarea>
                <!-- <button class="hidden lg:flex justify-center items-center -ml-8"><Icon name="system-uicons:arrow-up" class="bg-gradient-t-br bg-[#3CB333] from-[#f1a879] to-[#e97163] text-6xl p-4 text-white rounded-full cursor-pointer"/></button> -->
            </div>
            <button class="bg-gradient-t-br bg-[#3CB333] text-white from-[#f1a879] to-[#e97163] flex justify-center py-3 rounded-3xl font-bold text-xl w-full lg:w-1/4 mt-4">Submit</button>
        </form>
    </section>
</template>