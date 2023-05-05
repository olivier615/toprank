<template>
    <header class="fixed-top">
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark text-light">
          <div class="container-fluid">
            <a class="navbar-brand d-flex" href="#">
              <img class="me-3 logoSize" alt="Vue logo" src="../../assets/logo.png">
              <h1>Kaya Bet</h1>
            </a>  
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0 fs-4 bg-dark">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">kota hiburan</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                     tip taruhan
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <li><a class="dropdown-item" href="#">bakarat</a></li>
                    <li><a class="dropdown-item" href="#">Analisis keberuntungan</a></li>
                    <li><a class="dropdown-item" href="#">selamat hari amerika</a></li>
                    <li><a class="dropdown-item" href="#">Catur</a></li>
                    <li><a class="dropdown-item" href="#">Slot</a></li>
                    <li><a class="dropdown-item" href="#">penangkapan ikan</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">anggota terdaftar</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">main sekarang</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
    </header>
</template>

<style lang="scss">
.logoSize {
  width: 48px;
  height: 48px;
}
</style>