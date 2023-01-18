<template>
  <div class='row row-navbar justify-content-between align-items-center mx-1 mx-lg-3'>
    <div class='col-6'>
      <b-link to="/">
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
  color: #ECE7E3;
  width: 170px;
  background-color: black;
  border-radius: 30px;
  font-family: 'Lato', sans-serif;
  font-weight: 700;
  font-size: 16px;
  border: 2px solid #000000;
}

.btn-primary-about:hover {
  color: black;
  background-color: #ECE7E3;
  border: 2px solid #000000;
}

.btn-outline-about {
  width: 120px;
  border: 2px solid #000000;
  color: black;
  border-radius: 30px;
  font-family: 'Lato', sans-serif;
  font-weight: 700;
  font-size: 16px;
}

.btn-outline-about:hover {
  border: 2px solid black;
  background-color: black;
  color: #ECE7E3;
}

</style>
