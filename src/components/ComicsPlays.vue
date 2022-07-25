<template>
    <ul>
        <li class="comic-card">
            <figure>
                <img :src="play.thumb" :alt="play.series">
            </figure>
            <figcaption>
                <h5>{{ play.series }}</h5>
            </figcaption>

        </li>
    </ul>

</template>

<script>
export default {
    name: "ComicsPlays",
    props: {
        play: Object
    }
}
</script>

<style lang="scss" scoped>
.comic-card {
    flex-basis: 25%;
    padding: 10px;

    img {
        display: block;
    }
}
</style>