<template>
  <div>
    <div class="page-header clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image: url('img/s1.jpg')"
      >
      </parallax>
      <div class="container">
        <div class="photo-container">
          <img src="img/salma4.png" alt="" />
        </div>
        <h3 class="title">Salma Ramadhiany</h3>
        <p class="category">Programmer</p>
        <div class="content">
          <div class="social-description">
            <h2>6</h2>
            <p>Project</p>
          </div>
          <div class="social-description">
            <h2>3 year</h2>
            <p>Experience</p>
          </div>
          <div class="social-description">
            <h2>1</h2>
            <p>Company</p>
          </div>
        </div>
      </div>
    </div>
    <div class="section">
      <div class="container">
        <h3 class="title">About me</h3>
        <h5 class="description">
          IT professional with over 3 year of experience web developer for
          startup. Develop project concepts and maintain optimal workflow
        </h5>
      </div>
    </div>
    <div class="container">
      <h3 class="title">EXPERTISE</h3>
      <div class="col-md-12">
        <n-progress type="info" :value="90" label="PHP" show-value>
        </n-progress>
        <n-progress type="success" :value="95" label="Laravel" show-value>
        </n-progress>
        <n-progress type="primary" :value="75" label="Node JS" show-value>
        </n-progress>
        <n-progress type="warning" :value="80" label="Vue JS" show-value>
        </n-progress>
        <n-progress type="primary" :value="80" label="Strapi" show-value>
        </n-progress>
        <n-progress type="warning" :value="80" label="HTML" show-value>
        </n-progress>
        <n-progress type="info" :value="75" label="CSS" show-value>
        </n-progress>
        <n-progress type="success" :value="80" label="JS" show-value>
        </n-progress>
        <n-progress type="primary" :value="80" label="Postgre SQL" show-value>
        </n-progress>
        <n-progress type="warning" :value="80" label="Mysql" show-value>
        </n-progress>
      </div>
    </div>

    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">Work Experience</h2>
          </div>
        </div>
        <div class="separator separator-primary"></div>
        <div class="section-story-overview">
          <div class="row">
            <div class="col-md-6">
              <div
                class="image-container image-left"
                style="background-image: url('img/fivecode3.jpeg')"
              >
                <!-- First image on the left side -->
                <!--<p class="blockquote blockquote-primary">
                  "Over the span of the satellite record, Arctic sea ice has
                  been declining significantly, while sea ice in the
                  Antarctichas increased very slightly"
                  <br />
                  <br />
                  <small>-NOAA</small>
                </p>-->
              </div>
            </div>
            <div class="col-md-5">
              <!-- First image on the right side, above the article -->
              <div
                class="image-container image-right"
                style="background-image: url('img/fivecode1.jpeg')"
              ></div>
              <h3>PT Lima Kode Teknologi</h3>
              <p>
                working as a web programmer, from 2019 until now. Using php,
                laravel, jquery, CSS, lumen, JS, mysql, POSTGRE SQL, vue JS &
                node JS
              </p>
              <p>
                Work with teams to build projects. Develop project concepts and
                maintain an optimal workflow. Develop frontend and backend
                systems. Maintain database and collaborate with team using
                gitlab
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="container text-center">
      <h3 class="title my-5">Porfolio</h3>
      <div class="row">
        <div class="col-md-6">
          <router-link to="/landing" target="_blank">
            <img src="img/km.png" alt="Image" class="img-raised" />
          </router-link>
          <router-link
            to="/landing"
            class="btn btn-simple btn-primary btn-round"
            >View Page
          </router-link>
        </div>
        <div class="col-md-6">
          <router-link to="/profile" target="_blank">
            <img src="img/eg.png" alt="Image" class="img-raised" />
          </router-link>
          <router-link
            to="/profile"
            class="btn btn-simple btn-primary btn-round"
            >View Page</router-link
          >
        </div>
        <div class="col-md-6">
          <router-link to="/profile" target="_blank">
            <img src="img/m1.png" alt="Image" class="img-raised" />
          </router-link>
          <router-link
            to="/profile"
            class="btn btn-simple btn-primary btn-round"
            >View Page</router-link
          >
        </div>
        <div class="col-md-6">
          <router-link to="/profile" target="_blank">
            <img src="img/edu2.png" alt="Image" class="img-raised" />
          </router-link>
          <router-link
            to="/profile"
            class="btn btn-simple btn-primary btn-round"
            >View Page</router-link
          >
        </div>
        <div class="col-md-6">
          <router-link to="/profile" target="_blank">
            <img src="img/dress.png" alt="Image" class="img-raised" />
          </router-link>
          <router-link
            to="/profile"
            class="btn btn-simple btn-primary btn-round"
            >View Page</router-link
          >
        </div>
        <div class="col-md-6">
          <router-link to="/profile" target="_blank">
            <img src="img/shamo3.png" alt="Image" class="img-raised" />
          </router-link>
          <router-link
            to="/profile"
            class="btn btn-simple btn-primary btn-round"
            >View Page</router-link
          >
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Tabs, TabPane, Progress } from "@/components";

export default {
  components: {
    [Progress.name]: Progress,
  },
  name: "profile",
  bodyClass: "profile-page",
  data() {
    return {
      pagination: {
        simple: 1,
        default: 2,
        full: 3,
      },
    };
  },
};
</script>
<style></style>
