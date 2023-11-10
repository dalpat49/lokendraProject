<!-- eslint-disable vue/multi-word-component-names -->
<template>
<header>
    <div>
       <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/Project">Product</RouterLink>
        <RouterLink to="/Service">Service</RouterLink>
        <RouterLink to="/ContactUs">Contact Us</RouterLink>
      </nav>  
    </div>
  </header>
<RouterView/> 



<!-- new Section -->  
<section class="new_section mt-5 py-5 ">
  <div class="container py-5" id="new_section_container">
    <div class="card mb-4 mt-4 py-4 border-0 rounded-0" style="max-width: 1000px;"  id="new_section_card">
    <div class="row" id="new_section_row">
      <div class="col-lg-4 col-md-4" id="new_section_col_lg_1st">
        <div class="new_section_col_lg_2nd_image mx-4 mt-5">
        <img src="src/assets/phone_call.png" style="width: 50px; height: 50px;"/>
      </div>
        <div class="new_section_col_lg_1st_image mx-4 mt-4">
        <img  src="src/assets/mimi.jpg" style="width: 250px; height: 250px;"/>
      </div>
      
    </div>
      <div class="col-lg-8 col-md-8" id="new_section_col_lg_2nd">
        <div class="card-body">
          <h5 class="card-title mt-4 px-2">We realize that you lead a busy life, so we have made it
easy for you to drop off your vehicle 24/7.</h5>
          <p class="card-text mt-4 mx-2">image from <strong>Freepik</strong></p>
          <div class="pt-3" id="phone_no" >
                <i class="bi bi-telephone-fill"></i>
                <h1 class="mx-3" >+1 (234) 567-8910</h1>
              </div>
        </div>
      </div>
    </div>
  </div>
</div>
</section>

<footer class="footer footer_class pb-4">
  <div class="container px-5" >
      <div class="row" >
        <div class="col-lg-4 col-md-4 col-sm-6 col-xs-12 mt-4">
            <div>
              <h5>About Us</h5>
            </div>
            <div class="pt-4 " > 
              <h6>Microprixs Solution Pvt.Ltd</h6>
            </div>
            <div class="pt-2">
              <p>
                T 3006 - 3007  3rd Floor ,Orbit Mall , <br>Near Civil Lines Metro Station,<br>Jaipur,Rajasthan 302020
              </p>
            </div>
            <div>
              <a>support@microprixs.com </a>
            </div>
        </div>
        <div class="col-lg-4 col-md-4 col-sm-6 col-xs-12 mt-4">
            <div>
              <h5 class="px-3" >Quick Link</h5>
            </div>
            <div class="pt-3 px-1" >
              <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/Project">Product</a></li>
                <li><a href="/Service">Service</a></li>
                <li><a href="/ContactUs">Contact Us</a></li>
              </ul>
            </div>
        </div>
        <div class="col-lg-4 col-md-4 col-sm-6 col-xs-12 mt-4">
            <div>
              <h5>More Information</h5>
            </div>
            <div class="pt-4 " > 
              <h6>Microprixs Solution Pvt.Ltd</h6>
            </div>
            <div class="pt-2 px-1">
              <p>
                +91 9982499155 , +91 8696434457
              </p>
            </div>
            <div>
              <a>Lokendrasingh07773@gmail.com</a>
            </div>
            <div class="footer_icons mt-3" >
              <div>
                <img src="src/assets/instagram.png"/>
              </div>
              <div>
                <img src="src/assets/linkedin.png"/>
              </div>
              <div>
                <img src="src/assets/facebook.png"/>
              </div>
            </div>
        </div>
      </div>
  </div>
</footer>

</template>

<style scoped>
@media (max-width: 976px){
  .card {
    display: flex;
    text-align-last: center;
    text-align: center;
}
  #row_wise{
    padding: 0% !important;
  }
}




/* new Section */
.new_section{
  background-color: #f2f2f2;
}
div#new_section_container {
    justify-content: center;
    display: flex;
}
.new_section_col_lg_1st_image img {
    border-radius: 50%;
}
.new_section_col_lg_2nd_image {
    display: flex;
    position: absolute;
    background: #2590f4;
    padding: 8px;
    border-radius: 50%;
}
div#new_section_col_lg_1st {
    display: flow;
    position: relative;
}
h5.card-title {
    font-size: 28px;
    font-weight: normal;
}
i.bi.bi-telephone-fill {
    color: #2590f4;
}
p.card-text.mt-4 strong {
    color: #2590f4;
}
p.card-text.mt-4 {
    font-size: x-large;
}




header {
  max-height: 100vh;
  background-color: #f3f3f3;
}
nav {
    width: 100%;
    text-align: left;
    margin-right: 2rem;
    font-size: 1rem;
    padding: 1.2rem 0;
    text-align: center;
}

nav a.router-link-exact-active {
  color: rgb(0, 0, 0);
}


nav a {
  display: inline-block;
  padding: 0 1rem;
  list-style-type: none;
  color: rgb(134, 134, 134);
  text-decoration-line: none;
  font-weight: 600;
    font-size: 16px;
}
nav a:hover{
color: rgb(0, 108, 232);
}

nav a:first-of-type {
  border: 0;
}
.footer_class{
  background-color: #333333;
  color: white;
  width: 100%;
}
.col-lg-4.col-md-4.col-sm-6.col-xs-12.mt-4 a {
  text-decoration: none;
  color: white;
  }
.col-lg-4.col-md-4.col-sm-6.col-xs-12.mt-4 li{
  list-style-type: none;
  line-height: 2rem;
}
.footer_icons{
  display: flex;
}
.footer_icons img{
  width: 40px;
  height: 40px;
  margin-left: 7px;
}







#phone_no{
  display: flex;
  position: relative;
}
#phone_no i{
  font-size: xx-large;
}
.text_section9.pt-4 p {
    font-size: larger;
}
.text_section9.pt-4 h5 {
  font-size: 28px;
  font-weight: 400 !important;
}
.text_section9.pt-4 i{
  color: #2590f4;
}
.text_section9 {
    display: flow;
    position: relative;
    align-self: center;
    text-align: left;
    margin-left: 17rem;
}
#container_section9{
   justify-content: center;
   
}
.card.content.mt-2 {
    display: flex;
    position: relative;
    padding: 13px 0px 36px 22px !important;
    margin: 5rem 8rem 0 7rem !important;
    border: none;
    border-radius: none;
}
.section_9{
  background-color: #f2f2f2;
  height: 450px;
  display: flex;
  position:relative;
  justify-content: center;
}
.images_section8 {
    display: flex;
    position: absolute;
}
.image1 img {
    background-color: #2590f4;
    border-radius: 50%;
    margin: 40px 0px 0px 44px;
    padding: 13px;
}
.image1 {
    display: flex;
    position: absolute;
}
.image2 img{
  border-radius: 50%;
  margin: 34px 0 0 47px;
}




</style>
