<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <div class="icon mt-4">
          <nuxt-link to="/buku/rekomen">
            <svg xmlns="http://www.w3.org/2000/svg" width="57" height="40" fill="currentColor" class="bi bi-arrow-left-square-fill text-white" viewBox="0 0 16 16">
              <path d="M16 14a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2zm-4.5-6.5H5.707l2.147-2.146a.5.5 0 1 0-.708-.708l-3 3a.5.5 0 0 0 0 .708l3 3a.5.5 0 0 0 .708-.708L5.707 8.5H11.5a.5.5 0 0 0 0-1" />
            </svg>
          </nuxt-link>
          <h2 class="text-center my-4">HAM (Hak Asasi Manusia)</h2>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-4 text-white d-flex flex-column justify-content-center">
        <h4>Detail Buku:</h4>
        <h5>Pengarang: H. Sabaruddin Tain</h5>
        <h5>Jumlah Halaman: 127</h5>
        <h5>Tahun Terbit: 2008</h5>
        <h5>Penerbit: Anak Saleh Pratama</h5>
        <h5>Rak: 127</h5>
      </div>
      <div class="col-4 d-flex flex-column justify-content-center align-items-center">
        <div class="mb-5">
          <div class="card-body">
            <img src="~/assets/img/komHam.jpg" class="img-thumbnail" />
          </div>
        </div>
      </div>
      <div class="col-4 d-flex flex-column justify-content-center align-items-center">
        <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Meminjam</button>
        <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Membaca Buku</button>
        <button type="button" class="btn btn-lg text-white mb-4" style="background-color: #123577; width: 200px">Mengembalikan</button>
      </div>
    </div>

    <div class="row text-white">
      <div class="col">
        <h4>Deskripsi:</h4>
        <h5>
          Buku ini bukanlah berisi panduan akhlak (budi pekerti) untuk anak-anak. Melainkan sebuah upaya percobaan untuk mengenalkan nilai-nilai dasar budi pekerti melalui bahasa gambar yang kami pilih, yakni komik. Itulah misi utama penulisan buku
          komik ini.
        </h5>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-fluid {
  background-color: #4377de;
}
h2 {
  color: #fff;
}
</style>
