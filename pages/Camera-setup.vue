<template>
  <div>
    <!--Header-->
    <div class="header pt-5 pb-7">
      <div class="m-0">
        <div class="header-body">
          <section class="py-6 pb-9">
            <div class="row m-3 justify-content-center text-center mt-2">
              <!-- //////////////////TITULOS con GIT FINAL//////////////////// -->
              <div class="camera-title col-lg-9">
                <!-- <div>
                  <h1
                    class="titulo-camera display-4 mb-0 text-danger"
                    data-aos="fade-left"
                    data-aos-duration="1500"
                  >
                    CAMERA SETUP
                  </h1>
                </div> -->
              </div>
              <div class="col-lg-12 mt-5">
                <netflix />
              </div>
            </div>
          </section>
        </div>
      </div>

      <!-- /////////////////SEPARADOR ///////////////////////-->
      <div class="separator separator-bottom separator-skew zindex-100">
        <svg
          x="0"
          y="0"
          viewBox="0 0 2560 100"
          preserveAspectRatio="none"
          version="1.1"
          xmlns="http://www.w3.org/2000/svg"
        >
          <polygon
            class="fill-default"
            points="2560 0 2560 100 0 100"
          ></polygon>
        </svg>
      </div>
    </div>

    <!-- SECCION 2 -->
  </div>
</template>

<script>
import Netflix from "../pages/Netflix.vue";
import AOS from "aos";
export default {
  components: { Netflix },
  layout: "AuthLayout",
  mounted() {
    AOS.init();
  },
};
</script>




<style scoped>
.camera-title {
  position: absolute;
  left: 170px;
  margin-bottom: 20px;
  margin-top: 20px;
  top: 64px;
}

.camera-column {
  height: 550px;
  margin-top: 250px;
}

.camera-column2 {
  height: 550px;
  margin-top: 250px;
}
</style>
