<template>
<title>Beranda</title>
<div class="parallax">
    <div class="position-absolute top-50 start-50 translate-middle mt-5 pt-5">
      <h1>
        <div class="p-3 mb-2 bg-white text-dark bg-opacity-25 fw-bold display-5 row text-center text-md-center ">
              Selamat Datang Di Website Resmi SMKN 4 Tasikmalaya
        </div>
      </h1>
    </div>
</div>
 

<!-- BERITA -->
<div class="container mt-4 mb-4">
   <div class="row">
        <div class="col-lg-8">
            <div id="carouselExampleDark" class="carousel carousel-dark slide ">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
                </div>
  <div class="carousel-inner">
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="/assets/1.jpg" class="d-block w-100 h-50 rounded" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>First slide label</h5>
        <p>Some representative placeholder content for the first slide.</p>
      </div>
    </div>
    <div class="carousel-item" data-bs-interval="2000">
      <img src="/assets/1.jpg" class="d-block w-100 h-50 rounded" alt="...">
      <div class="carousel-caption d-none d-md-block">
        <h5>Second slide label</h5>
        <p>Some representative placeholder content for the second slide.</p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
    </div>
    </div>
    <div class="col-lg-4">

        <h1>BERITA</h1>
        <p class="placeholder-glow" style="width: 25%;">
        <span class="placeholder col-12 placeholder-xs"></span>
        </p>
        <h3>PPDB</h3>
        <h6>infomasi PPDB jawa Barat SMKN 4 Tasikmalaya tahun ajaran 2022/2023</h6>

        <button class="btn btn-secondary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasScrolling" aria-controls="offcanvasScrolling">Tekan untuk info lebih lanjut</button>
        <div class="offcanvas offcanvas-start" data-bs-scroll="true" data-bs-backdrop="false" tabindex="-1" id="offcanvasScrolling" aria-labelledby="offcanvasScrollingLabel">
            <div class="offcanvas-header">
                <h5 class="offcanvas-title" id="offcanvasScrollingLabel">PPDB SMKN 4 Tasikmalaya</h5>
                <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
                <p>Try scrolling the rest of the page to see this option in action.</p>
            </div>
        </div>

        <h3 class="pt-2">Kunjungan Industri</h3>
        <h6>infomasi PPDB jawa Barat SMKN 4 Tasikmalaya tahun ajaran 2022/2023</h6>
        <button class="btn btn-secondary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight">Tekan untuk info lebih lanjut</button>

<div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
  <div class="offcanvas-header">
    <h5 class="offcanvas-title" id="offcanvasRightLabel">Offcanvas right</h5>
    <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
  </div>
  <div class="offcanvas-body">
    ...
  </div>
</div>

    </div>
  </div>
</div>

<div class="parallax2">

<div class="container pt-5">
    <div class="text-center">
    <img src="/assets/kepalasekolah.png" class="rounded-5" alt="" width="200">
    <h1 class="display-4 fw-bold text-dark">Kurniawan</h1>
    <p class="fw-bold">kepala sekolah SMKN 4 Tasikmalaya</p>
  </div>
  </div>
</div>




<div class="container p-1 bg-light-subtle">
  <div class="row">
    <div class="text-center">
    <h2 class="p-3 mb-2 bg-light-subtle text-light-emphasis">Data Statistic</h2>
  </div>
  <div class="row">
    <div class="col-lg-6">
      <div class="text-md-center bg-secondary-subtle p-5 mt-5 rounded">
        <h2>Jumlah guru {{ jguru }}</h2>
      </div>
    </div>
    <div class="col-lg-6">
      <div class="text-md-center bg-secondary-subtle p-5 mt-5 rounded">
        <h2>Jumlah siswa {{ jmurid }}</h2>
      </div>
    </div>

  </div>
 
    <div class="col-lg-6 p-5">
      <h3 class="text-center pb-3">Jumlah Siswa Tiap Jurusan</h3>
      <ChartJurusan />
    </div>
    <div class="col-lg-6 p-5">
      <h3 class="text-center pb-3">Jumlah Siswa Tiap Angkatan</h3>
      <ChartAngkatan />
    </div>
    <div class="">
  <div class="text-center">
    <h2 class="p-3 mb-2 bg-light-subtle text-light-emphasis">Seragam Praktik</h2>
  </div>
  <div class="container text-center ps-5 me-5">
  <div class="row justify-content-center">
    <div class="col-md-4 mb-4">
      <div class="card1" style="width: 80%; height: auto;">
        <img src="/assets/Jurusan/pplg.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">PPLG</h5>
              <p class="card-text">Perkembangan Perangkat Lunak & Gim.</p>
          </div>
      </div>      
    </div>
    <div class="col-md-4 mb-4">
      <div class="card1" style="width: 80%; height: auto;">
        <img src="/assets/Jurusan/tjkt.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">TJKT</h5>
              <p class="card-text">Teknik Jaringan Dan Telekomunikasi.</p>
          </div>
      </div>
    </div>
    <div class="col-md-4 mb-4">
      <div class="card1" style="width: 80% ; height: auto;">
        <img src="/assets/Jurusan/tbsm.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">TBSM</h5>
              <p class="card-text">Teknik Bisnis Dan Sepeda Motor.</p>
          </div>
        </div>
    </div>
    <div class="col-md-4 mb-4">
      <div class="card1" style="width: 80%; height: auto;">
        <img src="/assets/Jurusan/dkv.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Dkv</h5>
              <p class="card-text">Deasin Kommonikasi Visual.</p>
          </div>
      </div>
    </div>
    <div class="col-md-4 mb-4">
      <div class="card1" style="width: 80%; height: auto;">
        <img src="/assets/Jurusan/toi.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">TOI</h5>
              <p class="card-text">teknik Otomasi Industri.</p>
          </div>
      </div>
    </div>

  </div>
</div>
</div>
  </div>
</div>



</template>
<style>

/* From Uiverse.io by JoanMarcc */ 
.card1 {
  margin-left: 20px;
  margin-top: 5%;
  width: 250px;

  height: 325px;
  background: white;
  border-radius: 20px;
  box-shadow: -8px 8px 0px 5px rgb(50, 50, 50, 0.2);
  border: solid 2px white;
  overflow: hidden;
  position: relative;
  transition: all 0.5s ease;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  transform: rotate(3deg) skewX(3deg);
}


.card1:hover {
  transform: translateY(-5%);
  box-shadow: 0px 20px 10px rgb(50, 50, 50, 0.2);
}


.parallax {

  background-image: url('/assets/home.jpg');

  height: 80vh;
  width: 100%;

  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.parallax2{
  background-image: url('/assets/homekepsek.jpg');

height: 60vh;
width: 100%;

background-attachment: fixed;
background-position: center;
background-repeat: no-repeat;
background-size: cover;
}
</style>
<script>

export default{
  name:"jumlah",
  data: function() {
    return {
      jguru: '100',
      jmurid: '1,620',
    }
  }
}


// const dataJSON = { "guru": 25, "siswa": 50 };

// // Update elements after they are created
// document.getElementById('jguru').innerText = `guru: ${dataJSON.guru}`;
// document.getElementById('jmurid').innerText = `siswa: ${dataJSON.siswa}`;
</script>