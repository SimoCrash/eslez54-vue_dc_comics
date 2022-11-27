<template>
  <div>
    <div class="contents">
        <img :src="imgFilm" alt="">
        <h4> {{ titleFilm }}</h4>
    </div>
  </div>
</template>

<script>
export default {
    name: 'cardFilm',
    props: {
        imgFilm: String,
        titleFilm: String,
    },
}
</script>

<style lang="scss" scoped>
    .contents {
        background-color: #1c1c1c;
        img {
            max-width: 100%;
            margin-bottom: 0.4rem;
        }
        h4 {
            text-transform: uppercase;
            color: white;
            margin-top: 10px;
        }
    }
</style>