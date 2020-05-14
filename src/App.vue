<template>
  <div>
    <div>
      <navbar></navbar>
    </div>
    <div class="portfolyo">
      <img class="resim d-none d-lg-block" src="./assets/images/background1.png" alt />
      <img class="resim d-lg-none d-block" src="./assets/images/back-2.png" alt />

      <div class="perde"></div>
      <img src="./assets/images/profil1.jpeg" alt class="profil" />
      <div class="aciklamalar">
        <div style="font-size:30px">Erdem ÜN</div>
        <div style="font-size:25px">Software Developer (Mechanical Engineer)</div>
        <div style="font-size:25px">Github Repo</div>
        <br />
        <div style="font-size:25px">15</div>
      </div>
    </div>
    <div class="container-fluid sosyal-link">
      <vs-button
        color="#4267b2"
        href="https://www.facebook.com/PcLokcer"
        target="_blank"
        type="filled"
        class="btnn"
      >
        <i class="fab fa-facebook"></i>
      </vs-button>
      <vs-button
        color="orange"
        href="https://www.instagram.com/pclokcer"
        target="_blank"
        type="filled"
        class="btnn"
      >
        <i class="fab fa-instagram"></i>
      </vs-button>
      <vs-button
        color="#0073b1"
        href="https://www.linkedin.com/in/erdem-%C3%BCn-5b1580153/"
        target="_blank"
        type="filled"
        class="btnn"
      >
        <i class="fab fa-linkedin"></i>
      </vs-button>
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
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="2" vs-sm="2" vs-xs="2">
          <img :style="window.width  < 900 ? 'width:80%' : 'width:60%'" src="./assets/logo.png" alt />
        </vs-col>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="2" vs-sm="2" vs-xs="2">
          <img
            :style="window.width  < 900 ? 'width:80%' : 'width:60%'"
            src="./assets/images/node.png"
            alt
          />
        </vs-col>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="2" vs-sm="2" vs-xs="2">
          <img
            :style="window.width  < 900 ? 'width:80%' : 'width:60%'"
            src="./assets/images/git.png"
            alt
          />
        </vs-col>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="2" vs-sm="2" vs-xs="2">
          <img
            :style="window.width  < 900 ? 'width:80%' : 'width:60%'"
            src="./assets/images/vscode.png"
            alt
          />
        </vs-col>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="2" vs-sm="2" vs-xs="2">
          <img
            :style="window.width  < 900 ? 'width:80%' : 'width:60%'"
            src="./assets/images/csharp.png"
            alt
          />
        </vs-col>
        <vs-col vs-type="flex" vs-justify="center" vs-align="center" vs-lg="2" vs-sm="2" vs-xs="2">
          <img
            :style="window.width  < 900 ? 'width:80%' : 'width:60%'"
            src="./assets/images/mysql.jpg"
            alt
          />
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
          <h1>ÖRNEK PROJELER</h1>
        </vs-col>
      </vs-row>
      <hr />
      <vs-row class="text-center">
        <vs-col
          vs-type="flex"
          vs-justify="center"
          vs-align="center"
          vs-lg="12"
          vs-sm="12"
          vs-xs="12"
        >
          <vs-button
            @click="resim_page = 0"
            class="yuvarlak mr-3"
            style="outline: none;"
            radius
            :color="resim_page == 0 ? 'blue' : 'white'"
            :style="resim_page == 0 ? 'color: white;' : 'color: blue;'"
            icon="phone_iphone"
          ></vs-button>
          <vs-button
            @click="resim_page = 1"
            class="yuvarlak ml-3"
            radius
            icon="laptop_mac"
            style="outline: none;"
            :color="resim_page == 1 ? 'blue' : 'white'"
            :style="resim_page == 1 ? 'color: white;' : 'color: blue;'"
          ></vs-button>
        </vs-col>
      </vs-row>
    </div>
    <br />
    <br />
    <br />
    <div v-show="resim_page == 0" class="container-fluid">
      <vs-row vs-justify="center">
        <vs-col
          type="flex"
          vs-justify="center"
          vs-align="center"
          vs-w="3"
          vs-lg="3"
          vs-sm="10"
          vs-xs="10"
        >
          <vs-card class="card-headers">
            <div slot="header">
              <span>Ekibimle Beraber Hayata Geçirdiğimiz Projenin Mobil Giriş Ekranı (Logo Temsili Değil)</span>
            </div>
            <div slot="media">
              <img src="./assets/images/mobil1.jpeg" />
            </div>
          </vs-card>
        </vs-col>
        <vs-col
          type="flex"
          vs-justify="center"
          vs-align="center"
          vs-w="3"
          vs-lg="3"
          vs-sm="10"
          vs-xs="10"
        >
          <vs-card class="card-headers" :style="window.width  < 900 ? '' : 'margin-left:30px'">
            <div slot="header">
              <span>Örnek Hesap Makinesi</span>
            </div>
            <div slot="media">
              <img src="./assets/images/mobil2.jpeg" />
            </div>
          </vs-card>
        </vs-col>
      </vs-row>
    </div>
    <div v-show="resim_page == 1" class="container-fluid">
      <vs-row vs-justify="center">
        <vs-col
          type="flex"
          vs-justify="center"
          vs-align="center"
          vs-w="5"
          vs-lg="5"
          vs-sm="10"
          vs-xs="10"
        >
          <vs-card class="card-headers">
            <div slot="header">
              <span>Ekibimle Beraber Hayata Geçirdiğimiz Projenin Günlük Hesaplamalarından Ortaya Çıkan Veri Grafikleri</span>
            </div>
            <div slot="media">
              <img src="./assets/images/web1.png" />
            </div>
          </vs-card>
        </vs-col>
        <vs-col
          type="flex"
          vs-justify="center"
          vs-align="center"
          vs-w="5"
          vs-lg="5"
          vs-sm="10"
          vs-xs="10"
        >
          <vs-card class="card-headers" :style="window.width  < 900 ? '' : 'margin-left:30px'">
            <div slot="header">
              <span>Ekibimle Beraber Hayata Geçirdiğimiz Projenin Örnek Web Kodları</span>
            </div>
            <div slot="media">
              <img src="./assets/images/web2.png" />
            </div>
          </vs-card>
        </vs-col>
      </vs-row>
    </div>
    <br />
    <br />
    <br />
    <div class="footerr">
      <footer-alt></footer-alt>
    </div>
  </div>
</template>

<script>
import navbar from "./layout/navbar";
import footer from "./layout/footer";

export default {
  components: {
    navbar,
    "footer-alt": footer
  },
  data() {
    return {
      window: {
        width: 0,
        height: 0
      },
      resim_page: 0
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
.btnn {
  margin-right: 15px;
  width: 50px !important;
  height: 50px !important;
  min-width: 50px !important;
  border-radius: 25px;
  -moz-border-radius: 25px;
  -webkit-border-radius: 25px;
  -webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
  z-index: 1600;
}
.card-headers {
  background-color: rgb(235, 223, 223) !important;
}
.footerr {
  background-color: rgb(154, 153, 153);
  /*height: 200px;
  width: 100%;*/
}
.yuvarlak {
  width: 100px !important;
  height: 100px !important;
  min-width: 100px !important;
  border-radius: 50px;
  -moz-border-radius: 50px;
  -webkit-border-radius: 50px;
  -webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
}
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
  margin-top: 120px;
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
