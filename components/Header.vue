<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="~/assets/img/Logo.png" alt="Logo" width="65" height="57" class="d-inline-block align-text-bootom">
        SMKN 4 TASIKMALAYA
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="/">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Profile
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="profile/">sejarah</a></li>
              <li><a class="dropdown-item" href="visi">visi & misi</a></li>
              <li><a class="dropdown-item" href="#">struktur organisasi</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="eskul/">Ekstrakulikuler</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Galeri</a>
          </li>

        </ul>
      </div>
    </div>
  </nav>

</template>
<style>
.collapse {
  padding-left: 68%;
}
</style>
