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
        <b-navbar-brand href="./"
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

    <!-- BACK TO TOP -->
    <a href="#slider" id="myBtn" title="Go to top" style="scroll-behavior: auto"
      ><i class="fa-solid fa-angles-up"></i
    ></a>
    <!-- BACK TO TOP END -->

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

    <!-- POSYANDU START -->
    <div class="posyandu">
      <b-tabs content-class="mt-3" justified>
        <!-- posyandu kecamatan -->
        <b-tab title="Profile Posyandu" class="tabs" active>
          <h2>Profile <span>Posyandu</span></h2>

          <p>
            Pengertian Posyandu adalah kegiatan kesehatan dasar yang
            diselenggarakan dari, oleh dan untuk masyarakat yang dibantu oleh
            petugas kesehatan.
          </p>

          <div class="tabpos">
            <div class="tupos">
              <h4>Tujuan Posyandu</h4>
              <h5>Tujuan posyandu antara lain:</h5>
              <p>
                - Menurunkan angka kematian bayi (AKB), angka kematian ibu (ibu
                hamil), melahirkan dan nifas.
                <br />
                - Membudayakan NKBS
                <br />
                - Meningkatkan peran serta masyarakat untuk mengembangkan
                kegiatan kesehatan dan KB serta kegiatan lainnya yang menunjang
                untuk tercapainya masyarakat sehat sejahtera.
                <br />
                - Berfungsi sebagai wahana gerakan reproduksi keluarga
                sejahtera, gerakan ketahanan keluarga dan gerakan ekonomi
                keluarga sejahtera.
              </p>
              <h5 class="keg">Kegiatan Pokok Posyandu :</h5>
              <p>
                - Menurunkan angka kematian bayi (AKB), angka kematian ibu (ibu
                hamil), melahirkan dan nifas.
                <br />
                - Membudayakan NKBS
                <br />
                - Meningkatkan peran serta masyarakat untuk mengembangkan
                kegiatan kesehatan dan KB serta kegiatan lainnya yang menunjang
                untuk tercapainya masyarakat sehat sejahtera.
                <br />
                - Berfungsi sebagai wahana gerakan reproduksi keluarga
                sejahtera, gerakan ketahanan keluarga dan gerakan ekonomi
                keluarga sejahtera.
                <br />
                - KIA
                <br />
                - KB
                <br />
                - Imunisasi
                <br />
                - Gizi
                <br />
                - Penanggulangan diare
              </p>
            </div>
          </div>
        </b-tab>

        <!-- Data Posyandu -->
        <b-tab title="Data Posyandu">
          <h2>Data <span>Posyandu</span></h2>
          <div class="galeri-foto">
            <div class="album">
              <div class="album-img">
                <a href="#"
                  ><img src="~assets/img/posyandu/bantarjati.jpg" alt=""
                /></a>
              </div>
              <div class="album-content">
                <h5>Bantarjati</h5>
                <div class="album-content-date"></div>
              </div>
            </div>
            <div class="album">
              <div class="album-img">
                <a href="#"
                  ><img src="~assets/img/posyandu/cibuluh.jpg" alt=""
                /></a>
              </div>
              <div class="album-content">
                <h5>Cibuluh</h5>
                <div class="album-content-date"></div>
              </div>
            </div>
            <div class="album">
              <div class="album-img">
                <a href="#"
                  ><img src="~assets/img/posyandu/ciluar.jpg" alt=""
                /></a>
              </div>
              <div class="album-content">
                <h5>Ciluar</h5>
                <div class="album-content-date"></div>
              </div>
            </div>
            <div class="album">
              <div class="album-img">
                <a href="#"
                  ><img src="~assets/img/posyandu/cimahpar.jpg" alt=""
                /></a>
              </div>
              <div class="album-content">
                <h5>Cimahpar</h5>
                <div class="album-content-date"></div>
              </div>
            </div>
            <div class="album">
              <div class="album-img">
                <a href="#"
                  ><img src="~assets/img/posyandu/ciparigi.jpg" alt=""
                /></a>
              </div>
              <div class="album-content">
                <h5>Ciparigi</h5>
                <div class="album-content-date"></div>
              </div>
            </div>
            <div class="album">
              <div class="album-img">
                <a href="#"
                  ><img src="~assets/img/posyandu/kedunghalang.jpg" alt=""
                /></a>
              </div>
              <div class="album-content">
                <h5>Kedunghalang</h5>
                <div class="album-content-date"></div>
              </div>
            </div>
            <div class="album">
              <div class="album-img">
                <a href="#"
                  ><img src="~assets/img/posyandu/tanahbaru.jpg" alt=""
                /></a>
              </div>
              <div class="album-content">
                <h5>Tanah baru</h5>
                <div class="album-content-date"></div>
              </div>
            </div>
            <div class="album">
              <div class="album-img">
                <a href="#"
                  ><img src="~assets/img/posyandu/tegalgundil.jpg" alt=""
                /></a>
              </div>
              <div class="album-content">
                <h5>Tegal Gundil</h5>
                <div class="album-content-date"></div>
              </div>
            </div>
          </div>
        </b-tab>
      </b-tabs>
    </div>
    <!-- PROFIL START END -->

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

<style>
body {
  font-family: "Roboto", sans-serif;
  scroll-behavior: smooth;
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

/* NAVBAR */
#navbar {
  color: black;
  font-weight: bold;
  background-color: white;
}

.navbar-2 {
  padding: 5px 60px 5px 60px;
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

/* PROFIL STYLE */
.profil {
  margin-top: 30px;
  font-weight: 600;
  padding: 50px;
  /* height: 1000px; */
}

.profil title {
  color: #3375cc;
}

/* profil kec */

.tabs h2 {
  text-align: center;
  margin-top: 50px;
  font-size: 25px;
}

.tabs h2 span {
  color: #3375cc;
}

.tabs p {
  padding: 10px 40px 10px 20px;
  font-weight: 400;
}

.tabwil {
  font-family: arial, sans-serif;
  /* border-collapse: collapse; */
  text-align: center;
  display: flex;
  justify-content: center;
  gap: 20px;
}

.table {
  width: 400px;
}

.batwil h5 {
  text-align: center;
  margin-bottom: 7px;
}

.batwil p {
  border-bottom: 1px solid black;
  text-align: start;
}

.inov {
  margin-top: 50px;
}

/* posyandu */
/* POSYANDU STYLE */
.posyandu {
  margin-top: 30px;
  font-weight: 600;
  padding: 50px;
  /* height: 1000px; */
}

.posyandu title {
  color: #3375cc;
}
.tabpos {
  font-family: arial, sans-serif;
  /* border-collapse: collapse; */
  text-align: center;
  display: flex;
  justify-content: center;
  gap: 20px;
}
.tupos h5 {
  text-align: start;
  margin-bottom: 7px;
}

.tupos p {
  text-align: start;
}

.keg {
  margin-top: 50px;
}

/* Data Posyandu */
.galeri-foto {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin-top: 30px;
}

.album {
  box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.356);
}

.album-img a img {
  width: 300px;
  height: 200px;
}

.album-content {
  padding: 10px;
}

.album-content-date {
  display: flex;
  gap: 5px;
  margin-top: 15px;
}

.album-content-date p {
  margin-top: -10px;
  font-weight: 500;
}

.album-content2 h5 {
  text-align: center;
}

/* visi misi  */

.vs {
  display: flex;
  gap: 15px;
  justify-content: center;
  margin-top: 20px;
}

.misi p {
  border-bottom: 1px solid black;
}

.vs-img {
  margin-top: 20px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

/* data pejabat */
.table-pejabat {
  width: 100%;
}

/* struktur organisasi */
.img-so {
  margin: 40px 200px 20px 200px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

/* peta wilayah */
.all-map {
  display: flex;
  justify-content: center;
  gap: 25px;
  margin-top: 20px;
}

.admin-kec-img img {
  width: 100%;
}

.admin-kota-img img {
  width: 100%;
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

/* RESPONSIVE MOBILE */

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
  /* PROFIL STYLE */
  .profil {
    width: 100%;
    margin-top: 20px;
    padding: 30px;
  }

  .tabwil {
    display: flex;
    justify-content: center;
    flex-direction: column;
  }

  .table {
    width: 100%;
  }

  .vs {
    display: flex;
    flex-direction: column;
  }

  .img-so {
    margin: 15px 1px 1px 1px;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .all-map {
    display: flex;
    justify-content: center;
    flex-direction: column;
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
      title: "POSYANDU | Kecamatan Bogor Utara",
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

  data() {
    return {
      // Note `isActive` is left out and will not appear in the rendered table
      fields: ["No", "Nama_Kelurahan"],
      items: [
        {
          isActive: true,
          No: "1",
          Nama_Kelurahan: "Bantar Jati",
        },
        {
          isActive: true,
          No: "2",
          Nama_Kelurahan: "Cibuluh",
        },
        {
          isActive: true,
          No: "3",
          Nama_Kelurahan: "Tanah Baru",
        },
        {
          isActive: true,
          No: "4",
          Nama_Kelurahan: "Kedung Halang",
        },
        {
          isActive: true,
          No: "5",
          Nama_Kelurahan: "Cipairgi",
        },
        {
          isActive: true,
          No: "6",
          Nama_Kelurahan: "Tegal Gundil",
        },
        {
          isActive: true,
          No: "7",
          Nama_Kelurahan: "Cimahpar",
        },
        {
          isActive: true,
          No: "8",
          Nama_Kelurahan: "Ciluar",
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
