<template>
  <div class='row row-navbar justify-content-between align-items-center mx-3'>
    <div class='col-6'>
      <b-link to="index">
        <button class="btn btn-primary-about">Hi! I'm Davide</button>
      </b-link>
    </div>
    <div class='col-6 d-flex justify-content-end' >
      <b-link to="about">
        <button class="btn btn-outline-about" >About me</button>
      </b-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavbarAbout'
}
</script>

<style>

.btn-primary-about {
  color: white;
  width: 170px;
  background-color: black;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
  border: 2px solid #000000;
}

.btn-primary-about:hover {
  color: white;
  opacity: 80%;
  width: 170px;
  background-color: black;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
}

.btn-outline-about {
  width: 120px;
  border: 2px solid #000000;
  color: #000000;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
}

</style>
