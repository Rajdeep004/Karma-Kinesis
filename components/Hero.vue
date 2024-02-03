<script setup>

</script>

<template>
    <section id="hero">
        <div class="txt">
            <h3>Let your <span>KARMA</span> be in motion</h3>
            <h1>KARMA KINESIS</h1>
        </div>
        <img src="/img/ffb62e0854eb1ba594e56725937f119d.png" alt="girl yoga">
        <div class="btns">
            <div class="lft-btn">
                <p>&#9679;</p>
                <p>&#9679;</p>
                <p>&#9679;</p>
            </div>
            <div class="rght-btn">
                Yaha icons aayege 
            </div>
        </div>
    </section>
</template>

<style lang="postcss" scoped>
    #hero{
        @apply w-full  h-[90vh] flex flex-col items-center relative;
    }
    .txt{
        @apply  relative mt-[10vh]

    }
    h3{
        font-size: 3vw;
        position: absolute;
        bottom: 75%;
    }
    span{
        font-style: italic;
    }
    h1{
        @apply bg-gradient-to-r from-[#4AD75B] to-[#38AD2F] text-[10vw] text-transparent bg-clip-text font-semibold;
    }
    img{
        @apply  w-[75vw] h-[94vh] absolute right-[15vw]
    }
    .btns{
        @apply w-full h-[10vh] absolute top-[80vh] flex justify-between
    }
    .lft-btn{
        @apply  w-[30%] h-full flex gap-2 text-[120%] justify-center items-center text-[#969696]
    }
    .lft-btn :nth-child(1){
        color: black;
    }
    .rght-btn{
        @apply  w-[40%] h-full flex justify-center items-center
    }


</style>