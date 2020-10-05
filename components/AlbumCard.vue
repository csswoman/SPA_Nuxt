<template>
  <div class="column is-one-quarter">
    <div class="box">
      <h3>{{ album.title }}</h3>
      <a class="button is-primary" href="#">Ver álbum</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "AlbumCard",
  props: {
    album: Object,
  },
};
</script>

<style scoped>
.box {
  padding: 1em;
}

h3 {
  min-height: 5em;
}
</style>
