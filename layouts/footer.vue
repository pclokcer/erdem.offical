<template>
  <div>
    <div class="container-fluid">
      <div class="row pt-3 pb-3 text-right footer-font">
        
        <div class="col-12">
          <div>
            <a style="color:white;">Telefon: +90 543 231 90 57</a>
          </div>
          <div>
            <a style="color:white;">Email: erdemun.offical@gmail.com</a>
          </div>
        </div>
      </div>
      <div
        class="row pb-3 pt-2 text-center justify-content-lg-between justify-content-center"
        style="background-color:#2c2c2c;"
      >
        <div class="col-md-4"></div>
        <div
          class="col-md-12"
          style="color:rgb(154, 153, 153); padding-top: 4px;"
        >Copyrigth © {{year}} by Erdem ÜN -- (PcLokcer)</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>

<style>
.sırala {
  text-align: left;
}
</style>