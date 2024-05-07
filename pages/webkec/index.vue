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
        <b-navbar-brand href="#"
          ><img src="~/assets/img/logobogut-03.png" alt=""
        /></b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-navbar-nav>
              <b-nav-item href="#" class="nav-p">Profil</b-nav-item>
              <b-nav-item href="#">Berita</b-nav-item>
              <b-nav-item href="#">Dokumen</b-nav-item>
              <b-nav-item href="#">Posyandu</b-nav-item>
              <b-nav-item href="#">Kontak</b-nav-item>
              <b-nav-item href="#">Galeri</b-nav-item>
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

    <!-- HEAD SECTION START -->
    <div class="hero">
      <div class="hero-img">
        <img
          src="~/assets/img/BG2-KECAMATAN-01.jpg"
          alt="img"
          style="width: 100%; margin-top: -100px; position: relative"
        />
        <div
          class="contain-2"
          style="position: absolute; top: 200px; left: 100px; z-index: 10"
        >
          <div class="contain-3" style="padding: 50px; border-radius: 30px">
            <h5>WEBSITE RESMI</h5>
            <h5 style="font-style: italic">PEMERINTAH KOTA BOGOR</h5>
            <h2 style="margin-top: 25px">KECAMATAN</h2>
            <h1 style="font-weight: bold; font-size: 50px">
              BOGOR <span style="color: #3575cc">UTARA</span>
            </h1>
            <button class="btn-hero" type="submit">Baca Selengkapnya</button>
          </div>
        </div>
      </div>
    </div>
    <!-- HEAD SECTION END -->

    <!-- SAMBUTAN CAMAT -->
    <div class="cam" style="margin: 120px 10px 100px 10px">
      <h2 class="text-center"><span>SAMBUTAN </span>CAMAT</h2>
      <div class="d-flex justify-content-center" style="margin-top: 50px">
        <div class="cam-img" style="margin-right: 30px">
          <img src="~/assets/img/camatbogut12.png" alt="camatbogut.jpg" />
          <div class="nama-cam" style="text-align: center">
            <h5>Camat Kec. Bogor Utara</h5>
            <p>Riki Robiansah, S.STP</p>
          </div>
        </div>
        <div class="cam-sam" style="width: 500px">
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
    <div class="kat-ber" style="text-align: center; padding: 15px">
      <h2>KATEGORI <span>BERITA</span></h2>
      <div
        class="kat-ber2 d-flex"
        style="justify-content: center; gap: 30px; margin-top: 20px"
      >
        <div><a href="#">BERITA TERBARU</a></div>
        <div><a href="#">BERITA WILAYAH</a></div>
        <div><a href="#">BERITA KOTA</a></div>
      </div>
      <div
        class="card-section d-flex"
        style="justify-content: center; gap: 30px"
      >
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
            BOGOR. Wali Kota Bogor, Bima Arya membuka secara resmi Musyawarah
            Rencana Pembangunan (Musrenbang) Kecamatan Bogor Utara......
          </p>

          <button>Baca Selengkapnya</button>
        </div>

        <div class="card-ber">
          <div class="card-ber-img">
            <img src="~/assets/img/berita3.png" alt="berita1.jpg" />
          </div>
          <p>22-10-2024</p>
          <h5 style="color: black"><a href="">Gelar operasi PA di...</a></h5>
          <p>
            Operasi pasar dilakukan Kecamatan Bogor Utara, Kota Bogor pada hari
            Jumat (14/01/2022). Operasi pasar tersebut dilakukan di halaman
            Kantor Kec......
          </p>

          <button>Baca Selengkapnya</button>
        </div>
      </div>
    </div>
    <!-- BERITA END  -->

    <!-- OUR AGENDA -->

    <div class="keg">
      <h2><span>AGENDA</span> KEGIATAN</h2>
      <div class="keg-agn-1">
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
      </div>
    </div>

    <!-- OUR AGENDA END -->

    <!-- LAIN-LAIN -->
    <div class="lokban">
      <h2>LOKASI & <span>BANNER</span></h2>
      <div>
        <div></div>
      </div>
    </div>
    <!-- LAIN-LAIN END -->

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

.nav-p:hover {
  color: #3375cc;
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

/* CAMAT  */

.cam h2 {
  font-weight: bold;
  color: #3375cc;
}

.cam h2 span {
  border-bottom: 2px solid #3375cc;
  color: black;
}

.nama-cam {
  border: 0.5px solid black;
  padding: 10px 10px 1px 10px;
}

.nama-cam p {
  margin-bottom: 10px;
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

.kat-ber2 a {
  color: black;
  font-size: 15px;
  font-weight: 400;
  margin-top: 50px;
}

.kat-ber2 a:hover {
  color: #3375cc;
  font-weight: bold;
  border-bottom: 2px solid #3375cc;
  padding: 10px;
}

.kat-ber2 a.active {
  color: #47b2e4c4;
}

.card-ber {
  width: 250px;
  padding: 15px;
  box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.356);
  border-radius: 20px;
  background-color: white;
  margin-top: 35px;
  margin-bottom: 50px;
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
  height: 160px;
}

/* AGENDA */

.keg h2 {
  color: #3375cc;
  font-weight: bold;
  text-align: center;
  margin: 80px 1px 80px 1px;
}

.keg h2 span {
  color: black;
  border-bottom: 2px solid #3375cc;
}

.keg-agn-1 {
  display: flex;
  justify-content: start;
}

.calender {
  margin-left: 230px;
  /* margin: auto; */
  display: flex;
  justify-content: end;
}

.calender .cal-1 {
  background-color: rgb(201, 201, 201);
  /* background-color: #3375cc; */
  /* background-color: #0d1f38; */
  border: 1.5px solid #0d1f38;
  border-radius: 10px;
  padding: 30px;
}

/* .calender .cal-2 {
  background-color: white;
} */

.keg-agn-2 {
  width: 500px;
  height: 400px;
  margin-top: 20px;
  margin-left: -300px;
  margin: auto;
  padding: 150px 50px 50px 50px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: start;
  overflow: scroll;
  border-bottom: 1px dotted black;
}

.keg-h4 {
  margin-top: 40px;
}

.keg-p {
  border-bottom: 1px dotted black;
  padding: 0px 0px 10px 0px;
}

/* LOKASI AND BANNER */
.lokban {
  text-align: center;
  margin-top: 150px;
}

.lokban h2 {
  color: #3375cc;
}

.lokban h2 span {
  color: black;
  border-bottom: 2px solid #3375cc;
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
}
</style>

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

  async asyncData({ $axios }) {
    //fetching posts
    const posts = await $axios.$get("/api/web/postHomepage");

    //fetching categories
    const categories = await $axios.$get("/api/web/categorySidebar");

    //fetching tags
    const tags = await $axios.$get("/api/web/tags");

    return {
      posts: posts.data,
      categories: categories.data,
      tags: tags.data,
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
