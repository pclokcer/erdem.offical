<template>
  <div>
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-2 text-left"></div>
        <div class="col-md-8 text-center">
          <p style="margin-top: 30px; margin-bottom: 30px">
            Projede Kullandığım Bazı Nodejs Modülleri;
          </p>
        </div>
        <div class="col-md-2 text-left"></div>
      </div>
      <div class="row mb-5">
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - express
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - nodemon
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - jsonwebtoken
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - socket.io
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - nodemailer
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - joi
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - mysql
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - mkdirp
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - moment
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - crypto-js
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - node-cron
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - dotenv
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - bcrypt
        </div>
        <div style="margin-bottom: 12px" class="col-md-6 text-center">
          - node-cache
        </div>
      </div>
    </div>
    <hr />
    <section id="tecrube">
      <div class="container-fluid mb-5">
        <div class="row mb-4">
          <div class="col-md-12 text-center">
            <h1 class="mt-3">E-Garsonum Sisteminin Kurgusu</h1>
          </div>
        </div>
        <div class="row">
          <div class="col-md-2 text-left"></div>
          <div class="col-md-8 text-left ml-3">
            <p>
              Diagramda Görülen Mobil, Web ve Sunucu yazılımlarının hepsine
              hakim bir şekilde kodlama yapabilirim. Akışı Anlatmak gerekirse,
              mobilden ve web den gelen http istekleri sunucu tarafında bulunan
              nginx karşılar. Burda isteğin konfigure ettiğimiz şekilde
              yönlendirilmesi yapılır. Yönlendirme web sayfası alabilir, API
              isteği alabilir veya Web Socket isteği alabilir şekilde konfigure
              edilmiştir.
            </p>
            <br />
            <p>- Web Sayfasına göre yönlendirme alırsa web sayfası verilir.</p>
            <br />
            <p>
              - API isteğine göre yönlendirme alırsa web servisimiz de ilk
              olarak token kontrolü yapılır. Token kontrolünden geçen istek
              mysql veya bellekten data alabilir ve data kaydı kapabilir.
            </p>
            <br />
            <p>
              - Web Socket isteğine göre yönlendirme alırsa soket bağlantısı
              gerçekleştirilir ve sokette oda kurulur. Anlık haberleşme için
              gelen Mobil Platform bağlantı istekleri bu odaya dahil edilerek
              kullanıcılar arasında bağlantı gerçekleşmiş olur. Artık Anlık
              olarak kullanıcılar birbirleri ile haberleşmeye hazırdır.
            </p>
          </div>
          <div class="col-md-2 text-left"></div>
        </div>
        <br />
        <br />
        <br />
        <div class="row">
          <div class="col-md-12 text-center">
            <img width="60%" src="../assets/images/diagram.png" alt />
          </div>
        </div>
      </div>
      <hr />
    </section>
    <section>
      <b-container fluid class="mt-5">
        <div class="row">
          <div class="col-md-12 text-center">
            <h2>Projeden Resimler</h2>
          </div>
        </div>
        <b-container>
          <b-row class="text-center orta mt-3">
            <b-col md="12">
              <b-button
                @click="resim_page = 0"
                class="yuvarlak mr-3"
                style="outline: none"
                radius
                :style="
                  resim_page == 0
                    ? 'color: white;background-color: blue;'
                    : 'color: blue;background-color: white;'
                "
              >
                <svg
                  class="bi bi-phone"
                  width="1.5em"
                  height="1.5em"
                  viewBox="0 0 16 16"
                  fill="currentColor"
                >
                  <path
                    fill-rule="evenodd"
                    d="M11 1H5a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V2a1 1 0 0 0-1-1zM5 0a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2H5z"
                  />
                  <path
                    fill-rule="evenodd"
                    d="M8 14a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"
                  />
                </svg>
              </b-button>

              <b-button
                @click="resim_page = 1"
                class="yuvarlak ml-3"
                radius
                icon="display"
                style="outline: none"
                :style="
                  resim_page == 1
                    ? 'color: white;background-color: blue;'
                    : 'color: blue;background-color: white;'
                "
              >
                <svg
                  class="bi bi-display"
                  width="1.5em"
                  height="1.5em"
                  viewBox="0 0 16 16"
                  fill="currentColor"
                >
                  <path
                    d="M5.75 13.5c.167-.333.25-.833.25-1.5h4c0 .667.083 1.167.25 1.5H11a.5.5 0 0 1 0 1H5a.5.5 0 0 1 0-1h.75z"
                  />
                  <path
                    fill-rule="evenodd"
                    d="M13.991 3H2c-.325 0-.502.078-.602.145a.758.758 0 0 0-.254.302A1.46 1.46 0 0 0 1 4.01V10c0 .325.078.502.145.602.07.105.17.188.302.254a1.464 1.464 0 0 0 .538.143L2.01 11H14c.325 0 .502-.078.602-.145a.758.758 0 0 0 .254-.302 1.464 1.464 0 0 0 .143-.538L15 9.99V4c0-.325-.078-.502-.145-.602a.757.757 0 0 0-.302-.254A1.46 1.46 0 0 0 13.99 3zM14 2H2C0 2 0 4 0 4v6c0 2 2 2 2 2h12c2 0 2-2 2-2V4c0-2-2-2-2-2z"
                  />
                </svg>
              </b-button>
              <!-- laptop -->
            </b-col>
          </b-row>
        </b-container>
        <div v-show="resim_page == 0" class="row mt-5 mb-5">
          <b-container>
            <b-row>
              <b-col>
                <b-card
                  title="Mobil"
                  img-src="../assets/images/mobil1.jpeg"
                  img-alt="Image"
                  img-bottom
                  tag="article"
                  class="mb-2 pic"
                >
                  <b-card-text
                    >Mobil Giriş Ekranı (Logo Temsili Değil)</b-card-text
                  >
                </b-card>
              </b-col>
              <b-col>
                <b-card
                  title="Mobil"
                  img-src="../assets/images/mobil2.jpeg"
                  img-alt="Image"
                  img-bottom
                  tag="article"
                  class="mb-2 pic"
                >
                  <b-card-text>Projenin Örnek Mobil Ekranı</b-card-text>
                </b-card>
              </b-col>
            </b-row>
          </b-container>
        </div>
        <div v-show="resim_page == 1" class="row mt-5 mb-5">
          <b-container>
            <b-row>
              <b-col class="orta">
                <b-card
                  title="Web"
                  img-src="../assets/images/web1.png"
                  img-alt="Image"
                  img-bottom
                  tag="article"
                  style="max-width: 50rem"
                  class="mb-2 pic"
                >
                  <b-card-text
                    >Projenin Günlük Hesaplamalarından Ortaya Çıkan Veri
                    Grafikleri</b-card-text
                  >
                </b-card>
              </b-col>
              <b-col class="orta">
                <b-card
                  title="Web"
                  img-src="../assets/images/web2.png"
                  img-alt="Image"
                  img-bottom
                  tag="article"
                  style="max-width: 50rem"
                  class="mb-2 pic"
                >
                  <b-card-text>Projenin Örnek Web Ekranı</b-card-text>
                </b-card>
              </b-col>
            </b-row>
          </b-container>
        </div>
      </b-container>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      resim_page: 0,
    };
  },
};
</script>

<style>
.logo {
  padding: 20px;
  margin-left: 50px;
  border-radius: 20px;
  margin-right: 50px;
  -webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.2);
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.2);
}
.logo:hover {
  -webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.5);
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.5);
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
.sunum {
  width: 400px;
  margin: 15px;
}
</style>