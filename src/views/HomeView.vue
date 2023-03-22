<script setup>
import Banner from "../components/Banner.vue";
/* import font awesome icon component */
</script>

<template>
  <div class="Home">
    <Banner />
    <div class="separation-bottom-dark">

      <div class="slider">
        <div class="slide-track">
          <div class="slide mx-3 my-3">
            <img src="../assets/brico.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/hubo.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/zooplus.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/tomandco.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/aliexpress.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/chienvert.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/blackdecker.jpg" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/brico.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/hubo.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/zooplus.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/tomandco.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/aliexpress.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/chienvert.png" height="100" width="250" alt="" />
          </div>
          <div class="slide mx-3 my-3">
            <img src="../assets/blackdecker.jpg" height="100" width="250" alt="" />
        </div>
      </div>
    </div>
    <!-- <div class=" mobile d-flex align-items-center py-2">
          
            <img class="mx-4" src="../assets/brico.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/hubo.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/zooplus.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/tomandco.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/aliexpress.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/chienvert.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/blackdecker.jpg" width="75" alt="">

            <img class="mx-4" src="../assets/brico.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/hubo.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/zooplus.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/tomandco.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/aliexpress.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/chienvert.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/blackdecker.jpg" width="75" alt="">

            <img class="mx-4" src="../assets/brico.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/hubo.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/zooplus.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/tomandco.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/aliexpress.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/chienvert.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/blackdecker.jpg" width="75" alt="">

            <img class="mx-4" src="../assets/brico.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/hubo.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/zooplus.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/tomandco.png" width="75" alt="">
          
            <img class="mx-4" src="../assets/aliexpress.png" width="75" alt="">
          
              <img class="mx-4" src="../assets/chienvert.png" width="75" alt="">
          
              <img class="mx-4" src="../assets/blackdecker.jpg" width="75" alt="">
          </div> -->
    </div>
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-5 my-5">
            <video width="420" height="500" autoplay muted loop>
              <source src="../assets/cat-tube.mp4" type="video/mp4">
            </video>
        </div>
        <div class="col-6 my-5">
          <h2 class="text-start">Your compagnon, our priority !</h2>
          <p class="text-start fs-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Id at rerum ut! Corrupti hic
            itaque cum, harum aliquam magni, facere temporibus non labore voluptas quibusdam veritatis fugit et officia
            praesentium quis nihil. Eveniet eos aliquam, aut libero pariatur omnis quod? Assumenda labore explicabo
            officiis necessitatibus molestias animi id dolorum! Et quam, ab eius rem earum tempora consequuntur quaerat
            </p>
        </div>
      </div>
    </div>

  </div>
</template>

<style scoped>
*{
  color: white;
}
.separation-top-dark {
  height: 50px;
  background-color: #313131;
}

.separation-bottom-dark {
  height: 130px;
  background-color: #000000;
  position: relative;
  overflow: hidden;
  filter: grayscale(1);
}
@keyframes animationSpeed {
  0% {
    transform: translateX(0);
  }

  100% {
    transform: translateX(calc(-250px * 7))
  }
}

.slider {
  background: rgb(0, 0, 0);
  box-shadow: 0 10px 20px -5px rgba(0, 0, 0, .125);
  margin: auto;
  overflow: hidden;
  position: relative;
}

.slider::before,
.slider::after {
  content: "";
  position: absolute;
  width: 200px;
  z-index: 2;
}

.slider::after {
  right: 0;
  top: 0;
  transform: rotateZ(180deg);
}

.slider::before {
  left: 0;
  top: 0;
}

.slide-track {
  animation: animationSpeed linear infinite;
  animation-duration: 30s;
  display: flex;
  width: calc(250px * 14);
}

.slide {
  height: 100px;
  width: 250px;
}</style>
