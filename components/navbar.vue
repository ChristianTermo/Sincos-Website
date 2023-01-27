<template>
  <div>
     <b-navbar class="nav fixed-top" toggleable="lg" type="light" variant="light" fi>
      <a href="#Descrizione"><img src="~/static/assets/sincoslogoblueNOscritte.png" /> </a>
 
       <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
 
       <b-collapse id="nav-collapse" is-nav>
 
         <!-- Right aligned nav items -->
         <b-navbar-nav class="ml-auto">
           <b-nav-item right href="#Aboutus" >Chi siamo</b-nav-item>
           <b-nav-item right href="#Solution"> Soluzioni e Partner</b-nav-item>
           <b-nav-item right href="#Contatti">Contatti</b-nav-item>
           <b-nav-item right href="#">Lavora con noi</b-nav-item>
 
           <b-nav-item-dropdown text="Lang" right>
             <b-dropdown-item href="#">EN</b-dropdown-item>
           </b-nav-item-dropdown>
 
         </b-navbar-nav>
       </b-collapse>
     </b-navbar>
   </div>
 </template>
 
 <script>
 
 </script>
 