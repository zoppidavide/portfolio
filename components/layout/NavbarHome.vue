<template>
  <div class='row row-navbar justify-content-between align-items-center mx-3'>
    <div class='col-6'>
      <b-link to="index">
<!--        <button class="btn btn-outline-primary">Davide Zoppi</button>-->
        <b-button variant="outline-primary">Hi! I'm Davide</b-button>
      </b-link>
    </div>
    <div class='col-6 d-flex justify-content-end' >
      <b-link to="about">
        <b-button class='btn-primary'>About me</b-button>
<!--        <button class="btn btn-primary" >About me</button>-->
      </b-link>
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
  width: 120px;
  background-color: black;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
  border: 2px solid #000000;
}

.btn-primary:hover {
  opacity: 80%;
  width: 120px;
  background-color: black;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
}

.btn-outline-primary {
  width: 170px;
  border: 2px solid #000000;
  color: #000000;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
}

</style>
