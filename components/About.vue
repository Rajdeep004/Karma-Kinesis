<template>
    <div id="about">
        <div class="top">
            <h1>Breathe, Stretch, and Welcome</h1>
            <h2>Let Your KARMA be in Motion</h2>
        </div>
        <div class="btm">
            <div class="lft-btm">
                <img src="/img/da19c5ef4dde41c89ffbe5623d8fd333.png" alt="">
            </div>
            <div class="rght-btm">
                <div class="top-rght-btm">
                    <div class="one"><img src="/img/Vector.svg" alt=""></div>
                    <div class="two">
                        <h1>Breathe, Stretch, and Welcome</h1>
                        <h2>Breathe, Stretch, and Welcome Breathe, Stretch, and Welcome Breathe, Stretch, and Welcome      </h2></div>
                </div>
                <div class="cntr-rght-btm">
                    <div class="one"><img src="/img/Vector (1).svg" alt=""></div>
                    <div class="two">
                        <h1>Breathe, Stretch, and Welcome</h1>
                        <h2>Breathe, Stretch, and Welcome Breathe, Stretch, and Welcome Breathe, Stretch, and Welcome      </h2></div>
                </div>
                <div class="btm-rght-btm">
                    <div class="one"><img src="/img/Vector (2).svg" alt=""></div>
                    <div class="two">
                        <h1>Breathe, Stretch, and Welcome</h1>
                        <h2>Breathe, Stretch, and Welcome Breathe, Stretch, and Welcome Breathe, Stretch, and Welcome      </h2></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="postcss" scoped>
    #about{
        @apply w-full h-[100vh] mt-[10vh] border-t-2 border-[#cacaca] 
    }
    .top{
        @apply  flex flex-col text-center mt-[8vh]
    }
    h1{
        @apply text-[1.7vw]
    }
    h2{
        @apply text-[1vw] 
    }

    .top h1{
        @apply text-[2vw]
    }
    .top h2{
        @apply text-[1.5vw];
    }
    .btm{
        @apply  w-full h-[81vh] flex
    }
    .lft-btm{
        @apply w-[50%] h-full  flex justify-center items-center
    }
    .lft-btm img{
        @apply h-full w-auto mb-[15%]
    }
    .rght-btm{
        @apply h-full w-[50%]  
    }
    .top-rght-btm{
        @apply w-full h-[33.3%]  flex gap-[3vw] justify-center items-end
    }
    .cntr-rght-btm{
        @apply w-full h-[33.3%]  flex gap-[3vw] justify-center items-center
    }
    .btm-rght-btm{
        @apply w-full h-[33.3%]  flex gap-[3vw] justify-center items-start
    }
    .two{
        @apply w-[50%]
    }
</style>