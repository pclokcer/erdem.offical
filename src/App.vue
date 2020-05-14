<template>
  <div>
    <div>
      <navbar></navbar>
    </div>
    <div class="portfolyo">
      <img class="resim d-none d-lg-block" src="./assets/images/background1.png" alt />
      <img class="resim d-lg-none d-block" src="./assets/images/profil1.jpeg" alt />

      <div class="perde"></div>
      <img src="./assets/images/profil1.jpeg" alt class="profil" />
      <div class="aciklamalar">
        <div>asdasd</div>
        <div>asdasd1</div>
      </div>
    </div>
    <div class="container-fluid sosyal-link">
      <vs-button
        color="success"
        href="https://www.facebook.com/PcLokcer"
        target="_blank"
        type="filled"
        class="mr-3"
      >face</vs-button>
      <vs-button
        color="success"
        href="https://www.facebook.com/PcLokcer"
        target="_blank"
        type="filled"
        class="mr-3"
      >face</vs-button>
      <vs-button
        color="success"
        href="https://www.facebook.com/PcLokcer"
        target="_blank"
        type="filled"
        class="mr-3"
      >face</vs-button>
      <vs-button
        color="success"
        href="https://www.facebook.com/PcLokcer"
        target="_blank"
        type="filled"
        class="mr-3"
      >face</vs-button>
    </div>
    <br />
    <br />
    <br />
    <br />
    <div class="container-fluid">
      <vs-row class="text-center">
        <vs-col
          vs-type="flex"
          vs-justify="center"
          vs-align="center"
          vs-lg="12"
          vs-sm="12"
          vs-xs="12"
        >
          <h1>HAKKIMDA</h1>
        </vs-col>
      </vs-row>
      <hr />
      <vs-row class="text-center">
        <vs-col
          vs-offset="2"
          vs-tooltip="'col - 8'"
          vs-type="flex"
          vs-justify="center"
          vs-align="center"
          vs-w="8"
        >
          <p>
            Makine Mühendisliği Bölümü Mezunuyum. Bilgisayarla Küçüklüğümden
            Beri Çok İlgili Olduğum için Yazılım Sektörü Hep İlgimi Çekmiştir.
            Üniversite Sırasında Yazılım Konusunda İlerleyip Ürünler Oluşturdum.
            Şimdi ise Mobil Uygulamalar, Web Uygulamalar ve Backend Uygulamaları
            Geliştirmekteyim.
          </p>
        </vs-col>
      </vs-row>
    </div>
    <br />
    <br />
    <br />
    <br />
    <div class="container-fluid">
      <vs-row class="text-center">
        <vs-col
          vs-type="flex"
          vs-justify="center"
          vs-align="center"
          vs-lg="12"
          vs-sm="12"
          vs-xs="12"
        >
          <h1>KULLANDIĞIM TEKNOLOJİLER</h1>
        </vs-col>
      </vs-row>
      <hr />
      <vs-row>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="4" vs-sm="4" vs-xs="4">
          <img :style="window.width  < 768 ? 'width:70%' : 'width:35%'" src="./assets/logo.png" alt />
        </vs-col>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="4" vs-sm="4" vs-xs="4">
          <img :style="window.width  < 768 ? 'width:70%' : 'width:35%'" src="./assets/logo.png" alt />
        </vs-col>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="4" vs-sm="4" vs-xs="4">
          <img :style="window.width  < 768 ? 'width:70%' : 'width:35%'" src="./assets/logo.png" alt />
        </vs-col>
      </vs-row>
    </div>
    <div class="container-fluid">
      <vs-row class="text-center">
        <vs-col
          vs-type="flex"
          vs-justify="center"
          vs-align="center"
          vs-lg="12"
          vs-sm="12"
          vs-xs="12"
        >
          <h1>KULLANDIĞIM TEKNOLOJİLER</h1>
        </vs-col>
      </vs-row>
    </div>
  </div>
</template>

<script>
import navbar from "./layout/navbar";

export default {
  components: {
    navbar
  },
  data() {
    return {
      window: {
        width: 0,
        height: 0
      }
    };
  },
  created() {
    window.addEventListener("resize", this.handleResize);
    this.handleResize();
  },
  destroyed() {
    window.removeEventListener("resize", this.handleResize);
  },
  methods: {
    handleResize() {
      this.window.width = window.innerWidth;
      this.window.height = window.innerHeight;
    }
  }
};
</script>

<style scoped>
.portfolyo {
  position: relative;
  width: 100%;
  height: 500px;
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: center;
}

.resim {
  position: absolute;
  width: 100%;
  height: 500px;
  left: 0;
  top: 0;
  min-height: 500px;
}

.perde {
  position: absolute;
  width: 100%;
  height: 500px;
  top: 0;
  left: 0;
  min-height: 500px;
  background-image: linear-gradient(
    to bottom,
    rgba(0, 21, 255, 0.394),
    rgba(0, 21, 255, 0.075)
  );
  z-index: 1000;
}

.profil {
  position: absolute;
  width: 150px;
  border-radius: 500px;
  top: 50px;
  display: flex;
  text-align: center;
  justify-content: center;
  z-index: 1001;
}

.aciklamalar {
  color: white;
  display: grid;
  text-align: center;
  justify-content: center;
  z-index: 1002;
}

.sosyal-link {
  margin-top: -25px;
  display: flex;
  align-items: center;
  justify-content: center;
}
/*
-webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
 */
</style>
