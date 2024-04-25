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
            <h2 style="margin-top: 20px">KECAMATAN</h2>
            <h1 style="font-weight: bold">
              BOGOR <span style="color: #47b2e4">UTARA</span>
            </h1>
            <button type="submit">Selengkapnya</button>
          </div>
        </div>
      </div>
    </div>

    <!-- <div class="contain" style="position: relative">
      <div class="contain-2" style="position: absolute; top: 20px">
        <p>lorem ipsusdjsadks</p>
      </div>
    </div> -->
    <!-- HEAD SECTION END -->
    <div>
      <img src="" alt="" />
    </div>
  </div>
</template>

<style>
body {
  font-family: "Roboto", sans-serif;
}

navbar {
  color: black;
  background-color: transparent;
}

.contain-3 {
  background-color: rgba(255, 255, 255, 0.751);
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
};
</script>
