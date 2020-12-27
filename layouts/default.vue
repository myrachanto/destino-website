<template>
  <div>
    <navbar />
    <Nuxt />
    <Foot />
  </div>
</template>
<script>
import Foot from '../components/footer.vue'
import Navbar from '../components/Navbar.vue'
export default {
  components:{
    Navbar,
    Foot
  }
}
</script>
<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'EB Garamond', serif;
  /* font-size: 2rem; */
}
/* h1 {
  font-size: 7rem;
}

h1 {
  font-size: 5rem;
} */
html{
  font-size: 62.5%;
  /* font-size: 2rem; */
}

.headers h1{
  font-size: 4rem;
  padding: 2px;
  color:rgb(15, 15, 14);
}
h2{
  font-size: 3rem;
  padding: 2px;
  color:rgb(66, 179, 56);
}
h3{
  font-size: 2.5rem;
  padding: 2px;
  color:rgb(66, 179, 56);
}

h4{
  font-size: 2rem;
  padding: 2px;
  color:rgb(66, 179, 56);
}
ul li{

  font-size: 2rem;
}
p{
  font-size: 2rem;
  padding: 10px;
}
.btn{
  font-size: 2rem;
  color: aliceblue;
  background: rgb(66, 179, 56);
  display: inline-block;
  padding: 10px 30px;
  margin-top: 20px;
  text-transform: uppercase;
  text-decoration: none;
  letter-spacing: 2px;
  transition: 0.5s ease;
}
.btn:hover{
  letter-spacing: 5px;
}
.about {
  display: flex;
  grid-template-columns:1fr 2fr;
}
.cont {
  max-width: 100vw;
  /* margin: 10px; */
  padding: 20px;
  overflow: hidden;
  padding: 4rem 1rem;
}

.grid-3 {
  display: grid;
  grid-gap: 20px;
  grid-template-columns: repeat(3, 1fr);
  flex-wrap: wrap;
}

.grid-2 {
  display: grid;
  grid-gap: 20px;
  grid-template-columns: repeat(2, 1fr);
}

.bg-dark {
  background: #333;
  color: #f4f4f4;
}

footer {
  text-align: center;
  padding: 2.2rem;
}

footer p {
  margin: 0;
}

@media (max-width: 560px) {
  .showcase::after {
    height: 50vh;
  }

  .content {
    top: 5%;
    margin-top: 5px;
  }

  .content .logo {
    height: 140px;
    width: 140px;
  }

  .content .text {
    display: none;
  }

  .grid-3,
  .grid-2 {
    grid-template-columns: 1fr;
  }
}


</style>
