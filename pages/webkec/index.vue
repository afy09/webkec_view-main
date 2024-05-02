<template>
  <div style="background-color: white">
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;1,100;1,300;1,400;1,500;1,700&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="~/assets/css/webkec.css" />
    <!-- NAVBAR SATART -->

    <div id="navbar" style="position: fixed; width: 100%; z-index: 10">
      <b-navbar
        class="bg-transparant"
        style="padding: 10px 20px 10px 20px; color: blue"
      >
        <div>
          <img src="~/assets/img/logobogut-03.png" />
        </div>
        <b-navbar-brand href="#"></b-navbar-brand>
        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-navbar-nav>
              <b-nav-item href="#">Profil</b-nav-item>
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
              BOGOR <span style="color: #47b2e4">UTARA</span>
            </h1>
            <button class="btn-hero" type="submit">Baca Selengkapnya</button>
          </div>
        </div>
      </div>
    </div>
    <!-- HEAD SECTION END -->

    <!-- SAMBUTAN CAMAT -->
    <div class="cam" style="margin: 120px 10px 50px 10px">
      <h2 class="text-center">
        SAMBUTAN <span style="color: #47b2e4">CAMAT</span>
      </h2>
      <div class="d-flex justify-content-center" style="margin-top: 50px">
        <div class="cam-img" style="margin-right: 30px">
          <img />
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
      <h2><span style="color: #47b2e4">KATEGORI </span>BERITA</h2>
      <div
        class="kat-ber2 d-flex"
        style="justify-content: center; gap: 30px; margin-top: 20px"
      >
        <div><a href="#">BERITA TERBARU</a></div>
        <div><a href="#">BERITA WILAYAH</a></div>
        <div><a href="#">BERITA KOTA</a></div>
      </div>

      <div class="card-ber">
        <div class="card-ber-img">
          <img src="~/assets/img/berita1.png" alt="berita1.jpg" />
        </div>
        <p>22-10-2024</p>
        <h5>Bangkitkan UMKM</h5>
        <p>
          Camat Bogor Utara, Riki Robiansah meminta seluruh lurah dan bawahannya
          yang bertugas di Kecamatan Bogor Utara, Kota Bogor untuk memakai
          produk lokal setiap hari Selasa.
        </p>

        <button>Baca Selengkapnya</button>
      </div>
    </div>
    <!-- BERITA END  -->

    <div>
      <img src="" alt="" />
    </div>
  </div>
</template>

<!--------- ALL STYLE ------------->

<style>
body {
  font-family: "Roboto", sans-serif;
}

navbar {
  color: black;
  background-color: transparent;
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
  background-color: #47b2e4c4;
  color: white;
  font-size: 15px;
  transition: 500ms;
  border-style: none;
}

/* CAMAT  */

.nama-cam {
  border: 1px solid black;
  padding: 10px;
}

/* BERITA */

.kat-ber {
  background-color: rgba(242, 240, 240, 0.929);
  padding: 20px;
  padding-top: -30px;
}

.kat-ber2 a {
  color: black;
  font-size: 15px;
  font-weight: 400;
  margin-top: 50px;
}

.kat-ber2 a:hover {
  background-color: #47b2e4c4;
  padding: 10px;
}

.kat-ber2 a:active {
  color: #47b2e4c4;
}

.card-ber {
  width: 300px;
  padding: 20px;
  border: 1px solid black;
  border-radius: 20px;
  background-color: white;
  margin: 30px;
}

.card-ber p {
  font-size: 12px;
}

.card-ber button {
  border-style: none;
  padding: 10px;
  border-radius: 50px;
  color: white;
  background-color: #47b2e4c4;
}

.card-ber-img img {
  width: 200px;
  height: 250px;
}

/* .nama-cam h5 {
  background-color: rgb(180, 176, 176);
} */
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
};
</script>
