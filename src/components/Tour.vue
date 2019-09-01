<template lang="html">
  <div class="tour">
    <p>{{ destination }}</p>
    <p>{{ date }}</p>
    <p>{{ description }}</p>
    <img :src=imgurl alt="">
   </div>
</template>

<script>
export default {
  name: 'Tour',
  props: {
    destination: String,
    date: String,
    description: String,
    imgurl: String,
  }
}
</script>

<style lang="css" scoped>
</style>
