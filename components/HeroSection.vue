<template>
    <section id="hero" class="h-screen w-screen bg-dark grid place-content-center place-items-center gap-16 pt-32">
        <div class="text-white text-4xl text-center font-semibold">
            <p>HI, I’M MARTÍ PAREDES</p>
            <p class="bg-gradient-to-r from-primary to-secondary inline-block text-transparent bg-clip-text">
                FRONT-END DEVELOPER</p>
            <div class="font-extralight text-base mt-4">
                <p>Creating immersive digital experiences with a focus on design and functionality.</p>
            </div>
        </div>

        <button class="text-white border-2 border-white w-fit p-2 rounded-full uppercase hover:bg-white hover:text-dark transition-colors">Start the journey</button>

        <span class="relative aspect-[1/2] h-15 rounded-full border-2 border-white"><span class="m-2 mt block rounded-full bg-white aspect-square w-6 animate" /></span>
    </section>
</template>

<script setup>

</script>

<style scoped>

.animate {
    -webkit-animation: mover 1s infinite  alternate;
    animation: mover 1s infinite  alternate;
}


@keyframes mover {
    0% { transform: translateY(0); }
    100% { transform: translateY(45px); }
}


</style>