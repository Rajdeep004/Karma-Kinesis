<script setup>
const serviceList = [
    {
        title: "Aerobics",
        content: "Experience the exhilaration of aerobics, a dynamic form of exercise that combines rhythmic movements with music to elevate your heart rate and invigorate your body. Join us for energetic workouts that will leave you feeling refreshed, revitalized, and ready to conquer your fitness goals!",
        image: "/img/yoga1.jpg"
    },
    {
        title: "Pilates",
        content: "Discover the transformative power of Mat Pilates, a dynamic and low-impact exercise method designed to strengthen the body's core muscles, improve flexibility, and enhance overall posture and alignment. Whether you're a beginner or a seasoned practitioner, our sessions offer a supportive and nurturing environment to help you achieve balance, stability, and a sense of well-being.",
        image: "/img/yoga2.jpg"
    },
    {
        title: "Prenatal & postnatal",
        content: "Embrace the journey of motherhood with our specialized prenatal and postnatal exercise classes. Join our supportive community and experience the benefits of tailored exercises that cater to the unique needs of pregnancy and early motherhood.",
        image: "/img/yoga3.jpg"
    }
]
</script>

<template>
    <section id="services" class="container mx-auto  border-t-2 mt-8">
        <h1 class="text-center mt-10 text-2xl lg:text-4xl font-light">Breathe, Stretch, and Welcome</h1>
        <h2 class="text-center text-xl lg:text-2xl font-light">Let your KARMA in motion</h2>
        <div 
            class="flex flex-col lg:flex-row gap-8 p-5 lg:m-10"
        >
            <ServiceCard 
                v-for="service in serviceList"
                :title="service.title"
                :content="service.content"
                :image="service.image"
            />
        </div>
    </section>
    <h6 class="text-center text-xl lg:text-2xl font-light underline"><a href=""> Explore More Services </a></h6>
</template>

<style lang="postcss" scoped>
    
</style>