<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
        <nuxt-link to="../"><button type="submit" class="btn btn-lg rounded-5 px-5 bg-success text-white" style="float: right; margin-bottom: 15px;">KEMBALI</button></nuxt-link>
        <div class="my-3">
          <input type="search" class="form-control from-control-lg rounded-5" placeholder="Filter...">
        </div>
        <div clas="my-3 text-muted">menampilkan 1 dari 1</div>
        <table class="table">
          <thead>
            <tr>
              <td>No</td>
              <td>NAMA</td>
              <td>KEANGGOTAAN</td>
              <td>WAKTU</td>
              <td>KEPERLUAN</td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1.</td>
              <td>Seli</td>
              <td>Siswa</td>
              <td>26 februari 2024, 23.31.00</td>
              <td>Baca</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

