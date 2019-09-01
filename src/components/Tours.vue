<template lang="html">
  <div class="tours">
  <div v-for="tour in tours">
    <Tour :destination='tour.destination' :date='tour.date' :description='tour.description' :imgurl='tour.imgurl'/>
  </div>
</div>
</template>

<script>
import Tour from './Tour.vue'
export default {
  name: 'Tours',
  components: {
    Tour
  },
  data: () => {
    return {
      tours: [
        {
          destination: 'Odessa',
          date: '13.12.19',
          description: 'Trip to Odessa-mama',
          imgurl: require('../assets/odessa.jpg'),
        },
        {
          destination: 'Odessa',
          date: '13.12.19',
          description: 'Trip to Odessa-mama',
          imgurl: require('../assets/odessa.jpg'),
        },
        {
          destination: 'Odessa',
          date: '13.12.19',
          description: 'Trip to Odessa-mama',
          imgurl: require('../assets/odessa.jpg'),
        },
        {
          destination: 'Odessa',
          date: '13.12.19',
          description: 'Trip to Odessa-mama',
          imgurl: require('../assets/odessa.jpg'),
        },
        {
          destination: 'Odessa',
          date: '13.12.19',
          description: 'Trip to Odessa-mama',
          imgurl: require('../assets/odessa.jpg'),
        }
      ]
    }
  }
}
</script>

<style lang="css" scoped>
</style>
