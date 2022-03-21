<template>
  <div>
    <!-- Navbar-->
    <nav class="navbar navbar-expand-lg navbar-light nav-bg">
      <div class="container-fluid">
        <h4 class="mx-2 p-4 nav-title">Vaccination</h4>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
          <div class="navbar-nav d-flex flex-row align-items-center">
            <a class="nav-link p-2 mx-4" aria-current="page" href="#">Database</a>
            <a class="nav-link p-2 mx-4" href="#">Education</a>
            <a class="nav-link p-2 mx-4" href="#">News</a>
            <a class="nav-link p-2 mx-4" href="#">Regulation</a>
            <div class="mx-4">
                <button class="button-vac shadow p-3 px-4">Hoax Buster</button>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Nav",
};
</script>

<style>
.nav-title {
  color: #2747c5;
  font-size: 2.5em;
}

.nav-link {
  font-size: 1.2em;
  color: #6d7b93;
}

</style>