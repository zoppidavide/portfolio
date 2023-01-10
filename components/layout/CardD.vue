<template>
  <div class='projectcard'>
    <NuxtLink :to='to'>
      <div class='card-background'>
      </div>
      <b-row class='bio mx-1 my-2'>

        <b-col cols='12' md='10' class=''><h6 style='color: var(--color-secondary);'> {{ bio }} </h6></b-col>

      </b-row>
    </NuxtLink>
  </div>
</template>


<script>
export default {
  name: 'CardD',
  props: {
    title: String,
    thumbnail: String,
    bio: String,
    to: [String]
  }
}
</script>


<style>

h6 {
  color: white;
}

.projectcard {
  border-radius: 20px;
  overflow: hidden;
  width: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  margin-bottom: 32px;
}

.card-background {
  overflow: hidden;
  position: absolute;
  inset: 0;
}

img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.3s ease-in-out;
}

.card-background img:hover {
  transform: scale(1.04);
}

.card:hover img {
  transform: scale(1.04);
}

.bio {
  position: absolute;
  bottom: 0;
}

.bio h6 {
}

.card-small {
  height: 300px;
}

.card-medium {
  height: 400px;
}

.card-large {
  height: 500px;
}

@media (max-width: 768px) {
  .card-small {
    height: 300px;
  }

  .card-medium {
    height: 300px;
  }

  .card-large {
    height: 300px;
  }

  .projectcard {
    margin-bottom: 16px;
  }
}


</style>
