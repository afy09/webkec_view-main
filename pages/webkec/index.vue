<template>
  <div style="background-color: white">
    <!-- META -->
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;1,100;1,300;1,400;1,500;1,700&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="~/assets/css/webkec.css" />
    <!-- NAVBAR SATART -->

    <div id="navbar" style="position: fixed; width: 100%; z-index: 12">
      <b-navbar toggleable="lg" class="navbar-2">
        <b-navbar-brand href=""
          ><img src="~/assets/img/logokecc.png" alt=""
        /></b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-navbar-nav>
              <b-nav-item href="profil" class="nav-p">Profil</b-nav-item>
              <b-nav-item href="berita">Berita</b-nav-item>
              <b-nav-item href="dokumen">Dokumen</b-nav-item>
              <b-nav-item href="posyandu">Posyandu</b-nav-item>
              <b-nav-item href="galeri">Galeri</b-nav-item>
            </b-navbar-nav>

            <b-nav-item-dropdown right>
              <!-- Using 'button-content' slot -->
              <template #button-content>
                <em>Daftar Kelurahan</em>
              </template>
              <b-dropdown-item href="#">Bantar Jati</b-dropdown-item>
              <b-dropdown-item href="#">Cibuluh</b-dropdown-item>
              <b-dropdown-item href="#">Ciluar</b-dropdown-item>
              <b-dropdown-item href="#">Cimahpar</b-dropdown-item>
              <b-dropdown-item href="#">Ciparigi</b-dropdown-item>
              <b-dropdown-item href="#">Kedunghalang</b-dropdown-item>
              <b-dropdown-item href="#">Tanahbaru</b-dropdown-item>
              <b-dropdown-item href="#">Tegalgundil</b-dropdown-item>
            </b-nav-item-dropdown>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>

    <!-- NAVBAR END -->

    <button v-show="isVisible" @click="scrollToTop" class="back-to-top">
      ↑
    </button>

    <!-- HERO SECTION -->
    <div id="slider">
      <div class="slides">
        <div class="slider">
          <div class="legend"></div>
          <div class="content">
            <div class="content-txt">
              <h1>Kecamatan <span>Bogor Utara</span></h1>
              <p>
                Selamat Datang di Website Resmi Pemerintah Kota Bogor, Kecamatan
                Bogor Utara
              </p>
            </div>
          </div>
          <div class="image">
            <img src="~/assets/img/BG2-KECAMATAN-01.jpg" />
          </div>
        </div>

        <div class="slider">
          <div class="legend"></div>
          <div class="content">
            <div class="content-txt">
              <h1>Kecamatan <span>Bogor Utara</span></h1>
              <p style="color: black">
                Selamat Datang di Website Resmi Pemerintah Kota Bogor, Kecamatan
                Bogor Utara
              </p>
            </div>
          </div>
          <div class="image">
            <img src="~/assets/img/banner1revv.jpg" />
          </div>
        </div>

        <div class="slider">
          <div class="legend"></div>
          <div class="content">
            <div class="content-txt">
              <h1>Kecamatan <span>Bogor Utara</span></h1>
              <p>
                Selamat Datang di Website Resmi Pemerintah Kota Bogor, Kecamatan
                Bogor Utara
              </p>
            </div>
          </div>
          <div class="image">
            <img src="~/assets/img/banner3.jpg" />
          </div>
        </div>

        <div class="slider">
          <div class="legend"></div>
          <div class="content">
            <div class="content-txt">
              <h1>Kecamatan <span>Bogor Utara</span></h1>
              <p>
                Selamat Datang di Website Resmi Pemerintah Kota Bogor, Kecamatan
                Bogor Utara
              </p>
            </div>
          </div>
          <div class="image">
            <img src="~/assets/img/banner6.jpeg" />
          </div>
        </div>
      </div>
      <div class="switch">
        <ul>
          <li>
            <div class="on"></div>
          </li>
          <li></li>
          <li></li>
          <li></li>
        </ul>
      </div>
    </div>
    <!-- HERO SECTION END-->

    <!-- BACK TO TOP -->
    <a href="#slider" id="myBtn" title="Go to top" style="scroll-behavior: auto"
      ><i class="fa-solid fa-angles-up"></i
    ></a>
    <!-- BACK TO TOP END -->

    <!-- SAMBUTAN CAMAT -->
    <div class="cam" style="margin: 120px 10px 100px 10px">
      <h2 class="text-center"><span>SAMBUTAN </span>CAMAT</h2>
      <div
        class="cam-img-sam d-flex justify-content-center"
        style="margin-top: 50px"
      >
        <div class="cam-img">
          <img src="~/assets/img/camatbogut12.png" alt="camatbogut.jpg" />
          <div class="nama-cam" style="text-align: center">
            <h5>Camat Kec. Bogor Utara</h5>
            <p>Riki Robiansah, S.STP</p>
          </div>
        </div>
        <div class="cam-sam">
          <p>
            Rasa sykur terbesar selalu terhaturkan kepada Allah SWT. Karena
            nikmat kesehatan dan kesempatan dari-Nya, masyarakat Kota Bogor
            tetap bersemangat menuju hidup sehat. Selamat datang di situs resmi
            Website Kecamatan Bogor Utara Kota Bogor. Website Kecamatan Bogor
            Utara memuat profil Kecamatan Bogor Utara dan informasi penting
            berbagai program dan kegiatan Kecamatan Bogor Utara Kota Bogor. Kami
            harap website ini dapat bermanfaat dalam memberikan data dan
            informasi yang dapat digunakan untuk masyarakat.
          </p>
        </div>
      </div>
    </div>

    <!-- SAMBUTAN CAMAT END -->

    <!-- BERITA  -->
    <div id="kat-ber" class="kat-ber" style="text-align: center; padding: 15px">
      <h2>INFORMASI <span>TERKINI</span></h2>
      <div
        id="kat-btn"
        class="kat-ber2 d-flex"
        style="justify-content: center; gap: 30px; margin-top: 20px"
      >
        <button class="kat-btn active">BERITA TERBARU</button>
        <button class="kat-btn">BERITA WILAYAH</button>
        <button class="kat-btn">BERITA KOTA</button>
      </div>
      <div
        class="card-section d-flex"
        style="justify-content: center; gap: 30px"
      >
        <!-- CAROSEL -->
        <div class="container">
          <div class="carousel-view">
            <button id="prev-btn" class="prev-btn">
              <svg viewBox="0 0 512 512" width="20" title="chevron-circle-left">
                <path
                  d="M256 504C119 504 8 393 8 256S119 8 256 8s248 111 248 248-111 248-248 248zM142.1 273l135.5 135.5c9.4 9.4 24.6 9.4 33.9 0l17-17c9.4-9.4 9.4-24.6 0-33.9L226.9 256l101.6-101.6c9.4-9.4 9.4-24.6 0-33.9l-17-17c-9.4-9.4-24.6-9.4-33.9 0L142.1 239c-9.4 9.4-9.4 24.6 0 34z"
                />
              </svg>
            </button>
            <div id="item-list" class="item-list">
              <div class="card-ber">
                <div class="card-ber-img">
                  <img src="~/assets/img/berita1.png" alt="berita1.jpg" />
                </div>
                <p>22-10-2024</p>
                <h5 style="color: black"><a href="">Bangkitkan UMKM</a></h5>
                <p>
                  Camat Bogor Utara, Riki Robiansah meminta seluruh lurah dan
                  bawahannya yang bertugas di Kecamatan Bogor Utara......
                </p>
                <button>Baca Selengkapnya</button>
              </div>

              <div class="card-ber">
                <div class="card-ber-img">
                  <img src="~/assets/img/berita2.png" alt="berita1.jpg" />
                </div>
                <p>22-10-2024</p>
                <h5 style="color: black"><a href="">Buka Musrenbang ...</a></h5>
                <p>
                  BOGOR. Wali Kota Bogor, Bima Arya membuka secara resmi
                  Musyawarah Rencana Pembangunan (Musrenbang) Kecamatan Bogor
                  Utara......
                </p>

                <button>Baca Selengkapnya</button>
              </div>

              <div class="card-ber">
                <div class="card-ber-img">
                  <img src="~/assets/img/berita3.png" alt="berita1.jpg" />
                </div>
                <p>22-10-2024</p>
                <h5 style="color: black">
                  <a href="">Gelar operasi PA di...</a>
                </h5>
                <p>
                  Operasi pasar dilakukan Kecamatan Bogor Utara, Kota Bogor pada
                  hari Jumat (14/01/2022). Operasi pasar tersebut dilakukan di
                  halaman Kantor Kec......
                </p>

                <button>Baca Selengkapnya</button>
              </div>

              <div class="card-ber">
                <div class="card-ber-img">
                  <img src="~/assets/img/berita4.png" alt="berita4.jpg" />
                </div>
                <p>22-10-2024</p>
                <h5 style="color: black"><a href="">Bogor si asyik ...</a></h5>
                <p>
                  Wali Kota Bogor, Bima Arya mengapresiasi Sistem Informasi
                  Analisis Potensi dan Permasalahan Kecamatan......
                </p>
                <button>Baca Selengkapnya</button>
              </div>
            </div>
            <button id="next-btn" class="next-btn">
              <svg
                viewBox="0 0 512 512"
                width="20"
                title="chevron-circle-right"
              >
                <path
                  d="M256 8c137 0 248 111 248 248S393 504 256 504 8 393 8 256 119 8 256 8zm113.9 231L234.4 103.5c-9.4-9.4-24.6-9.4-33.9 0l-17 17c-9.4 9.4-9.4 24.6 0 33.9L285.1 256 183.5 357.6c-9.4 9.4-9.4 24.6 0 33.9l17 17c9.4 9.4 24.6 9.4 33.9 0L369.9 273c9.4-9.4 9.4-24.6 0-34z"
                />
              </svg>
            </button>
          </div>
        </div>
        <!-- CAROSEL END -->
      </div>
    </div>
    <!-- BERITA END  -->

    <!-- OUR AGENDA LOKASI BANNER -->

    <div class="keg">
      <div class="keg-agn-1">
        <div class="lok-ban">
          <h3><span>LOKASI</span> KANTOR</h3>
          <div class="lok">
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3963.5338823061356!2d106.80870307358114!3d-6.580352064323299!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69c42eb7a8c665%3A0x66758cee3516bf26!2sNorth%20Bogor%20District%20Office!5e0!3m2!1sen!2sus!4v1715149152653!5m2!1sen!2sus"
              width="600"
              height="450"
              style="border: 0"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>

          <div class="peta-img">
            <img src="~assets/img/petabogut-01.png" alt="peta_bogut" />
          </div>
        </div>

        <div class="keg-cal">
          <h3><span>AGENDA</span> KEGIATAN</h3>
          <div class="keg-agn-2">
            <h4 class="keg-h4">Aula Kecamatan Bogor Utara</h4>
            <p style="font-style: italic">Kamis/2019-02-14 13:00:00</p>
            <p class="keg-p">
              Rapat Koordinasi Mabiran Bogor Utara dengan Kwarran Bogor Utara.
            </p>

            <h4 class="keg-h4">Ruang Paseban Sri Bima Balaiko</h4>
            <p style="font-style: italic">Kamis/2019-02-13 08:00:00</p>
            <p class="keg-p">
              Pelatihan Pengelolaan Kecamatan dan Kelurahan di Kota Bogor
            </p>

            <h4 class="keg-h4">Posyandu Pitaloka</h4>
            <p style="font-style: italic">Jumat/2018-08-31 13:00:00</p>
            <p class="keg-p">
              lurah, ekbang, pem dan staf ke posyandu pitaloka dan sekaligus
              memantau perbaikan jalan di rw 08
            </p>
          </div>
          <h3><span>CALE</span>NDER</h3>
          <div class="calender">
            <b-row class="calender-2">
              <b-col md="auto" class="cal-1">
                <b-calendar
                  class="cal-2"
                  v-model="value"
                  @context="onContext"
                  locale="en-US"
                ></b-calendar>
              </b-col>
              <b-col>
                <pre class="small">{{ context }}</pre>
              </b-col>
            </b-row>
          </div>

          <h3><span>BAN</span>NER</h3>
          <div class="ban">
            <a href="https://jabarprov.go.id/" target="_blank" class="jabar"
              ><img src="~/assets/img/jabar.jpg" alt="WEB_JABAR"
            /></a>

            <a href="https://kotabogor.go.id/" class="kotabogor" target="_blank"
              ><img src="~/assets/img/kotabogor.jpg" alt="WEB_KOTABOGOR"
            /></a>

            <a href="https://www.kominfo.go.id/" class="kominfo" target="_blank"
              ><img src="~/assets/img/kominfo.jpg" alt="WEB_KOMINFO"
            /></a>
          </div>
        </div>
      </div>
    </div>

    <!-- OUR AGENDA LOKASI BANNER END -->

    <!-- FOOTHER -->
    <footer>
      <div class="all-footer">
        <div class="footer-1">
          <div class="foot-cont">
            <i class="fa-solid fa-envelope fa-xl"></i>
            <h3>KONTAK KAMI</h3>
          </div>
          <div class="foot-almt" style="margin-top: 20px">
            <h5>Alamat Kantor :</h5>
            <p style="margin-bottom: 20px; font-size: 14px">
              Jl. Gagalur II No.2
            </p>
          </div>

          <div class="foot-almt" style="margin-top: 30px">
            <h5>Email :</h5>
            <p style="margin-bottom: 20px; font-size: 14px">
              kec.bout@kotabogor.go.id
            </p>
          </div>

          <div class="foot-almt" style="margin-top: 30px">
            <h5>No Telopn :</h5>
            <p style="margin-bottom: 20px; font-size: 14px">(0251) 8323444</p>
          </div>
        </div>
        <div class="line"></div>
        <div class="sosmed">
          <a href="#"> <i class="fa-brands fa-instagram fa-xl"></i></a>
          <a href="#"> <i class="fa-brands fa-x-twitter fa-xl"></i></a>
          <a href="#"> <i class="fa-brands fa-facebook fa-xl"></i></a>
          <a href="#"> <i class="fa-brands fa-youtube fa-xl"></i></a>
        </div>
        <div class="copyright">
          <p>
            copyright &copy; by <a href="">DISKOMINFO</a> Kota Bogor. All Right
            Reserved.
          </p>
        </div>
      </div>
    </footer>
    <!-- FOOTHER END -->
  </div>
</template>

<!-- --------------------------- -->
<!--------- ALL STYLE ------------->
<!-- --------------------------- -->

<style>
body {
  font-family: "Roboto", sans-serif;
}

#navbar {
  color: black;
  font-weight: bold;
  background-color: white;
}

.navbar-2 {
  padding: 5px 60px 5px 60px;
}

.contain-3 {
  background-color: rgba(255, 255, 255, 0.53);
}

.btn-hero {
  padding: 10px 15px 10px 15px;
  border-radius: 50px;
  border: 2px solid black;
  color: rgb(0, 0, 0);
  background-color: transparent;
}

.btn-hero:hover {
  background-color: #3375cc;
  color: white;
  font-size: 15px;
  transition: 500ms;
  border-style: none;
}

/* BACK TO TOP  */
#myBtn {
  /* Hidden by default */
  position: fixed; /* Fixed/sticky position */
  bottom: 20px; /* Place the button at the bottom of the page */
  right: 30px; /* Place the button 30px from the right */
  z-index: 9999999; /* Make sure it does not overlap */
  border: 1px solid #3375cc; /* Remove borders */
  /* outline: none;  */
  background-color: rgba(0, 4, 244, 0); /* Set a background color */
  color: #3375cc; /* Text color */
  cursor: pointer; /* Add a mouse pointer on hover */
  padding: 10px 15px 10px 15px; /* Some padding */
  border-radius: 50px; /* Rounded corners */
  font-size: 18px; /* Increase font size */
  scroll-behavior: auto;
}

#myBtn:hover {
  background-color: #3375cc; /* Add a dark-grey background on hover */
  color: white;
  scroll-behavior: smooth;
}

/* HERO SECTION */
#slider {
  width: 100%;
  height: 580px;
  position: relative;
  overflow: hidden;
}
@keyframes load {
  from {
    left: -100%;
  }
  to {
    left: 0;
  }
}
.slides {
  width: 400%;
  height: 100%;
  margin-top: 20px;
  position: relative;
  -webkit-animation: slide 30s infinite;
  -moz-animation: slide 30s infinite;
  animation: slide 30s infinite;
}
.slider {
  width: 25%;
  height: 100%;
  float: left;
  position: relative;
  z-index: 1;
  overflow: hidden;
}
.slide img {
  width: 100%;
  height: 100%;
}
.slide img {
  width: 100%;
  height: 10%;
}
.image {
  width: 100%;
  height: 100%;
}
.image img {
  width: 100%;
  height: 100%;
}

/* Legend */
.legend {
  border: 500px solid transparent;
  border-left: 800px solid #3574cc2b;
  border-bottom: 0;
  position: absolute;
  bottom: 0;
}

/* Contents */
.content {
  width: 100%;
  height: 100%;
  position: absolute;
  overflow: hidden;
}
.content-txt {
  width: 400px;
  height: 150px;
  float: left;
  position: relative;
  top: 350px;
  -webkit-animation: content-s 7.5s infinite;
  -moz-animation: content-s 7.5s infinite;
  animation: content-s 7.5s infinite;
}
.content-txt h1 {
  text-transform: uppercase;
  font-size: 24px;
  color: black;
  text-align: left;
  margin-left: 30px;
  padding-bottom: 10px;
  font-weight: bold;
}

.content-txt h1 span {
  color: #3375cc;
  font-weight: bold;
}

/* .content-txt h3 {
  text-transform: uppercase;
  font-size: 18px;
  color: black;
  text-align: left;
  margin-left: 30px;
  padding-bottom: 10px;
  font-weight: bold;
} */

.content-txt p {
  font-weight: normal;
  font-size: 14px;
  font-style: italic;
  font-weight: bold;
  color: #fff;
  text-align: left;
  margin-left: 30px;
}

/* Switch */
.switch {
  width: 120px;
  height: 10px;
  position: absolute;
  bottom: 50px;
  z-index: 99;
  left: 30px;
}
.switch > ul {
  list-style: none;
}
.switch > ul > li {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #333;
  float: left;
  margin-right: 5px;
  cursor: pointer;
}
.switch ul {
  overflow: hidden;
}
.on {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  background: #3375cc;
  position: relative;
  -webkit-animation: on 30s infinite;
  -moz-animation: on 30s infinite;
  animation: on 30s infinite;
}

/* Animation */
@-webkit-keyframes slide {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: -100%;
  }
  46% {
    margin-left: -100%;
  }
  50% {
    margin-left: -200%;
  }
  71% {
    margin-left: -200%;
  }
  75% {
    margin-left: -300%;
  }
  96% {
    margin-left: -300%;
  }
}
@-moz-keyframes slide {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: -100%;
  }
  46% {
    margin-left: -100%;
  }
  50% {
    margin-left: -200%;
  }
  71% {
    margin-left: -200%;
  }
  75% {
    margin-left: -300%;
  }
  96% {
    margin-left: -300%;
  }
}
@keyframes slide {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: -100%;
  }
  46% {
    margin-left: -100%;
  }
  50% {
    margin-left: -200%;
  }
  71% {
    margin-left: -200%;
  }
  75% {
    margin-left: -300%;
  }
  96% {
    margin-left: -300%;
  }
}

@-webkit-keyframes content-s {
  0% {
    left: -420px;
  }
  10% {
    left: 0px;
  }
  30% {
    left: 0px;
  }
  40% {
    left: 0px;
  }
  50% {
    left: 0px;
  }
  60% {
    left: 0px;
  }
  70% {
    left: 0;
  }
  80% {
    left: -420px;
  }
  90% {
    left: -420px;
  }
  100% {
    left: -420px;
  }
}
@-moz-keyframes content-s {
  0% {
    left: -420px;
  }
  10% {
    left: 0px;
  }
  30% {
    left: 0px;
  }
  40% {
    left: 0px;
  }
  50% {
    left: 0px;
  }
  60% {
    left: 0px;
  }
  70% {
    left: 0;
  }
  80% {
    left: -420px;
  }
  90% {
    left: -420px;
  }
  100% {
    left: -420px;
  }
}
@keyframes content-s {
  0% {
    left: -420px;
  }
  10% {
    left: 20px;
  }
  15% {
    left: 0px;
  }
  30% {
    left: 0px;
  }
  40% {
    left: 0px;
  }
  50% {
    left: 0px;
  }
  60% {
    left: 0px;
  }
  70% {
    left: 0;
  }
  80% {
    left: -420px;
  }
  90% {
    left: -420px;
  }
  100% {
    left: -420px;
  }
}

@-webkit-keyframes on {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: 15px;
  }
  46% {
    margin-left: 15px;
  }
  50% {
    margin-left: 30px;
  }
  71% {
    margin-left: 30px;
  }
  75% {
    margin-left: 45px;
  }
  96% {
    margin-left: 45px;
  }
}

@-moz-keyframes on {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: 15px;
  }
  46% {
    margin-left: 15px;
  }
  50% {
    margin-left: 30px;
  }
  71% {
    margin-left: 30px;
  }
  75% {
    margin-left: 45px;
  }
  96% {
    margin-left: 45px;
  }
}

@keyframes on {
  0%,
  100% {
    margin-left: 0%;
  }
  21% {
    margin-left: 0%;
  }
  25% {
    margin-left: 15px;
  }
  46% {
    margin-left: 15px;
  }
  50% {
    margin-left: 30px;
  }
  71% {
    margin-left: 30px;
  }
  75% {
    margin-left: 45px;
  }
  96% {
    margin-left: 45px;
  }
}
/* COBA */

/* CAMAT  */

.cam h2 {
  font-weight: bold;
  color: #3375cc;
}

.cam h2 span {
  border-bottom: 2px solid #3375cc;
  color: black;
}

.cam-img-sam {
  gap: 20px;
}

.nama-cam {
  border: 0.5px solid black;
  padding: 10px 10px 1px 10px;
}

.nama-cam p {
  margin-bottom: 10px;
}

.cam-sam {
  width: 40%;
}

/* BERITA */

.kat-ber {
  background-image: linear-gradient(180deg, white, rgb(201, 201, 201), white);
  padding: 100px 20px 50px 20px;
}

.kat-ber h2 {
  margin-top: 50px;
  font-weight: 900;
  color: #3375cc;
  margin-bottom: 50px;
}

.kat-ber h2 span {
  border-bottom: 2px solid #3375cc;
  color: black;
}

.kat-btn {
  color: black;
  font-size: 15px;
  font-weight: 400;
  /* margin-top: 50px; */
  border: none;
}

.active,
.kat-btn:hover {
  color: #3375cc;
  font-weight: bold;
  border-bottom: 2px solid #3375cc;
  padding: 10px;
  cursor: pointer;
  z-index: 7;
}

/* corasel */

button {
  border: none;
  cursor: pointer;
  color: white;
  background: none;
  transition: all 0.3s ease-in-out;
}

.container {
  width: 100%;
  height: auto;
  margin-top: 30px;
  padding: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  /* background-color: white; */
}

.carousel-view {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
  /* padding: 100px 0; */
  transition: all 0.25s ease-in;
}

.carousel-view .item-list {
  max-width: 950px;
  width: auto;
  /* padding: 10px; */
  display: flex;
  gap: 20px;
  text-align: center;
  scroll-behavior: smooth;
  transition: all 0.25s ease-in;
  -ms-overflow-style: none; /* IE and Edge */
  scrollbar-width: none; /* Firefox */
  overflow: auto;
  scroll-snap-type: x mandatory;
}

/* Hide scrollbar for Chrome, Safari and Opera */
.item-list::-webkit-scrollbar {
  display: none;
}

.prev-btn {
  background: none;
  cursor: pointer;
}

.next-btn {
  cursor: pointer;
}

.card-ber {
  scroll-snap-align: center;
  min-width: 300px;
  height: auto;
  padding: 20px;
  box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.356);
  border-radius: 20px;
  margin: 10px;
  background-color: white;
}
.card-ber p {
  font-size: 12px;
}

.card-ber h5 a {
  color: black;
}

.card-ber h5 a:hover {
  color: #3575cc;
}

.card-ber button {
  border-style: none;
  padding: 10px;
  border-radius: 50px;
  color: white;
  background-color: #3575cc;
  font-size: 12px;
}

.card-ber button:hover {
  background-color: #0d1f38;
  color: white;
  padding: 15px;
  transition-duration: 500ms;
}

.card-ber-img img {
  width: 100%;
  height: 190px;
}

/* AGENDA */

.keg-agn-1 {
  display: flex;
  justify-content: start;
  /* margin-left: 80px; */
}

.keg-cal {
  margin: 30px;
}

.lok-ban h3,
.keg-cal h3 {
  font-weight: bold;
  margin-bottom: 30px;
  margin-top: 30px;
  color: #3375cc;
}

.lok-ban h3 span,
.keg-cal h3 span {
  border-bottom: 2px solid #3375cc;
  color: black;
}

.keg-agn-2 {
  width: 500px;
  height: 500px;
  margin-top: 20px;
  margin-bottom: 50px;
  margin: auto;
  padding: 130px 50px 50px 50px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: start;
  overflow: scroll;
  border-left: 1px solid black;
}

.keg-h4 {
  margin-top: 40px;
}

.keg-p {
  border-bottom: 1px dotted black;
  padding: 0px 0px 10px 0px;
}

.calender {
  /* margin-left: 230px; */
  margin: auto;
  display: flex;
  justify-content: start;
  margin-bottom: 50px;
}

.calender .cal-1 {
  background-color: rgb(201, 201, 201);
  border: 1.5px solid #0d1f38;
  border-radius: 10px;
  padding: 30px;
}

.ban {
  margin-top: 50px;
}

/* .ban img {
  width: 80%;
  height: 100px;
} */

.ban a img {
  height: 110px;
  margin-bottom: 20px;
}

.ban a img:hover {
  background-color: rgba(0, 0, 0, 0.338);
}

/* LOKASI */
.lok-ban {
  margin: 30px 30px 30px 50px;
}

.lok {
  background-color: #3575cc;
  padding: 20px;
  border-radius: 20px;
  border: 2px solid black;
}

.peta-img {
  margin-top: 50px;
}

/* FOOTER */

.all-footer {
  background-color: rgb(20, 18, 26);
  margin-top: 80px;
  padding: 50px 80px 10px 80px;
  text-align: center;
  color: rgba(255, 255, 255, 0.4);
}

.foot-cont {
  display: flex;
  justify-content: center;
  color: white;
  gap: 13px;
}

.foot-cont h3 {
  font-size: 20px;
}

.foot-cont i {
  padding-top: 10px;
}

.footer-1 p {
  font-size: 15px;
  color: white;
  font-style: italic;
  margin-top: 10px;
}

.line {
  display: flex;
  justify-content: center;
  width: 100%;
  height: 1px;
  background-color: white;
  text-align: center;
  margin-top: 40px;
}

.sosmed {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-top: 30px;
}

.sosmed a {
  color: white;
}

.sosmed a i:hover {
  font-size: 30px;
  color: #3575cc;
}

.copyright {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: 13px;
  text-align: center;
  padding: 5px;
  padding-top: 25px;
}

/* MEDIA QUERY / RESPONSIVE DESIGN */

@media (max-width: 550px) {
  .navbar-2 {
    padding: 20px;
  }

  #slider {
    width: 100%;
    height: 350px;
    position: relative;
    overflow: hidden;
  }

  .legend {
    display: none;
  }

  .content {
    display: none;
  }

  /* SAM MOBILE */
  .cam-img-sam {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .cam h2 {
    font-size: 25px;
    margin-bottom: 100px;
  }

  .cam-img img {
    width: 100%;
    margin: 0px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .cam-sam {
    width: 100%;
    margin-top: 5px;
  }

  /* KATBER MOBILE */
  .kat-ber h2 {
    font-size: 25px;
    margin-top: -30px;
  }

  .kat-btn {
    font-size: 13px;
  }

  .carousel-view .item-list {
    max-width: 270px;
  }
  .card-ber {
    min-width: 250px;
  }

  /* LOKASI, CAL, BAN */

  .keg-agn-1 {
    display: flex;
    justify-content: center;
    flex-direction: column;
  }

  .keg-agn-1 h3 {
    font-size: 20px;
  }

  .lok-ban h3 {
    font-size: 23px;
  }

  .lok iframe {
    display: flex;
    justify-content: center;
    width: 100%;
    height: 300px;
  }

  .peta-img img {
    width: 100%;
    margin: 10px;
  }

  .keg-cal h3 {
    font-size: 23px;
  }

  .keg-agn-2 {
    width: 100%;
    margin-top: 50px;
    margin-bottom: 60px;
  }

  .keg-h4 {
    font-size: 18px;
  }

  .keg-p {
    font-size: 12px;
  }

  .calender .cal-1 {
    width: 100%;
    display: flex;
    justify-content: center;
  }
}
</style>

<!-- --------- -->
<!--ALL SCRIPT -->
<!-- --------- -->

<!-- script slide card -->
<script>
const prev = document.getElementById("prev-btn");
const next = document.getElementById("next-btn");
const list = document.getElementById("item-list");

const itemWidth = 150;
const padding = 10;

prev.addEventListener("click", () => {
  list.scrollLeft -= itemWidth + padding;
});

next.addEventListener("click", () => {
  list.scrollLeft += itemWidth + padding;
});
</script>
<!-- script slide card end -->

<script>
import BackToTop from "~/components/BackToTop.vue";
export default {
  data() {
    return {
      isVisible: false,
    };
  },
  mounted() {
    window.addEventListener("scroll", this.toggleVisibility);
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.toggleVisibility);
  },
  methods: {
    toggleVisibility() {
      this.isVisible = window.scrollY > 300;
    },
    scrollToTop() {
      window.scrollTo({
        top: 0,
        behavior: "smooth",
      });
    },
  },
};
</script>

<!-- script vue -->
<script>
import Slider from "@/components/web/slider.vue";

export default {
  components: {
    Slider,
  },

  layout: "empty",

  //meta
  head() {
    return {
      title: "Kecamatan Bogor Utara",
      meta: [
        {
          hid: "og:title",
          name: "og:title",
          content: "Belajar Bareng - Mari Belajar Bareng",
        },
        {
          hid: "og:site_name",
          name: "og:site_name",
          content: "Belajar Bareng - Mari Belajar Bareng",
        },
        {
          hid: "og:image",
          name: "og:image",
          content: "https://i.imgur.com/xKOCz0P.png",
        },
      ],
    };
  },

  // data() {
  //   return {
  //     value: "",
  //     context: null,
  //   };
  // },
  // methods: {
  //   onContext(ctx) {
  //     this.context = ctx;
  //   },
  // },
};
</script>
<!-- script end -->
