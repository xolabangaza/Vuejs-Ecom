<template>
  <div id="carouselExample" class="carousel slide">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://i.postimg.cc/vH6ZGhnG/pexels-marlene-lepp-nen-1183266.jpg" class="image"  alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.postimg.cc/8Pqzk5Mx/pexels-sam-lion-5709661.jpg" class="image" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.postimg.cc/BZy2SPH5/pexels-robin-1020370.jpg" class="image" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

<section id="featured" class="image">
        <h2>Just dropped</h2>
                <div class="feat">
                    <div class="first-container">
                        <div class="product">
                            <img src="https://i.postimg.cc/5y2DJ3Yp/1672969769fce342960111936d61a3207f08b51848-thumbnail-600x.webp" class="prod-img" 
                            alt="product">
                            <h4>product 1</h4>
                        </div>
        
                         <div class="product2">
                            <img src="https://i.postimg.cc/fT2DV3MJ/1632707070c9d5a5844f37adfa971c366e035175ab-thumbnail-600x.webp
                            " class="prod-img"
                             alt="product">
                            <h4>product 2</h4>
                        </div>
        
                        <div class="product3">
                            <img src="https://i.postimg.cc/BQ6t7f6P/16326200802bf5f3d0457c0f0ce6ad4719471e7b97-thumbnail-600x.webp" class="prod-img" 
                            alt="product">
                            <h4>product 3</h4>
                        </div> 
                    </div>
                    
                        
                    <div class="second-container">
                        <div class="product4">
                            <img src="https://i.postimg.cc/8cFQW4pc/16656272281e18f677127d0a213858b1684eee6a08-thumbnail-600x.webp
                            " class="prod-img" alt="product">
                            <h4>product 4</h4>
                        </div>
        
                        <div class="product5">
                            <img src="https://i.postimg.cc/nzGY2fLw/1666749801734163531713ac5fccb2fd025c0814f2-thumbnail-600x.webp" class="prod-img" alt="product">
                            <h4>product 5</h4>
                        </div>
        
                        <div class="product6">
                            <img src="https://i.postimg.cc/FzGprX5J/1667886765770b30b4ab32fcd16670bc198b0a6f2a-thumbnail-600x.webp
                            " class="prod-img" alt="product"> -
                            <h4>product 6</h4>
                        </div>
                        
                    </div>
                   

                </div>
      </section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style scoped>
h1{
    color: blueviolet;
}
h2{
    color: blueviolet;
    text-align: center;
    margin-top: 20px;
    font-size: 60px;
    font-weight: 40px;
}

.feat{
    display: flex;
    flex-direction: column;
}

.first-container, .second-container{
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    margin-block: 10px;
    background-color: azure;
    margin-inline: 10px;
    padding: 15px;
    border-radius: 20px;
    margin-bottom: 40px;

}

.prod-img{
    width: 250px; 
}

/* .carousel-inner{
  height: 600px;
} */

.image{
  height: 100%;
  width: 100%;
  object-fit: cover; 
}

.carousel-item{
  height: 40rem;
} 
  
</style>
