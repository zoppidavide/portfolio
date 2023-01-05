<template>
  <div class='row row-navbar justify-content-between align-items-center mx-3'>
    <div class='col-6'>
      <button class="btn btn-primary">Davide Zoppi</button>
    </div>
    <div class='col-6 d-flex justify-content-end' >
      <button class="btn btn-outline-primary">About me</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style>

.btn-primary {
  width: 145px;
  background-color: black;
  border-radius: 30px;
  border-style: none;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
}

.btn-primary:hover {
  opacity: 80%;
  width: 145px;
  background-color: black;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
}

.btn-outline-primary {
  width: 125px;
  opacity: 50%;
  border: 1px solid #000000;
  color: #000000;
  border-radius: 30px;
  text-decoration-color: black;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
}

</style>
