<template>
  <div class="main-container">    
    <div class="content">
        CONTENT GOES HERE!! 
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainComp',
  props: {
    msg: String
  }
}
</script>

<style lang="scss">
.main-container{
    width: 80%;
    padding: 0 20px;
    margin: 0 auto;

    /* TO DELETE */
    background-color: red;
    height: 20vh;
}
/* TO DELETE */
.content{
    padding: 70px;
}
</style>