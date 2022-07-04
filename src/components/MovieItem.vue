<template>
  <div>{{ movie.imdbID }}</div>
</template>

<script>
export default {
  props: {
    movie: {
      type: Object,
      default: () => ({})
      //일반함수->default: function () {return {}}
    }
  }
}
</script>