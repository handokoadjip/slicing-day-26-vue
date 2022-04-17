<template>
  <header class="mb-5">
    <nav class="navbar fixed-top bg-white navbar-light px-4">
      <div class="container-fluid px-0 d-flex justify-content-between">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <router-link class="navbar-brand text-center text-primary fs-2 mp-0 fw-bolder ls-5px" to="#">
          Nanimarquina
        </router-link>

        <div class="d-flex justify-content-center align-items-center d-none d-lg-block">
          <router-link class="text-decoration-none text-muted me-4" to="#"><i class="fas fa-heart"></i></router-link>
          <router-link class="text-decoration-none text-muted" to="#"><i class="fas fa-search"></i></router-link>
        </div>

        <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
          <ul class="navbar-nav text-uppercase">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-end text-lg-center fw-bold" aria-current="page" to="#">home
              </router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-end text-lg-center" to="#">pages</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-end text-lg-center" to="#">elements</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-end text-lg-center" to="#">blog</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-end text-lg-center" to="#">portofolio</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-end text-lg-center" to="#">shop</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

