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
              <b-dropdown-item href="kelbantarjati"
                >Bantar Jati</b-dropdown-item
              >
              <b-dropdown-item href="kelcibuluh">Cibuluh</b-dropdown-item>
              <b-dropdown-item href="kelciluar">Ciluar</b-dropdown-item>
              <b-dropdown-item href="kelcimahpar">Cimahpar</b-dropdown-item>
              <b-dropdown-item href="kelciparigi">Ciparigi</b-dropdown-item>
              <b-dropdown-item href="kelkedunghalang"
                >Kedunghalang</b-dropdown-item
              >
              <b-dropdown-item href="keltanahbaru">Tanahbaru</b-dropdown-item>
              <b-dropdown-item href="keltegalgundil"
                >Tegalgundil</b-dropdown-item
              >
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

    <!-- KELURAHAN START -->

    <div class="galeri">
      <h2>KELURAHAN <span>CIMAHPAR</span></h2>
      <b-tabs content-class="mt-3" justified>
        <!-- profil -->
        <b-tab title="Profil">
          <!-- <h3>Profil<span> Kelurahan</span></h3> -->
          <div class="profil">
            <div class="profil-lurah">
              <img
                src="~assets/img/cimahpar/lurah-cimahpar.png"
                alt="img-lurah"
              />
              <p
                class="nm-lurah"
                style="text-align: center; font-size: 20px; font-weight: 500"
              >
                Raden Ronny Kunaefi, SH., MA.
              </p>
              <p>
                Rasa syukur terbesar selalu terhaturkan kepada Allah SWT, karena
                nikmat kesehatan dan kesempatan dari-Nya, masyarakat Kota Bogor
                tetap bersemangat menuju hidup sehat. Selamat datang di situs
                resmi Website Kelurahan Bantar cimahpar Kota Bogor. Website
                Kelurahan cimahpar ini memuat Profil Kelurahan cimahpar dan
                informasi penting berbagai program dan kegiatan Kelurahan
                cimahpar Kota Bogor, Kami harap website ini dapat bermanfaat
                dalam memberikan data dan informasi yang dapat digunakan oleh
                masyarakat.
              </p>
            </div>

            <div class="profil-content">
              <h5>Luas Wilayah :</h5>
              <p>
                Luas Wilayah Kelurahan Bantarjati tercatat seluas 650 Ha yang
                terdiri dari 16 RW (RukunWilayah) dan 65 RT (Rukun Tetangga),
                dengan batas-batas sebagai berikut: Sebelah Utara : Kelurahan
                Ciluar Kecamatan Bogor Utara Sebelah Selatan : Kelurahan
                Katulampa Kecamatan Bogor Timur, Sebelah Timur : Jalan Tol
                Jagorawi / Kec. Sukaraja Kab. Bogor, Sebelah Barat : Kelurahan
                Tanah Baru Kecamatan Bogor Utara
              </p>
              <div class="profil-visi">
                <h5>Visi & Misi</h5>
                <p>
                  <span>Visi : </span>"Mewujudkan Wilayah Pemukiman dan
                  Pelayanan Prima"
                </p>
                <p>
                  <span>Misi : </span>
                </p>
                <p class="p-misi">1. Penataan Pemukiman yang nyaman dan asri</p>
                <p class="p-misi">
                  2. Menggerakkan seluruh masyarakat peduli lingkungan
                </p>
                <p class="p-misi">
                  3. Memberikan Pelayanan yang baik dan transparan
                </p>
                <p class="p-misi">
                  4. Memberdayakan usaha ekonomi masyarakat yang mandiri
                </p>
              </div>
            </div>
          </div>
        </b-tab>

        <!-- posyandu -->
        <b-tab title="Posyandu">
          <div class="galeri-foto">
            <div class="album">
              <div class="album-img">
                <a
                  ><img
                    src="~assets/img/cimahpar/pos-mawar-1a.png"
                    alt=""
                    id="show-btn"
                    @click="$bvModal.show('bv-modal-example')"
                /></a>
              </div>
              <div class="album-content">
                <h5>Mawar IA</h5>
              </div>
              <!-- modal -->
              <b-modal id="bv-modal-example" hide-footer>
                <template #modal-title>
                  <h5>Mawar IA</h5>
                </template>
                <div id="modal" class="d-block text-center">
                  <img src="~assets/img/cimahpar/pos-mawar-1a.png" alt="" />
                  <p class="text-center">Nama Posyandu : Mawar IA</p>
                  <p>
                    Strata : Posyandu Mandiri adalah Posyandu yang sudah dapat
                    melaksanakan kegiatan lebih dari 8 kali per tahun, dengan
                    rata-rata jumlah kader sebanyak lima orang atau lebih,
                    cakupan kelima kegiatan utamanya lebih dari 50%, mampu
                    menyelenggarakan program tambahan, serta telah memperoleh
                    sumber pembiayaan dari dana sehat yang dikelola oleh
                    masyarakat yang pesertanya lebih dari 50% KK yang bertempat
                    tinggal di wilayah kerja Posyandu. Intervensi yang dilakukan
                    bersifat pembinaan termasuk pembinaan program dana sehat,
                    sehingga terjamin kesinambungannya. Selain itu dapat
                    dilakukan intervensi memperbanyak macam program tambahan
                    sesuai dengan masalah dan kemampuan masing-masing
                  </p>
                  <p>
                    Lokasi : BELENTUK RT 01 RW 01 Kelurahan Cimahpar Kecamatan
                    Bogor Utara
                  </p>
                </div>
                <b-button
                  class="mt-3"
                  block
                  @click="$bvModal.hide('bv-modal-example')"
                  >Close</b-button
                >
              </b-modal>
              <!-- modal end -->
            </div>

            <div class="album">
              <div class="album-img">
                <a
                  ><img
                    src="~assets/img/cimahpar/pos-mawar-1b.png"
                    alt=""
                    id="show-btn"
                    @click="$bvModal.show('bv-modal-example-2')"
                /></a>
              </div>
              <div class="album-content">
                <h5>Mawar IB</h5>
              </div>
              <!-- modal -->
              <b-modal id="bv-modal-example-2" hide-footer>
                <template #modal-title>
                  <h5>Mawar IB</h5>
                </template>
                <div id="modal" class="d-block text-center">
                  <img src="~assets/img/cimahpar/pos-mawar-1b.png" alt="" />
                  <p class="text-center">Nama Posyandu : Mawar IB</p>
                  <p>
                    Strata : Posyandu Purnama adalah Posyandu yang sudah dapat
                    melaksanakan kegiatan lebih dari 8 kali per tahun, dengan
                    rata-rata jumlah kader sebanyak lima orang atau lebih,
                    cakupan kelima kegiatan utamanya lebih dari 50%, mampu
                    menyelenggarakan program tambahan, serta telah memperoleh
                    sumber pembiayaan dari dana sehat yang dikelola oleh
                    masyarakat yang pesertanya masih terbatas yakni kurang dari
                    50% KK di wilayah kerja Posyandu.
                  </p>
                  <p>
                    Lokasi : TAMAN KENARI RT 03 RW 01 Kelurahan Cimahpar
                    Kecamatan Bogor Utara
                  </p>
                </div>
                <b-button
                  class="mt-3"
                  block
                  @click="$bvModal.hide('bv-modal-example-2')"
                  >Close</b-button
                >
              </b-modal>
              <!-- modal end -->
            </div>

            <div class="album">
              <div class="album-img">
                <a
                  ><img
                    src="~assets/img/cimahpar/pos-mawar-3b.png"
                    alt=""
                    id="show-btn"
                    @click="$bvModal.show('bv-modal-example-3')"
                /></a>
              </div>
              <div class="album-content">
                <h5>Mawar IIIB</h5>
              </div>
              <!-- modal -->
              <b-modal id="bv-modal-example-3" hide-footer>
                <template #modal-title>
                  <h5>Mawar IIIB</h5>
                </template>
                <div id="modal" class="d-block text-center">
                  <img src="~assets/img/cimahpar/pos-mawar-3b.png" alt="" />
                  <p class="text-center">Nama Posyandu : Mawar IIIB</p>
                  <p>
                    Strata : Posyandu Purnama adalah Posyandu yang sudah dapat
                    melaksanakan kegiatan lebih dari 8 kali per tahun, dengan
                    rata-rata jumlah kader sebanyak lima orang atau lebih,
                    cakupan kelima kegiatan utamanya lebih dari 50%, mampu
                    menyelenggarakan program tambahan, serta telah memperoleh
                    sumber pembiayaan dari dana sehat yang dikelola oleh
                    masyarakat yang pesertanya masih terbatas yakni kurang dari
                    50% KK di wilayah kerja Posyandu.
                  </p>
                  <p>
                    Lokasi : CIMAHPAR RT 01 RT 03 Kelurahan Cimahpar Kecamatan
                    Bogor Utara
                  </p>
                </div>
                <b-button
                  class="mt-3"
                  block
                  @click="$bvModal.hide('bv-modal-example-3')"
                  >Close</b-button
                >
              </b-modal>
              <!-- modal end -->
            </div>

            <div class="album">
              <div class="album-img">
                <a
                  ><img
                    src="~assets/img/cimahpar/pos-mawar-4b.png"
                    alt=""
                    id="show-btn"
                    @click="$bvModal.show('bv-modal-example-4')"
                /></a>
              </div>
              <div class="album-content">
                <h5>Mawar IVB</h5>
              </div>
              <!-- modal -->
              <b-modal id="bv-modal-example-4" hide-footer>
                <template #modal-title>
                  <h5>Mawar IVB</h5>
                </template>
                <div id="modal" class="d-block text-center">
                  <img src="~assets/img/cimahpar/pos-mawar-4b.png" alt="" />
                  <p class="text-center">Nama Posyandu : Mawar IVB</p>
                  <p>
                    Strata : Posyandu Purnama adalah Posyandu yang sudah dapat
                    melaksanakan kegiatan lebih dari 8 kali per tahun, dengan
                    rata-rata jumlah kader sebanyak lima orang atau lebih,
                    cakupan kelima kegiatan utamanya lebih dari 50%, mampu
                    menyelenggarakan program tambahan, serta telah memperoleh
                    sumber pembiayaan dari dana sehat yang dikelola oleh
                    masyarakat yang pesertanya masih terbatas yakni kurang dari
                    50% KK di wilayah kerja Posyandu.
                  </p>
                  <p>
                    Lokasi : CIMAHPAR RT 01 RT 03 Kelurahan Cimahpar Kecamatan
                    Bogor Utara
                  </p>
                </div>
                <b-button
                  class="mt-3"
                  block
                  @click="$bvModal.hide('bv-modal-example-4')"
                  >Close</b-button
                >
              </b-modal>
              <!-- modal end -->
            </div>
          </div>
        </b-tab>

        <!-- kontak -->
        <b-tab title="Kontak">
          <div class="kontak">
            <h5>Kontak kami :</h5>
            <div class="kontak-content">
              <p>
                <span>Alamat : </span>Jl. Tumenggung Wiradireja No. 106 Bogor
                Utara
              </p>

              <p><span>No Telepon : </span> Telp. (0251)8651781</p>

              <p><span>Email: </span>kel.cimahpar@kotabogor.go.id</p>
            </div>
          </div>
        </b-tab>
      </b-tabs>
    </div>

    <!-- KELURAHAN END -->

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

/* PROFIL KEL */
.profil {
  display: flex;
  gap: 40px;
  justify-content: center;
  margin: 50px 30px 30px 30px;
}

.profil-lurah img {
  width: 400px;
  height: 450px;
}

.nm-lurah {
  padding: 10px;
  border: 1px solid black;
}

.profil-lurah p {
  font-weight: 400;
  width: 400px;
}

.profil-content p {
  font-weight: 400;
}

.profil-visi p span {
  font-weight: 600;
}

.p-misi {
  border-bottom: 1px solid black;
  margin-top: 3px;
}

/* ALL KELURAHAN*/
.galeri {
  margin: 50px 30px 50px 30px;
  font-weight: 600;
}

.galeri h2 {
  text-align: center;
  font-size: 23px;
  font-weight: 600;
  color: #3375cc;
  margin-top: 20px;
  margin-bottom: 30px;
}

.galeri h2 span {
  color: black;
  border-bottom: 2px solid #3375cc;
}

.galeri h3 {
  text-align: center;
  font-size: 20px;
  color: #3375cc;
  margin-top: 30px;
  margin-bottom: 20px;
}

/* POSYANDU STYLE */

.galeri-foto {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin-top: 50px;
}

.album {
  box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.356);
}

.album-img a img {
  width: 300px;
  height: 200px;
  cursor: pointer;
  /* transition: 0.3s; */
}

/* .album-img a img:hover {
    width: 325px;
    height: 225px;
  } */

.album-content {
  padding: 10px;
}

#modal p {
  text-align: start;
}

/* KONTAK STYLE */

.kontak {
  margin-top: 50px;
}

.kontak h5 {
  margin-bottom: 15px;
}

.kontak-content p {
  font-weight: 400;
}

.kontak-content p span {
  font-weight: 600;
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

  /* PROFIL KEL */
  .profil {
    flex-direction: column;
    margin: 10px 10px 10px 10px;
  }

  .profil-lurah img {
    width: 100%;
  }

  .profil-lurah p {
    width: 100%;
  }

  /* POSYANDU STYLE */
  .berita {
    width: 100%;
  }

  .galeri-foto {
    margin-top: 50px;
  }

  #modal img {
    width: 100%;
  }

  /* KONTAK */
  .kontak {
    margin-top: 30px;
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
      title: "Kelurahan Cimahpar | Kecamatan Bogor Utara",
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
