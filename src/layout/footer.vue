<template>
  <div class="container-fluid">
    <div class="row pt-3 pb-3 row-cols-2 row-cols-sm-2 row-cols-md-4 text-center footer-font">
      <div class="col sırala">
        <div>
          <a href></a>
        </div>
        <div>
          <a href></a>
        </div>
      </div>
      <div class="col pb-3 sırala">
        <div>
          <a href></a>
        </div>
        <div>
          <a href></a>
        </div>
      </div>
      <div class="col sırala"></div>
      <div class="col-6 sırala">
        <div>
          <a style="color:#2c2c2c;">Telefon: +90 543 231 90 57</a>
        </div>
        <div>
          <a style="color:#2c2c2c;">Email: erdemun_offical@gmail.com</a>
        </div>
      </div>
    </div>
    <div
      class="row pb-3 pt-2 text-center justify-content-lg-between justify-content-center"
      style="background-color:#2c2c2c;"
    >
      <div class="col-lg-4"></div>
      <div
        class="col-lg-12"
        style="color:rgb(154, 153, 153); padding-top: 4px;"
      >Copyrigth © {{year}} by Erdem ÜN -- (PcLokcer)</div>
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