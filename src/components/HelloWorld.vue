<template>
  <div class="hello">
    <img src="../assets/circle.png" class="img-circle" alt="Cinque Terre" width="150px" style="margin-bottom:30px"/>
    
    <div class="container-fluid">
      <div  role="group" aria-label="Basic example">
        <button type="button" class="btn btn-secondary" >Left</button>
        <button type="button" class="btn btn-secondary">Middle</button>
        <button type="button" class="btn btn-secondary">Right</button>
        <button type="button" class="btn btn-secondary">Right</button>
      </div>
    </div>

    <div class="jumbotron jumbotron-fluid">
      <div class="container">
        <h1 class="display-4">Follow Your Dream</h1>
        <p class="lead">Only I can change my life. No one can do it for me. - Carol Burnett</p>
      </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="col">
          <div class="card">
            <img class="card-img-top" src="../assets/circle.png" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Sally Smith</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-secondary">Go somewhere</a>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <img class="card-img-top" src="../assets/circle.png" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">John Johnson</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-secondary">Go somewhere</a>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <img class="card-img-top" src="../assets/circle.png" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Jim Carlton</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-secondary">Go somewhere</a>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card" >
            <img class="card-img-top" src="../assets/circle.png" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">George Gregor</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-secondary">Go somewhere</a>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col">
          <div class="card">
            <img class="card-img-top" src="../assets/circle.png" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Alizabeth Miller</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-secondary">Go somewhere</a>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <img class="card-img-top" src="../assets/circle.png" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Jacob Will</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-secondary">Go somewhere</a>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <img class="card-img-top" src="../assets/circle.png" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Charlie Paddison</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-secondary">Go somewhere</a>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card" >
            <img class="card-img-top" src="../assets/circle.png" alt="Card image cap">
            <div class="card-body">
              <h5 class="card-title">Jack Mile</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              <a href="#" class="btn btn-secondary">Go somewhere</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: 'white';
}
button{
  margin: 13px;
  width:200px;
  height: 50px;
}
.jumbotron{
  border:solid 2px;
  width: 80%;
  display: inline-block;
  vertical-align: middle;
  margin-top:50px;
}
.container{
  margin: 0 auto; 
  float: none; 
  /* background-color: black; */
}
.card{
  width: 250px;
  margin-top: 20px;
}
</style>
