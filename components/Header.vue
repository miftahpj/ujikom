<template>
    <div class="head p-3">
        <div class="title">
            <img src="/assets/logo-smkn4.png" alt="logo">
            <h2 class="ps-2">SMKN 4 Tasikmalaya</h2>
        </div>
        <div class="info ms-5 ps-5">
          <p>alamat <ion-icon name="location-sharp"></ion-icon></p>
            <span>Sukamenak,Purbaratu,Tasikmalaya</span>
              
        </div>
    </div>



    <ul class="nav justify-content-center sticky-top bg-white bg-opacity-75">
        <nav class="navbar navbar-expand-lg">
  <div class="container-fluid">
    <a class="navbar-brand fw-bold" href="/">Beranda</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle fw-bold" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Profil
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="/profil/sejarah">Sejarah</a></li>
            <li><a class="dropdown-item" href="/profil/vm">Visi Misi</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="/profil/ds">Data Statistic</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle fw-bold" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Estrakurikuler
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="/eskul/ol">Olahraga</a></li>
            <li><a class="dropdown-item" href="/eskul/nl">Non Olahraga</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle fw-bold" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Gallery
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="/kurikulum/jw">Pembelajaran</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">jadwal</a></li>
          </ul>
        </li>
        <!-- <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Siswa
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Sejarah</a></li>
            <li><a class="dropdown-item" href="#">Visi Misi</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li> -->
        <!-- <li class="nav-item">
          <a class="nav-link" href="/artikel">artikel</a>
        </li> -->
      </ul>
      

    </div>
  </div>
</nav>
    </ul>
    
<div class="garis"></div>
</template>
<style>

/* From Uiverse.io by vinodjangid07 */ 

.garis{
    border-bottom: 1px solid #ccc;
}
.head{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: nowrap;
    border-bottom: 1px solid #ccc;
}
.title{
    display: flex;
    align-items: center;

}
.title h2{
    font-size: 29px;
}
.title img{
    height: 60px;
}
.info{
    font-size: 24px;
    color: #000000;
    margin-left: 80px;
    
}
.info span{
    font-size: 19px;
    display: block;
    color: rgb(79, 79, 79);
}

@media (max-width: 768px) {
    .info {
        display: none;   
    }
    .cardh{
      display: none;
    }
}
</style>