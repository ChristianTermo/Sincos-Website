<template>
  <section id="Descrizione" class="hero" >
       <div class="hero-inner">
            <h1>&#10092;Sistemi Informativi
              <br>
              Consulenza e Software&#10093;
            </h1>

           <div>
              <p class="aftertitle" >Servizi per aree di mercato della mobilità, trasporti e infrastrutture,
              con particolare riferimento al settore ferroviario e all&#39;ERTMS
              Web Expert System per la diagnostica e la manutenzione apparati</p>
            </div>
            <p id="freccia">
              &#8681;
           </p>
       </div>
   </section>

</template>


<style>

@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:ital@1&display=swap');



.hero h1 {
    /* Text styles */
    font-size: 430%;
    font-family: 'Roboto Mono', monospace;
  text-decoration: none;
}

#freccia{
  color:white;
  font-size: 300%;
  width: 100%;
}

.aftertitle{
  color:white;
  width: 75%;
  padding-left: 25%;
}

.hero {
   /* Sizing */
   height: 100vh;
   
   /* Flexbox tuff */
   display: flex;
   justify-content: center;
   align-items: center;
   
   /* Text styles */
   text-align: center;
   
   /* Background styles */
   background-image: url(~/static/assets/opening8a.jpg);
   background-size: cover;
   background-position: center center;
   background-repeat: no-repeat;
   background-attachment: fixed;
}
.hero-inner {
  width: 90%;
  margin-top: 11%;
}

@media (max-width: 480px) {
  .hero h1 {
    /* Text styles */
    font-size: 330%;

}
    }
    @media (max-width: 370px) {
.hero h1 {
    
    font-size: 270%;

}
    }
</style>