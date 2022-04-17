<template>
  <footer>
    <div class="container-fluid">
      <div class="row align-items-center h-vh-50 p-5">
        <div class="col-lg-4">
          <div class="wrapper">
            <div
              class="copyright d-block d-lg-flex justify-content-lg-between align-items-lg-center text-center mb-3 mb-lg-0">
              <p class="mp-0 fs-5 text-black">
                Lorem ipsum dolor
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="wrapper d-flex justify-content-center mb-3 mb-lg-0">
            <router-link class="navbar-brand text-center text-black fs-2 mp-0 fw-bolder ls-5px" to="#">
              Nanimarquina
            </router-link>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="d-flex justify-content-center align-items-center">
            <router-link class="text-decoration-none mx-2 circle-icon" to="#"><i class="fab fa-instagram"></i>
            </router-link>
            <router-link class="text-decoration-none mx-2 circle-icon" to="#"><i class="fab fa-twitter"></i>
            </router-link>
            <router-link class="text-decoration-none mx-2 circle-icon" to="#"><i class="fab fa-facebook-f"></i>
            </router-link>
            <router-link class="text-decoration-none mx-2 circle-icon" to="#"><i class="fab fa-pinterest"></i>
            </router-link>
          </div>
        </div>
      </div>

      <div class="row align-items-center pb-5">
        <div class="col-lg-12 d-flex justify-content-center">
          <div class="wrapper">
            <ul class="text-uppercase d-inline mp-0">
              <li class="d-inline">
                <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">lorem
                </router-link>
              </li>
              <li class="d-inline">
                <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">ipsum
                </router-link>
              </li>
              <li class="d-inline">
                <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">dolor
                </router-link>
              </li>
              <li class="d-inline">
                <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">sit
                </router-link>
              </li>
              <li class="d-inline">
                <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">amet
                </router-link>
              </li>
            </ul>
          </div>
        </div>
      </div>

      <div class="row align-items-center bg-copy py-4 px-2 shadow-top">
        <div class="col-lg-12 d-flex justify-content-center">
          <div class="wrapper">
            <p class="m-0 text-fade-3 text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Est.</p>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>