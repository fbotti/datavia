<template>
  <section id="background">
    <div class="box-3">
      <img
        class="box-icon-cam"
        src="~assets/datavia-assets/datavia-assets/icons/icon-camera-setup.svg"
      />
      <h2 class="text-white ml-2">Camera Management</h2>
    </div>

    <!-- ////////////////////////icono home///////////////// -->
    <div class="container row ">
      <nuxt-link to="/">
        <div class="icon-menu">
          <div class="logo">
            <img
              src="~assets/datavia-assets/datavia-assets/icons/icon-home.svg"
              alt=""
            />
            <small>MENU</small>
          </div>
        </div>
      </nuxt-link>

      <!-- COLUMNA 1 -->
      <div class="columna1 col col-lg-6  h-100 w-100">
        <div class="column-title w-75">
          <img
              src="~assets/datavia-assets/datavia-assets/icons/icon-plus.svg"
              alt=""
            />
          <h2 class="text-white mt-1">Adding a New Camera</h2>
        </div>

        <nuxt-link to="/camera-A1">
          <input type="text" class="camera-name form-control mt-3 w-75 p-2 " placeholder="Camera Name">
        </nuxt-link>
        <div class="rowSelect row w-100">
          <input type="select" class="select1 form-control bg-dark mt-3 col-4 p-2 " placeholder="Select Camera Brand">
          <input type="select" class="select2 form-control bg-dark mt-3 col-4 p-2" placeholder="Select Camera Model">
        </div>

        <div class="columnaBox w-75 h-25 mt-5">
          <img
        class="box-icon-cam"
        src="~assets/datavia-assets/datavia-assets/icons/icon-camera.svg"
      />
        </div>

        <input type="textarea" placeholder="Description" class="columnaBox2 form-control  bg-dark w-75 h-25 mt-3">
      </div>

      <!-- COLUMNA 2 -->

      <div class="columna2 col col-lg-6  h-100 w-100">
        <div class="column-title w-75">
          <img
                src="~assets/datavia-assets/datavia-assets/icons/icon-preview.svg"
                alt=""
              />

           <h2 class="text-white mt-1">Camera Model Preview</h2>
        </div>

      <input type="text" class="form-control mt-3 w-75 p-2 bg-dark" placeholder="URL">

      <div class="columnaBox3 w-75 mt-5">
        <img
        class="box-icon-cam"
        src="~assets/datavia-assets/datavia-assets/icons/icon-camera.svg"
      />
      </div>
      </div>

    </div>

  </section>
</template>

<script>
export default {};
</script>

<style scoped>
* {
  /* background: #191a1d; */
  /* height: 100vh; */
  margin: 0px;
  padding: 0px;
}

a{
    width: 100%;
    text-align: -webkit-center;
}

.camera-name{
  background: #212529;
  transition: all 200ms;
}

.camera-name:hover{
  background: #408388;


}

.container[data-v-48ca2ab2] {
    width: 80%;
    height: 630px;
    margin: 0 auto;
    background-size: 100%;
    background-position: center center;
    background-size: cover;
    position: absolute;
    top: 140px;
    left: 142px;
    max-width: 1407px;
    display: -webkit-box;
    display: flex;
    -webkit-box-align: center;
    align-items: center;
    -webkit-box-pack: center;
    justify-content: center;

}

.form-control{
  border-color: rgb(100, 100, 100);
  cursor: pointer;
}

.form-control:focus {
  border-color: #85b0cb;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 8px #85b0cb;
}

.form-control:hover {

}

#background {
  background: #191a1d;
  height: 48em;
}


.column-title {
    display: flex;
    /* align-items: center; */
    justify-content: center;
    align-content: center;
}

.column-title img{
    width: 28px;
    position: absolute;
    left: 82px;
    top: 4px;
}

.icon-menu {
    padding: 0;
    cursor: pointer;
    background: #85b0cb;
    border-radius: 7px;
    position: absolute;
    width: 37px;
    top: -86px;
    left: 0px;
    -webkit-transition: all 200ms;
    transition: all 200ms;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 38px;
}



.icon-menu small{
  display: none;
  color: #fafafa;
    position: absolute;
    top: 12px;
    left: 60px;
}

.icon-menu:hover {
  background: #fafafa
}

.icon-menu:hover .logo{
  background: #fafafa
}

.icon-menu:hover small{
  display: block;
}

.logo {
  width: 28px;
  height: 26px;
  margin: 10px;
  cursor: pointer;
  background: #85b0cb;
  position: static;
  transition: all 200ms;
}


.box-3 {
    display: -webkit-box;
    display: flex;
    -webkit-box-align: baseline;
    align-items: baseline;
    width: 285px;
    height: 135px;
    top: 35px;
    left: 639px;
    position: absolute;
}

.box-3 .box-icon-cam {
    width: 21%;
    position: absolute;
    top: -10px;
    left: -65px;
}

.box-3 h3 {
  align-self: end;
  color: #ccc;
  position: absolute;
  left: 75px;
  top: 11px;
  font-size: 16px;
}

.columna1{
    display: flex;
    align-items: center;
    justify-content: end;
    flex-flow: column wrap;
}

.columna2{
  display: flex;
    align-items: center;
    justify-content: end;
    flex-flow: column wrap;
}

.rowSelect{
    display: inline-flex;
    justify-content: space-around;
}
.select1 {
    position: absolute;
    top: 92px;
    left: 74px;
}
.select2{
      position: absolute;
      top: 92px;
      left: 323px;
}

.columnaBox {
    display: flex;
    align-items: center;
    justify-content: center;
    align-self: initial;
    position: absolute;
    top: 126px;
    cursor: pointer;
    border: solid #85b0cb;
    border-radius: 10px;

}

.columnaBox2 {
    position: absolute;
    top: 336px;
}

.columnaBox3{
    display: flex;
    align-items: center;
    justify-content: center;
    align-self: initial;
    position: absolute;
    top: 126px;
    height: 337px;
    border: solid #85b0cb;
    border-radius: 10px;
    cursor: pointer;
}
</style>
