<template>
  <div class="container-fluid">
    <div class="row my-5">
      <div class="col-lg-6">
        <nuxt-link to="/pengunjung/tambah">
          <div class="card bg-pengunjung rounded-5">
            <div class="card-body">
              <h2>pengunjung</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
      <div class="col-lg-6">
        <nuxt-link to="/buku">
          <div class="card bg-buku rounded-5">
            <div class="card-body">
              <h2>Cari Buku</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
    </div>
  </div>
  <h1 class="statistik">STATISTIK</h1>

  <div class="container-fluid">
    <div class="row my-5">
      <div class="col-lg-6">
        <nuxt-link to="/pengunjung">
          <div class="card bg-warning rounded-5">
            <div class="card-body">
              <h4 class="jumlah"> 3 Pengunjung</h4>
            </div>
          </div>
        </nuxt-link>
      </div>

      <div class="col-lg-6">
        <nuxt-link to="/buku">
          <div class="card bg-success rounded-5">
            <div class="card-body">
              <h5 class="buku">180 Buku</h5>
            </div>
          </div>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  height: 250px;
  box-shadow: 1px 1px 10px #424242;
}
.card.bg-pengunjung {
  margin-top: 5%;
  background-image: url('../assets/img/bg-home-kunjungan.jpeg');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 90%;
}
.card.bg-buku {
  margin-top: 5%;
  background: url('../assets/img/bg-home-cari-buku.jpg');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  opacity: 90%;
}
h2{
  color:black;
  font: arial;
  
}
h1{
  color: white;
}
.card.bg-warning {
  margin-top: 3%;
}
.card.bg-success {
  margin-top: 3%;
}
.statistik {
  color: black;
  margin-left: 50px;
}
h5{
  text-align: center;
  margin-top: 80px;
  font-size: 300%;
  color: black;
}
h4{
  text-align: center;
  margin-top: 80px;
  font-size: 300%;
  color: black;
}
</style>