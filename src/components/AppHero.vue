<script>
export default {
  data() {
    return {
      image: 'https://i.pinimg.com/originals/76/ce/2c/76ce2c04b1f919061605f884b9250cec.jpg'
    }
  }
}
</script>

<template>
  <section>
    <img :src="image" alt="">
    <div>
      <h2>JUMBOTRON EXAMPLE</h2>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Illum consequuntur numquam impedit aspernatur dolor qui commodi amet modi nulla tenetur, obcaecati beatae, sequi nesciunt, voluptatibus voluptatem error accusamus? Quidem, corporis.</p>
      <button>more info</button>
    </div>
  </section>
</template>

<style scoped>
section {
  max-width: 1600px;
  height: 400px;
  margin: auto;
}

div {
  position: relative;
  bottom: 80%;
  left: 8%;
  color: aliceblue;
  width: 40%;
}
img {
  width: 100%;
  object-fit: cover;
  height: 100%;
}
button {
  background-color: transparent;
  color: aliceblue;
  border: 2px solid aliceblue;
  padding: 5px 10px;
}
</style>