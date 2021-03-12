<template>
  <div>
    <div class="container-fluid">
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
            - nodemon
          </div>
          <div style="margin-bottom: 12px" class="col-md-6 text-center">
            - net
          </div>
          <div style="margin-bottom: 12px" class="col-md-6 text-center">
            - fs
          </div>
          <div style="margin-bottom: 12px" class="col-md-6 text-center">
            - dotenv
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12 text-center">
          <h2 class="mt-3">Proje Bilgisi</h2>
        </div>
        <div class="col-md-2 text-left"></div>
        <div class="col-md-8 text-left ml-3">
          <p style="margin-top: 30px; margin-bottom: 30px">
            Sahadaki bulunan IOT cihazın güncellenmesi istediğinde sunucumuzda
            bulunan Nodejs ile geliştirdiğim hex kodu gönderen bir sistemdir.
            Cihaz hex kodunun satırlarını tek tek sunucudan ister. Sunucu da
            bulunan hex dosyası Nodejs ile geliştirilmiş yazılım sayesinde Hex
            kodunu satır satır okuyarak TCP ile bağlanmış cihaza Hex kodunu
            satır satır gönderir.
          </p>
        </div>
        <div class="col-md-2 text-left"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>