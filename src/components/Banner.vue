<script>
</script>

<template>
        <section>
                <div class="banner d-flex align-items-center justify-content-center">
                        <!-- <h1 class="big text-focus-in">Arbracats</h1> -->
                        <div class="row">
                                <div class="col-12">
                                        <img alt="Arbracats logo" class="logo big" src="@/assets/logowhite.png"/>
                                </div>
                        </div>
                </div>
        </section>
</template>

<style scoped>
.banner{
        background-image: url("../assets/bg-leaf.jpg");
        height: 500px;
        background-size: cover;
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-position: 15% 15%;
        overflow: hidden;
}
.big{
        animation-name:text-focus-in;
        animation-duration: 4s;
}

 @-webkit-keyframes text-focus-in {
  0% {
    -webkit-filter: blur(12px);
            filter: blur(12px);
    opacity: 0;
  }
  100% {
    -webkit-filter: blur(0px);
            filter: blur(0px);
    opacity: 1;
  }
}
@keyframes text-focus-in {
  0% {
    -webkit-filter: blur(12px);
            filter: blur(12px);
    opacity: 0;
  }
  100% {
    -webkit-filter: blur(0px);
            filter: blur(0px);
    opacity: 1;
  }
}

</style>