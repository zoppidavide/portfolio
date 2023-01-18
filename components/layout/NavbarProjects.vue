<template>
  <div class='row row-navbar-proj justify-content-between align-items-center mx-1 mx-lg-3'>
    <div class='col-6'>
      <b-link to="/">
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
  color: #ECE7E3;
  width: 120px;
  background-color: black;
  border-radius: 30px;
  font-family: 'Lato', sans-serif;
  font-weight: 700;
  font-size: 16px;
  border: 2px solid #000000;
}

.btn-primary:hover {
  color: black;
  background-color: #ECE7E3;
  border: 2px solid #000000;
}

.btn-outline-primary {
  width: 170px;
  border: 2px solid #000000;
  color: #000000;
  border-radius: 30px;
  font-family: 'Lato', sans-serif;
  font-weight: 700;
  font-size: 16px;
}

.btn-outline-primary:hover {
  background-color: black;
  width: 170px;
  border: 2px solid #000000;
  color: #ECE7E3;
}

</style>
