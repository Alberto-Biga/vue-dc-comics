<template>
  <div>
      <div class="card">
          <img :src="thumb" alt="">
          <!-- <h3>{{series}}</h3> -->
      </div>
  </div>
</template>

<script>
export default {
  name: 'CardFumetto',  
  props: {
      thumb: String,
      series: String
  }
}
</script>

<style lang="scss">

</style>
