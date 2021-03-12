<template>
  <div>
    <b-navbar id="nav-bar" toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href></b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-form class="mr-sm-4">
            <a class="nav-link" href="#header">Ana Sayfa</a>
          </b-nav-form>
          <b-nav-form class="mr-sm-4">
            <a class="nav-link" href="#info">Hakkımda</a>
          </b-nav-form>
          <b-nav-form class="mr-sm-4">
            <a class="nav-link" href="#teknolojiler">Teknolojiler</a>
          </b-nav-form>
          <b-nav-form class="mr-sm-4">
            <a class="nav-link" href="#projeler">Örnek Projeler</a>
          </b-nav-form>
          <b-nav-form class="mr-sm-4">
            <a class="nav-link" href="#footer">İletişim</a>
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <section id="header">
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-12 text-center resim">
            <img src="../assets/images/profil3.jpeg" alt />
            <h1>Erdem Ün</h1>
            <h2>Software Developer (Mechanical Engineer)</h2>
            <h2>Github Repo</h2>
            <h3>15</h3>
          </div>
        </div>
      </div>
    </section>
    <section id="info">
      <div class="container-fluid">
        <div class="row justify-content-between d-flex">
          <div class="col-12" style="margin-top: -35px">
            <div class="d-flex justify-content-center">
              <a
                target="_blank"
                style="color: blue"
                href="https://www.facebook.com/PcLokcer"
              >
                <svg
                  class="mb-1"
                  aria-hidden="true"
                  focusable="false"
                  width="1.7em"
                  height="1.7em"
                  style="
                    -ms-transform: rotate(360deg);
                    -webkit-transform: rotate(360deg);
                    transform: rotate(360deg);
                  "
                  preserveAspectRatio="xMidYMid meet"
                  viewBox="0 0 256 256"
                >
                  <path
                    d="M241.871 256.001c7.802 0 14.129-6.326 14.129-14.129V14.129C256 6.325 249.673 0 241.871 0H14.129C6.324 0 0 6.325 0 14.129v227.743c0 7.803 6.324 14.129 14.129 14.129h227.742"
                    fill="#395185"
                  />
                  <path
                    d="M176.635 256.001v-99.137h33.277l4.982-38.635h-38.259V93.561c0-11.186 3.107-18.809 19.148-18.809l20.459-.009V40.188c-3.54-.471-15.684-1.523-29.812-1.523c-29.498 0-49.692 18.005-49.692 51.071v28.493h-33.362v38.635h33.362v99.137h39.897"
                    fill="#FFF"
                  />
                </svg>
              </a>

              <a
                target="_blank"
                style="color: black"
                href="https://github.com/pclokcer"
              >
                <svg
                  class="mb-1"
                  aria-hidden="true"
                  focusable="false"
                  width="1.7em"
                  height="1.7em"
                  style="
                    -ms-transform: rotate(360deg);
                    -webkit-transform: rotate(360deg);
                    transform: rotate(360deg);
                  "
                  preserveAspectRatio="xMidYMid meet"
                  viewBox="0 0 256 250"
                >
                  <path
                    d="M128.001 0C57.317 0 0 57.307 0 128.001c0 56.554 36.676 104.535 87.535 121.46c6.397 1.185 8.746-2.777 8.746-6.158c0-3.052-.12-13.135-.174-23.83c-35.61 7.742-43.124-15.103-43.124-15.103c-5.823-14.795-14.213-18.73-14.213-18.73c-11.613-7.944.876-7.78.876-7.78c12.853.902 19.621 13.19 19.621 13.19c11.417 19.568 29.945 13.911 37.249 10.64c1.149-8.272 4.466-13.92 8.127-17.116c-28.431-3.236-58.318-14.212-58.318-63.258c0-13.975 5-25.394 13.188-34.358c-1.329-3.224-5.71-16.242 1.24-33.874c0 0 10.749-3.44 35.21 13.121c10.21-2.836 21.16-4.258 32.038-4.307c10.878.049 21.837 1.47 32.066 4.307c24.431-16.56 35.165-13.12 35.165-13.12c6.967 17.63 2.584 30.65 1.255 33.873c8.207 8.964 13.173 20.383 13.173 34.358c0 49.163-29.944 59.988-58.447 63.157c4.591 3.972 8.682 11.762 8.682 23.704c0 17.126-.148 30.91-.148 35.126c0 3.407 2.304 7.398 8.792 6.14C219.37 232.5 256 184.537 256 128.002C256 57.307 198.691 0 128.001 0zm-80.06 182.34c-.282.636-1.283.827-2.194.39c-.929-.417-1.45-1.284-1.15-1.922c.276-.655 1.279-.838 2.205-.399c.93.418 1.46 1.293 1.139 1.931zm6.296 5.618c-.61.566-1.804.303-2.614-.591c-.837-.892-.994-2.086-.375-2.66c.63-.566 1.787-.301 2.626.591c.838.903 1 2.088.363 2.66zm4.32 7.188c-.785.545-2.067.034-2.86-1.104c-.784-1.138-.784-2.503.017-3.05c.795-.547 2.058-.055 2.861 1.075c.782 1.157.782 2.522-.019 3.08zm7.304 8.325c-.701.774-2.196.566-3.29-.49c-1.119-1.032-1.43-2.496-.726-3.27c.71-.776 2.213-.558 3.315.49c1.11 1.03 1.45 2.505.701 3.27zm9.442 2.81c-.31 1.003-1.75 1.459-3.199 1.033c-1.448-.439-2.395-1.613-2.103-2.626c.301-1.01 1.747-1.484 3.207-1.028c1.446.436 2.396 1.602 2.095 2.622zm10.744 1.193c.036 1.055-1.193 1.93-2.715 1.95c-1.53.034-2.769-.82-2.786-1.86c0-1.065 1.202-1.932 2.733-1.958c1.522-.03 2.768.818 2.768 1.868zm10.555-.405c.182 1.03-.875 2.088-2.387 2.37c-1.485.271-2.861-.365-3.05-1.386c-.184-1.056.893-2.114 2.376-2.387c1.514-.263 2.868.356 3.061 1.403z"
                    fill="#161614"
                  />
                </svg>
              </a>

              <a
                target="_blank"
                style="color: orange"
                href="https://www.instagram.com/pclokcer"
              >
                <svg
                  class="mb-1"
                  aria-hidden="true"
                  focusable="false"
                  width="1.7em"
                  height="1.7em"
                  style="
                    -ms-transform: rotate(360deg);
                    -webkit-transform: rotate(360deg);
                    transform: rotate(360deg);
                  "
                  preserveAspectRatio="xMidYMid meet"
                  viewBox="0 0 256 256"
                >
                  <path
                    d="M128 23.064c34.177 0 38.225.13 51.722.745c12.48.57 19.258 2.655 23.769 4.408c5.974 2.322 10.238 5.096 14.717 9.575c4.48 4.479 7.253 8.743 9.575 14.717c1.753 4.511 3.838 11.289 4.408 23.768c.615 13.498.745 17.546.745 51.723c0 34.178-.13 38.226-.745 51.723c-.57 12.48-2.655 19.257-4.408 23.768c-2.322 5.974-5.096 10.239-9.575 14.718c-4.479 4.479-8.743 7.253-14.717 9.574c-4.511 1.753-11.289 3.839-23.769 4.408c-13.495.616-17.543.746-51.722.746c-34.18 0-38.228-.13-51.723-.746c-12.48-.57-19.257-2.655-23.768-4.408c-5.974-2.321-10.239-5.095-14.718-9.574c-4.479-4.48-7.253-8.744-9.574-14.718c-1.753-4.51-3.839-11.288-4.408-23.768c-.616-13.497-.746-17.545-.746-51.723c0-34.177.13-38.225.746-51.722c.57-12.48 2.655-19.258 4.408-23.769c2.321-5.974 5.095-10.238 9.574-14.717c4.48-4.48 8.744-7.253 14.718-9.575c4.51-1.753 11.288-3.838 23.768-4.408c13.497-.615 17.545-.745 51.723-.745M128 0C93.237 0 88.878.147 75.226.77c-13.625.622-22.93 2.786-31.071 5.95c-8.418 3.271-15.556 7.648-22.672 14.764C14.367 28.6 9.991 35.738 6.72 44.155C3.555 52.297 1.392 61.602.77 75.226C.147 88.878 0 93.237 0 128c0 34.763.147 39.122.77 52.774c.622 13.625 2.785 22.93 5.95 31.071c3.27 8.417 7.647 15.556 14.763 22.672c7.116 7.116 14.254 11.492 22.672 14.763c8.142 3.165 17.446 5.328 31.07 5.95c13.653.623 18.012.77 52.775.77s39.122-.147 52.774-.77c13.624-.622 22.929-2.785 31.07-5.95c8.418-3.27 15.556-7.647 22.672-14.763c7.116-7.116 11.493-14.254 14.764-22.672c3.164-8.142 5.328-17.446 5.95-31.07c.623-13.653.77-18.012.77-52.775s-.147-39.122-.77-52.774c-.622-13.624-2.786-22.929-5.95-31.07c-3.271-8.418-7.648-15.556-14.764-22.672C227.4 14.368 220.262 9.99 211.845 6.72c-8.142-3.164-17.447-5.328-31.071-5.95C167.122.147 162.763 0 128 0zm0 62.27C91.698 62.27 62.27 91.7 62.27 128c0 36.302 29.428 65.73 65.73 65.73c36.301 0 65.73-29.428 65.73-65.73c0-36.301-29.429-65.73-65.73-65.73zm0 108.397c-23.564 0-42.667-19.103-42.667-42.667S104.436 85.333 128 85.333s42.667 19.103 42.667 42.667s-19.103 42.667-42.667 42.667zm83.686-110.994c0 8.484-6.876 15.36-15.36 15.36c-8.483 0-15.36-6.876-15.36-15.36c0-8.483 6.877-15.36 15.36-15.36c8.484 0 15.36 6.877 15.36 15.36z"
                    fill="#0A0A08"
                  />
                </svg>
              </a>

              <a
                target="_blank"
                style="color: royalblue"
                href="https://www.linkedin.com/in/erdem-%C3%BCn-5b1580153/"
              >
                <svg
                  class="mb-1"
                  aria-hidden="true"
                  focusable="false"
                  width="1.7em"
                  height="1.7em"
                  style="
                    -ms-transform: rotate(360deg);
                    -webkit-transform: rotate(360deg);
                    transform: rotate(360deg);
                  "
                  preserveAspectRatio="xMidYMid meet"
                  viewBox="0 0 72 72"
                >
                  <rect
                    x="11"
                    y="11"
                    rx="3"
                    width="50"
                    height="50"
                    fill="#61b2e4"
                  />
                  <path fill="#fff" d="M20 30h6v21h-6z" />
                  <circle cx="23" cy="22" r="3.5" fill="#fff" />
                  <path
                    fill="#fff"
                    d="M42.5 35c-2.209 0-4 1.168-4 4.5V51h-6V30h6v2.21h-.002A7.981 7.981 0 0 1 44.5 29.5c4.418 0 8 3.3 8 9V51h-6V39.5c0-3.332-1.79-4.5-4-4.5"
                  />
                  <g fill="none" stroke="#000" stroke-width="2">
                    <rect
                      x="11"
                      y="11"
                      rx="3"
                      width="50"
                      height="50"
                      stroke-miterlimit="10"
                    />
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M20 30h6v21h-6z"
                    />
                    <circle
                      cx="23"
                      cy="22"
                      r="3.5"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      d="M42.5 35c-2.209 0-4 1.168-4 4.5V51h-6V30h6v2.21h-.002A7.981 7.981 0 0 1 44.5 29.5c4.418 0 8 3.3 8 9V51h-6V39.5c0-3.332-1.79-4.5-4-4.5"
                    />
                  </g>
                </svg>
              </a>
            </div>
          </div>
        </div>
      </div>

      <hr />
      <div class="container-fluid">
        <div class="row">
          <div class="col-md-12 text-center">
            <h2 class="mt-3">HAKKIMDA</h2>
          </div>
          <div class="col-md-2 text-left"></div>
          <div class="col-md-8 text-left ml-3">
            <p style="margin-top: 30px; margin-bottom: 30px">
              Makine Mühendisliği Bölümü Mezunuyum. Bilgisayarla Küçüklüğümden
              Beri Çok İlgili Olduğum için Yazılım Sektörü Hep İlgimi Çekmiştir.
              Üniversite Sırasında Yazılım Konusunda İlerleyip Ürünler
              Oluşturdum. Şimdi ise Mobil Uygulamalar, Web Uygulamalar ve
              Backend Uygulamaları Geliştirmekteyim.
            </p>
          </div>
          <div class="col-md-2 text-left"></div>
        </div>
      </div>
    </section>
    <section id="teknolojiler">
      <div class="container-fluid mb-5">
        <div class="row mb-2">
          <div class="col-md-12 text-center">
            <h2 class="mt-3">KULLANDIĞIM TEKNOLOJİLER</h2>
          </div>
        </div>
        <div class="row teknoloji">
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img height="50px" src="../assets/logo.png" alt />
              <h3>Vuejs</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img height="50px" src="../assets/images/flutter.png" alt />
              <h3>Flutter</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img height="50px" src="../assets/images/node.png" alt />
              <h3>Nodejs</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img
                src="https://miro.medium.com/max/336/1*glD7bNJG3SlO0_xNmSGPcQ.png"
                alt=""
                height="50px"
              />
              <h3>Docker</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img
                src="https://sm.pcmag.com/pcmag_au/review/a/amazon-web/amazon-web-services_282w.jpg"
                alt=""
                height="50px"
              />
              <h3>Amazon (AWS)</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img src="../assets/images/mongo.png" alt="" height="50px" />
              <h3>MongoDB</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img height="50px" src="../assets/images/native.png" alt />
              <h3>NativeScript</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo" style="height: 170px">
              <svg height="50" viewBox="0 0 452 342">
                <g fill="none" fill-rule="evenodd">
                  <path
                    d="M139 330l-1-2c-2-4-2-8-1-13H29L189 31l67 121 22-16-67-121c-1-2-9-14-22-14-6 0-15 2-22 15L5 303c-1 3-8 16-2 27 4 6 10 12 24 12h136c-14 0-21-6-24-12z"
                    fill="#00C58E"
                  />
                  <path
                    d="M447 304L317 70c-2-2-9-15-22-15-6 0-15 3-22 15l-17 28v54l39-67 129 230h-49a23 23 0 0 1-2 14l-1 1c-6 11-21 12-23 12h76c3 0 17-1 24-12 3-5 5-14-2-26z"
                    fill="#108775"
                  />
                  <path
                    d="M376 330v-1l1-2c1-4 2-8 1-12l-4-12-102-178-15-27h-1l-15 27-102 178-4 12a24 24 0 0 0 2 15c4 6 10 12 24 12h190c3 0 18-1 25-12zM256 152l93 163H163l93-163z"
                    fill="#2F495E"
                    fill-rule="nonzero"
                  />
                </g>
              </svg>
              <h3 class="mt-4">Nuxtjs</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo" style="height: 170px">
              <img width="50px" src="../assets/images/vscode.png" alt />
              <h4 style="margin-top: -15px">Visual Studio Code</h4>
            </div>
          </div>

          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img height="50px" src="../assets/images/mysql.jpg" alt />
              <h3>MySQL</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img height="50px" src="../assets/images/git.png" alt />
              <h3>GitBash</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img height="50px" src="../assets/images/csharp.png" alt />
              <h3>C#</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img height="50px" src="../assets/images/github.png" alt />
              <h3>Github</h3>
            </div>
          </div>
          <div class="col-md-3 text-center mt-5">
            <div class="logo">
              <img height="50px" src="../assets/images/bots.png" alt />
              <h3>Bootstrap</h3>
            </div>
          </div>
        </div>
      </div>
    </section>

    <b-card id="projeler" no-body>
      <b-tabs pills card align="center">
        <b-tab title="E-Garsonum" active
          ><b-card-text>
            <!-- E-Garsonum -->
            <e-garsonum></e-garsonum>
            <!-- E-Garsonum -->
          </b-card-text></b-tab
        >
        <b-tab title="Modem Hex Güncelleme"
          ><b-card-text>
            <!-- Hex Update -->
            <hex-update></hex-update>
            <!-- Hex Update -->
          </b-card-text></b-tab
        >
      </b-tabs>
    </b-card>
  </div>
</template>

<script>
import egarsonum from "./e-garsonum";
import hexUpdateVue from "./hexUpdate.vue";

export default {
  components: {
    "e-garsonum": egarsonum,
    "hex-update": hexUpdateVue,
  },
  data() {
    return {
      resim_page: 0,
    };
  },
};
</script>

<style scoped>
.pic {
  -webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.3);
}
.pic:hover {
  -webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.5);
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.5);
}
#nav-bar {
  background-color: blue !important;
}
#nav-collapse a {
  color: white !important;
}
#header {
  background-image: url(../assets/images/background.png);
  filter: grayscale(0.1);
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  height: 500px;
}
.resim img {
  height: 150px;
  border-radius: 50%;
  margin-top: 10px;
  -webkit-box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.9);
  box-shadow: 0px 10px 25px 0px rgba(0, 0, 0, 0.9);
}
.resim h1 {
  margin-top: 30px;
  color: white;
}
.resim h2 {
  margin-top: 30px;
  color: white;
  font-size: 30px !important;
}
.resim h3 {
  margin-top: 30px;
  color: white;
}
#info a {
  margin: 20px 15px 5px 15px;
  position: relative;
  top: -15px;
  border: 1px solid gray;
  padding: 15px;
  background-color: white;
  border-radius: 100%;
  box-shadow: 0px 1px 10px 0px rgba(0, 0, 0, 0.9);
}

.teknoloji img {
  margin-bottom: 50px;
}
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