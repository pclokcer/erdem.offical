<template>
  <div>
    <div>
      <navbar></navbar>
    </div>
    <div class="portfolyo">
      <img class="resim d-none d-lg-block" src="./assets/images/background.png" alt />
      <img class="resim d-lg-none d-block" src="./assets/images/profil1.jpeg" alt />

      <div class="perde"></div>
      <img src="./assets/images/profil1.jpeg" alt class="profil" />
      <div class="aciklamalar">
        <div>asdasd</div>
        <div>asdasd1</div>
      </div>
    </div>
    <div class="alt-portfolyo">
      <div class="alt-perde">
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
        >face</vs-button>
      </div>
      <div class="container-fluid alta-cek">
        <vs-row>
          <vs-col
            vs-type="flex"
            vs-justify="center"
            vs-align="center"
            vs-lg="12"
            vs-sm="12"
            vs-xs="12"
          >
            <h1>HAKKINDA</h1>
          </vs-col>
        </vs-row>
        <hr />
        <vs-row>
          <vs-col
            vs-type="flex"
            vs-justify="center"
            vs-align="center"
            vs-lg="12"
            vs-sm="12"
            vs-xs="12"
          >
            <h4>
              Makine Mühendisliği Bölümü Mezunuyum. Bilgisayarla Küçüklüğümden
              Beri Çok İlgili Olduğum için Yazılım Sektörü Hep İlgimi Çekmiştir.
              Üniversite Sırasında Yazılım Konusunda İlerleyip Ürünler Oluşturdum.
              Şimdi ise Mobil Uygulamalar, Web Uygulamalar ve Backend Uygulamaları
              Geliştirmekteyim.
            </h4>
          </vs-col>
        </vs-row>
      </div>
    </div>

    <br />
    <div class="container-fluid">
      <vs-row>
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

      <vs-row>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="4" vs-sm="4" vs-xs="4">
          <img class="resim-wit" src="./assets/logo.png" alt />
        </vs-col>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="4" vs-sm="4" vs-xs="4">
          <img class="resim-wit" src="./assets/logo.png" alt />
        </vs-col>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="4" vs-sm="4" vs-xs="4">
          <img class="resim-wit" src="./assets/logo.png" alt />
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
  }
};
</script>

<style scoped>
.techno {
  display: flex;
  align-items: center;
  justify-content: center;
}

.alta-cek {
  margin-top: 100px;
}

.resim-wit {
  width: 40%;
}

.iki-satir {
  position: relative;
  width: 100%;
  height: 300px;
  top: 0;
  left: 0;
  text-align: center;
  align-items: center;
  justify-content: center;
  z-index: 1003;
}

.portfolyo {
  position: relative;
  width: 100%;
  height: 750px;
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: center;
}

.resim {
  position: absolute;
  width: 100%;
  left: 0;
  top: 0;
  height: 750px;
  min-height: 750px;
}

.perde {
  position: absolute;
  width: 100%;
  height: 750px;
  top: 0;
  left: 0;
  min-height: 750px;
  background-image: linear-gradient(
    to bottom,
    rgba(0, 21, 255, 0.394),
    rgba(0, 21, 255, 0.068)
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

.alt-portfolyo {
  position: relative;
  width: 100%;
  height: auto;
  top: -250px;
  padding-bottom: 90px;
  left: 0;
  display: flex;
  text-align: center;
  align-items: center;
  justify-content: center;
  background-color: white;
  z-index: 1003;
}

.alt-perde {
  position: absolute;

  top: -22px;
}
/*
-webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
 */
</style>
