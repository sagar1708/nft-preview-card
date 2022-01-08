<template>
    
    <div class=" text-center" style="margin: auto">
      <div class="card-info d-flex flex-column border-0 rounded">
        <div class="">
          <img class="p-3" style="width: 100%" src="/assets/image-equilibrium.jpg" alt="">
        </div>
        <div>
          <h1> Equilibrium#3429 </h1>
          <p>Equilibrium collection promotes balance <br>and calm </p>
          <div class = "value">
            <img src = "/assets/icon-ethereum.svg" alt="">
            <p class = "price">     0.041ETH </p>
            <p class="time"> 30 days left </p>
          </div> 
          <div class ="line">
            <div class = "content">
              <img src = "/assets/image-avatar.png"  height="50px" width="50px" alt="">
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
<style>
.card-info {
  padding: 20px;
  background-color: hsl(216, 50%, 16%);
 
}
.text-center {
  background-color: hsl(217, 54%, 11%);
  font-family: "Outfit", sans-serif;

}
h1 {
  font-size: 25px;
  color: hsl(0, 0%, 100%);
  margin: 25px;
  text-align: left;


}
p { 
  text-align: left;
  color: hsl(216 , 27%, 60%);
  margin: 10px 25px;
  

}
.price {
   font-size: 15px;
   color :hsl(178, 100%, 50%);
   margin: 10px 10px 10px 3px;
   text-align: left;
   
}
.time {
  font-size: 15px;
  margin : 10px 10px 10px 120px;
  text-align: left;

}
.value {
  display: flex;
  margin: 20px 0 0 0;
  text-align: left;
}

 
</style>
