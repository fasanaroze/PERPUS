<template>
  <h2 class="text-center">Isi Buku Kunjungan</h2>
  <br />
  <div class="row mb-3">
    <label for="inputEmail3" class="col-sm-2 col-form-label">Nama</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="inputEmail3" />
    </div>
  </div>
  <div class="row mb-3">
    <label for="inputPassword3" class="col-sm-2 col-form-label">Kategori</label>
    <select class="form-select" id="specificSizeSelect">
      <option value="Siswa">Siswa</option>
      <option value="Guru">Guru</option>
      <option value="Staf">Staf</option>
    </select>
    <div class="col-sm-10">
      <input type="password" class="form-control" id="inputPassword3" />
    </div>
  </div>
  <div class="row mb-3">
    <label for="inputEmail3" class="col-sm-2 col-form-label">Keperluan</label>
    <div class="col-sm-10">
      <input type="email" class="form-control" id="inputEmail3" />
    </div>
  </div>
  <button type="submit" class="btn btn-primary">SUBMIT</button>
</template>
