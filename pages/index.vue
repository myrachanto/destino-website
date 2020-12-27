<template>
  <div class="container">
    <div class="main">
      <div class="headers" >
         <h1 >Shopping for a new website?</h1><br>
      <button class="btn">You are in the right place</button>
      </div>
    </div>
    
     <!-- About -->
  <section class="about bg-light">
    <div class="cont">
          <h2><strong>So!</strong>   ...Are you looking for a website?</h2>
      <div class="grid-2">
        <div class="center"> <img src="~assets/interior_desing_template_two.jpg" alt="interior design template" style="width:100%">
        </div>
        <div>
         <p>
      It is overwhelming especially if it is your first time researching and intending to own a website. The stuff they all talk about like web design or responsive, SEO- did I lose you? </p>
      <p>
No pressure here! You are in good hands, all you have to do is to let us know what you want in a website like <i> “I need a personal website, with 5 pages, can be viewed on a tablet or mobile”</i> you know stuff like that. Things that you understand but if you are up to it on design part maybe responsive web design templates might be of help. All you need to do is explore those website designs and they might help you with coming up with a design for your website that’s if you have no dream website design. Are you new to this stuff then this form will guide you, fill it!.<p>
  <p>
So are you ready to get your website done? I know am ready for you and thanks for your time here.

      </p>
        </div>
      </div>
    </div>
  </section>

 <!-- Services -->
  <section class="services">
    <div class="container grid-3 center">
      <div>
         <div class="card">
        <h2><b>Web desing</b></h2>         
      <img src="~assets/catering.jpg" alt="Catering website design" style="width:100%">
      <div class="cont">
        <p>responsive web designs is the core principle in our web development and as such bring about maximum user satisfaction</p>
      </div>
    </div> 
      </div>
      <div>
       <div class="card">
        <h2><b>Web Development</b></h2>         
      <img src="~assets/interior_design_template.jpg" alt="interior design" style="width:100%">
      <div class="cont">
        <p>As far as e commerce is concerned seo, efficiency, effectiveness are the keys to successful online business venture thus our web deisgn and development is founded to be resourceful in SEO, Social site interlink, easy share of contents among others</p>
      </div>
    </div> 
      </div>
      <div>
        <div class="card">
        <h2><b>Content Management (cms)</b></h2>         
      <img src="~assets/interior_desing_template_two.jpg" alt="interior design template" style="width:100%">
      <div class="cont">
        <p>Our web designs are built to bring control to our clients even with little or no programming skills. One, with the use of content management software(c.m.s) one can customize their websites towards their tastes and preferences.</p>
      </div>
    </div> 
      </div>
    </div>
  </section>



  </div>
</template>

<script>
export default {

    head: {
    title: 'Best responsive website design and web application development firm',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'Chantosweb developers responsive website design and web application development firm'
      }
    ],
  }
}
</script>

<style>
.container {
  /* margin: 20 auto;
  padding: 20px; */
 /* min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center; */
}
.main {
   background-image: url("~assets/web_development.jpg");
  background-repeat: no-repeat;
  background-attachment: fixed;
  max-height: 90vh;
  background:linear-gradient(0deg, rgba(105,105,105, 0.8),  rgba(105,105,105, 0.8)), url("~assets/web_development.jpg");
  background-size:cover;
  background-position: center;
  display: flex;
  grid-template-columns:1fr 2fr;
  display: flex;
  flex-wrap: wrap;
  /* margin-to: 20px; */
}
.content{
  font-size: 2rem;
  padding: 20px;
  box-shadow: 0 8px 6px 1px black;
}
.p{
  margin: 10px;
  padding: 10px;
}

.fr-1 {
   background:	rgb(128, 128, 128,0.8);
   border-radius: 10px;
}

.fr-2 {
  background:rgba(105,105,105, 0.2);
}
.any {
  min-width: 50vw;
}
.headers{
  position: relative;
  width: 100vw;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.center {
  text-align: center;
  margin: auto;
}

.bg-light {
  background: #f4f4f4;
  color: #333;
}

/* Small Screens */
@media (max-width: 560px) {
  .showcase::after {
    height: 50vh;
  }
  .main {
    height: 50vh;
  }

.headers{
  position: relative;
  width: 100vw;
  min-height: 40vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
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

/* Landscape */
@media (max-height: 500px) {
  .content .title,
  .content .text {
    display: none;
  }

  .content {
    top: 0;
  }
}

</style>
