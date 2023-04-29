<script setup>
import HomeCard from '../components/HomeCard.vue'
</script>

<template>
    <div class="p-8">
        <button
            type="button" 
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Podcast to make you smarter
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button" 
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Recommended Radio
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button" 
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Recommended Songs
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/33/300/300" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>
</template>
