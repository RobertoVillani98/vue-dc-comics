<template>
  <a href="#" class="card">
    <img :src="comicImg" :alt="comicTitle" />
    <span>{{ comicTitle }}</span>
  </a>
</template>

<script>
export default {
  name: "ComicCard",
  props: {
    comicImg: String,
    comicTitle: String,
  },
};
</script>

<style lang="scss" scoped>
.card {
  display: flex;
  flex-direction: column;

  img {
    width: 100%;
    max-height: 180px;
    object-fit: cover;
    object-position: top;
  }

  span {
    color: #fff;
    text-transform: uppercase;
    margin-top: 20px;
  }
}
</style>
