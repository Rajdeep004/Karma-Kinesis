<script setup>
    const isActive = ref(false)
    const toggle = () => {
        isActive.value=!isActive.value
    }
</script>



<template>
    <div class="min-h-[730px] w-full rounded-[70px] flex justify-center" style="background-image:url(/img/yoga1.jpg); background-position: center; background-size: cover;">
        <div class="flex w-full rounded-[70px] flex-col justify-between" :class="isActive? 'bg-black/60':''">
            <div class="flex flex-col text-white justify-center items-center self-start">
                <h1 class="">Yoga & Power Yoga</h1>
                <p class="w-11/12">Yoga harmonizes mind and body; Power Yoga intensifies it with a focus on strength and flexibility Yoga harmonizes mind and body; Power Yoga intensifies it with a focus on strength and flexibility</p>
            </div>
            <button @click="toggle" class="text-white text-4xl border-4 border-[#3CB333] py-2 mb-5 rounded-3xl">Yoga & Power Yoga</button>
        </div>
    </div>
</template>