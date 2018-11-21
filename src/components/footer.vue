<template>
  <div class="card">
    <div class="card-body">
      <div class="col" style="width: 18rem;">
        <!-- <ul class="col"> -->
          <h4 >Products</h4>
          <small>Team</small>
          <br/>
          <small>Talent</small>
          <br/>
          <small>Engagement</small>
        <!-- </ul> -->
      </div>

      <div class="col" style="width: 18rem;">
        <!-- <ul class="col"> -->
          <h4 >Company</h4>
          <small>About Us</small>
          <br/>
          <small>Work Here</small>
          <br/>
          <small>Privacy Policy</small>
        <!-- </ul> -->
      </div>

      <div class="col" style="width: 18rem;">
        <!-- <ul class="col"> -->
          <h4 >Help</h4>
          <small>FAQ</small>
          <br/>
          <small>Delivery</small>
          <br/>
          <small>Return And Exchange</small>
        <!-- </ul> -->
      </div>

      <div class="col" style="width: 11rem;">
        <div class="row">
          <h4 >Contact us</h4>
        </div>

        <div class="row">
          <div class="facebook">
            <img class="card-img-top" src="../assets/facebook.png" alt="Card image cap" width="10%"> 
          </div>  

          <div class="instagram">
            <img class="card-img-top" src="../assets/Instagram.png" alt="Card image cap" width="10%"> 
          </div>  

          <div class="twitter">
            <img class="card-img-top" src="../assets/twitter.png" alt="Card image cap" width="10%"> 
          </div>  
        </div>
      </div>     
    </div>
  </div>
</template>





<script>
export default {
  name: 'footer',
}
</script>




<style scoped>
.card{
  border-top:solid 2px;
  margin-top:70px;
  height: 200px;
}
.col{
  display: inline-block;
  margin-top: 20px;
  box-shadow: none; 
  vertical-align: middle;
  text-align: left;
}
/* .contact{
  margin-bottom: 40px;
} */
.instagram{
  width: 45px;
  padding-left: 5px;
  
}
.facebook{
  width: 45px;
  padding-left: 5px;
}

.twitter{
  width: 45px;
  padding-left: 5px;
}
.row{
  display: inline-flex;
  margin-bottom: 10px;
  vertical-align: middle;
  
}
</style>
