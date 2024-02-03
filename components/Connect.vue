<script setup>

</script>

<template>
    <div id="connect">
        <form action="#">
            <div class="txt">
                <h1>Sign up for our classes</h1>
                <p>To be invited to the nearest Cali center and get free physical advice to learn more about the program.</p>
            </div>
            <div class="input">
                <div class="lft-input">
                    <input type="text" placeholder="First Name">
                    <input type="email" placeholder="Your Email">
                </div>
                <div class="rght-input">
                    <input type="text" placeholder="Last Name">
                    <input type="number" placeholder="Phone Number">
                </div>
            </div>
            <div class="msg">
                <textarea name="text" id="" cols="30" rows="10" placeholder="Message"></textarea>
                <Icon name="system-uicons:arrow-up" class="icon"/>
            </div>
            <button>Get started</button>
        </form>
    </div>
</template>

<style lang="postcss" scoped>
    #connect{
        @apply w-full h-[100vh] mt-[10vh] border-t-2 border-[#cacaca] flex items-center 
    }
    form{
        @apply w-[50%] h-[80%] ml-[10vw] flex flex-col gap-[5vh]  mt-[5vh]
    }
    .txt{
        @apply ml-[2.5vw]
    }

    .txt h1{
        @apply text-[2.5vw]
    }
    .txt p{
        @apply text-[1.2vw]
    }
    .input{
        @apply  ml-[1vw] flex gap-[1vw] justify-between flex-row
    }
    .lft-input{
        @apply flex flex-col gap-[4vh] w-[50%] 
    }
    input{
        @apply px-[1.5vw] py-[1.5vh] w-[90%] border-[1px] rounded-[30px] text-[110%] border-gray-300 bg-gray-100
    }
    .rght-input{
      @apply flex flex-col gap-[4vh] w-[50%] 
    }
    .msg{
        @apply   mt-[10vh] px-[2vw] flex items-center
    }
    textarea{
        @apply resize-none w-[100%] px-[2vw] py-[2vh] text-[1.1vw] h-[30vh] bg-gray-100 rounded-[10px] border-[1px] border-gray-300 text-gray-400
    }
    .icon{
        @apply text-[4vw] text-white rounded-full ml-[-2vw] bg-gradient-to-br from-[#e86860] to-[#ee9672] px-[1vw] 
    }
    button{
        @apply text-[1.2vw] py-[1.3vh] rounded-[30px] w-[20%]  bg-gradient-to-tl text-white from-[#e86860] to-[#ee9672] flex ml-[2vw] px-[0vw] justify-center items-center
    }

</style>