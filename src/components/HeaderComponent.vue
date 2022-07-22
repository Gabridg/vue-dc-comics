<template>
    <figure>
        <img src="../assets/img/dc-logo.png" alt="logo dc comics">
    </figure>
    <ul>
        <li v-for="link in links" :key="link.id">
            <a :href="link.url" :class="{ active: link.current }">{{ link.text }}"</a>
        </li>
    </ul>
</template>

<script>
export default {
    name: "HeaderComponent",
    data() {
        return {

            links: [
                {
                    id: 1,
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    id: 2,
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    id: 3,
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    id: 4,
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    id: 5,
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    id: 6,
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    id: 7,
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    id: 8,
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    id: 9,
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    id: 10,
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ]

        }
    }
}
</script>

<style>
</style>