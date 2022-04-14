<template>
  <div class="nav">
    <div class="nav-container">
      <!-- LEFT NAV -->
      <div class="nav-img">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <!-- RIGHT NAV -->
      <div>
        <ul>
          <li>CHARACTERS</li>
          <li>COMICS</li>
          <li>MOVIES</li>
          <li>TV</li>
          <li>GAMES</li>
          <li>COLLECTIBLES</li>
          <li>VIDEOS</li>
          <li>FANS</li>
          <li>NEWS</li>
          <li>SHOP</li>
        </ul>
      </div>    
    </div>
  </div>  
</template>

<script>
export default {
  name: 'NavComp',
  props: {
    msg: String
  }
}
</script>


<style scoped lang="scss">
  .nav{
    background-color: white;
  }
  .nav-container{
    display: flex;    
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    width:80%;
    margin: 0 auto;
    line-height: 50px;
  }
  /*LIST CHANGES */
  ul{
    list-style-type: none;
    display: flex;
    // text-align: center;
    flex-direction: row;

      li{
        margin: 0 15px;
        padding: 5px;
        font-size: 15px;
      }
  } 
  .nav-img{
    display: flex;  
    padding: 0 20px;  
  } 
</style>
