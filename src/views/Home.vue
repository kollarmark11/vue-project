<template>
  <div class="home">
    <div class="container">

      <!--------------------------   HÍREK   ------------------------->
      <div class="hirek row py-5">
        <div class="col-md-6 d-flex justify-content-center">
          <img src="../assets/glak_kep.jpg" alt="" width=100%>
        </div>
        <div class="col-md-6 align-self-center">
          <h1>Geresdlak 1 - 0 Kölked</h1>
          <p>2020.09.20.</p>
          <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit modi repellendus exercitationem aut hic culpa, est ea dolores architecto dignissimos enim suscipit. Nesciunt impedit odit, debitis cupiditate eaque corporis assumenda!</h4>
        </div>
      </div>

      <!--------------------------   TABELLA   ------------------------->

      <div class="row py-5">
        <div class="col-md-12">
          <img src="../assets/tabella.png" alt="" width=100%>
        </div>
      </div>

      <!--------------------------   CSAPAT   ------------------------->

      <div class="row py-3 d-flex justify-content-center">
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
      </div>

      <div class="row py-3 d-flex justify-content-center">
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
      </div>

      <div class="row py-3 d-flex justify-content-center">
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
        <div class="col-md-2 d-flex justify-content-center" ><img src="../assets/testprof.jpg" width=150px id="picture"></div>
      </div>

      <!--------------------------   TÁMOGATÓK   ------------------------->






      <!--------------------------   SOCIAL   ------------------------->

      <div class="row py-5">
        <a href="mailto:kollarmark11@gmail.com">Send email</a>
        <a href="facebook.com">Facebook</a>
      </div>
      


    </div>
    
  </div>
</template>

<script>


</script>

<style scoped lang="scss">
  
  img{
    border-radius: 20px;
  }
  h4{
    font-size: 18px;
  }
  #picture{
    transition: 0.3s;
    &:hover{
      transform: translateY(-5px);
    }
  }
</style>