<template>
  <div class='row row-navbar justify-content-between align-items-center mx-lg-3 mx-sm-1'>
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
  border: 1px solid #000000;
}

.btn-primary:hover {
  color: black;
  width: 120px;
  background-color: white;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
  border: 1px solid #000000;
}

.btn-outline-primary {
  opacity: 50%;
  width: 170px;
  border: 1px solid #000000;
  color: #000000;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
}

.btn-outline-primary:hover {
  background-color: black;
  width: 170px;
  border: 1px solid #000000;
  color: white;
  border-radius: 30px;
  font-family: 'AkkuratLL-Bold';
  font-size: 16px;
}

</style>
