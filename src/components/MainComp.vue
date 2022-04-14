<template>
<div class="main">
    <div class="main-container">    
    <div class="content">
        CONTENT GOES HERE!!
    </div>
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
.main{
    background-color: black;        
}
.main-container{
    width: 80%;
    padding: 0 20px;
    margin: 0 auto;
    color: white;
    /* TO DELETE */    
    height: 20vh;
}
/* TO DELETE */
.content{
    padding: 80px 20px;
}
</style>