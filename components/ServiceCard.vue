<script setup>
    defineProps({
        title: String,
        content: String,
        image: String
    })

    const isActive = ref(false)
    const toggle = () => {
        isActive.value = !isActive.value
    }
</script>



<template>
    <div 
        class="min-h-[70vh]  w-full rounded-[70px] flex justify-center bg-cover bg-center" 
        :style="{backgroundImage: `url(${image})`}"
    >
        <div 
            class="flex w-full rounded-[70px] text-white transition-all ease-out duration-"
            :class="isActive? 'bg-black/60 flex-col justify-between items-center' : 'justify-center' "
        >
            <div
                v-show="isActive" 
                class="self-start m-8 space-y-2"
            >
                <h1 class="text-3xl">{{title}}</h1>
                <p class="">{{ content }}</p>
            </div>
            <button 
                @mouseover="isActive = true"
                @mouseleave="isActive = false"
                class="text-3xl py-4 w-4/5 mb-5 rounded-full bg-black/10 transition-all ease-in duration-150"
                :class="isActive? 'justify-self-end border-4 border-[#3CB333]' : 'self-end bg-[#3CB333] border-white border-2' "
                v-text="isActive? 'Explore Now' : title"
            ></button>
        </div>
    </div>
</template>