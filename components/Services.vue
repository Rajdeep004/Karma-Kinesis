<script setup>

</script>

<template>
    <div id="services">
        <div class="top">
            <h1>Breathe, Stretch, and Welcome</h1>
            <h2>Let Your KARMA be in Motion</h2>
        </div>
        <div class="cntr">
            <div class="one"></div>
            <div class="two">
                <h1>Yoga & Power Yoga</h1>
            </div>
            <div class="three">
                <div class="txt">
                    <div class="up">
                        <h1>Yoga and Power Yoga</h1>
                        <p>Yoga harmonizes mind and body; Power Yoga intensifies it with a focus on strength and flexibility Yoga harmonizes mind and body; Power Yoga intensifies it with a focus on strength and flexibility</p>
                    </div>
                    <div class="down">
                        <h1>Enroll now</h1>
                    </div>
                </div>
            </div>
        </div>
        <div class="btm">
            <h1>Explore more services <Icon name="system-uicons:arrow-right" /></h1>
        </div>
    </div>
</template>

<style lang="postcss" scoped>
    #services{
        @apply w-full h-[100vh]  border-t-2 border-[#cacaca] 
    }
    .top{
        @apply  flex flex-col text-center mt-[8vh]
    }
    .top h1{
        @apply text-[2vw]
    }
    .top h2{
        @apply text-[1.5vw];
    }
    .cntr{
        @apply w-full h-[75vh] flex justify-between px-[10vw] py-[5vh]
    }
    .one{
        height: 100%;
        width: 30%;
        border-radius: 70px;
        background-image: url(img/yoga1.jpg);
        background-size: cover;
        background-position: center;
    }
    .two{
        height: 100%;
        width: 30%;
        border-radius: 70px;
        background-color: palevioletred;
        background-image: url(img/yoga2.jpg);
        background-size: cover;
        background-position: start;
        display: flex;
        justify-content: center;
        align-items: end;
    }

    .two h1{
        border: 3px solid #3CB333;
        padding: 0.5vh 1vw;
        font-size: 200%;
        margin-bottom: 3vh;
        border-radius: 50px;
    }

    .three{
        height: 100%;
        width: 30%;
        border-radius: 70px;
        background-color: palevioletred;
        background-image: url(img/yoga3.jpg);
        background-size: cover;
        background-position: center;
    }

    .txt{
        background-color: black;
        height: 100%;
        opacity: 70%;
        overflow: hidden;
        width: 100%;
        border-radius: 70px;
    }

    .up{
        /* background-color: #3CB333; */
        width: 100%;
        height: 50%;
        display: flex;
        flex-direction: column;
        color: white;
        justify-content: end;
        align-items: center;
    }

    .up h1{
        font-size: 220%;
    }
    .up p{
        font-size: 100%;
        padding: 1.5vh 1vw;
        padding-left: 3vw;
    }
    .down{
        height: 50%;
        display: flex;
        align-items: end;
        justify-content: center;
    }

    .down h1{
        border: 3px solid #3CB333;
        padding: 0.5vh 4vw;
        color: white;
        font-size: 200%;
        margin-bottom: 3vh;
        border-radius: 50px;
    }
    .btm{
        display: flex;
        width: 60%;
        align-items:center ;
        justify-content: end;
        height: 6.3vh;

    }
    .btm h1{
        font-size: 1.5vw;
    }
</style>