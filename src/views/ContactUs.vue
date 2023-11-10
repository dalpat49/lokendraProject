<template>
     <section class="first_section">
        <div>
        <div class="paragraph">
          <div class="p-5" >
            <h2 class="pb-4 pt-5" >
              Contact
            </h2>
            <p>Amet luctus venenatis lectus magna fringilla urna porttitor rhoncus<br> dolor. 
               A lacus vestibulum sed arcu non. Dolor magna eget est lorem <br>ipsum dolor sit amet consectetur.
            </p>
            <button class="btn btn-primary mt-5 mb-2 px-4 py-2 rounded-0"><a>Read more</a> </button>
          </div>
        </div>
    </div>
      </section>
      
      <!-- Second Section -->
      <section class="second_section1 pt-5 pb-">
        <div class="container pt-2 pb-5" id="second_section_container">
          <div>
            <div class="second_section_h1 pt-2">
              <h1>Contact Us</h1>
            </div>
            <div  class="second_section_h4 pt-2 pb-2">
                <h4>Any questions or remarks? Just write us a message!</h4>
            </div>
          </div>
          <div  class="second_section_for_Email_name">
            <div class="second_section_for_Email">
              <p>Email</p>
                <input type="text" placeholder="Enter a valid email address" name="email">
            </div>
            <div class="second_section_for_name">
              <p>Name</p>
              <input type="text" placeholder="Enter Your Name" name="name">
            </div>
          </div>
          <div class="second_section_for_button mt-3 pb-3">
            <button class="btn btn-primary rounded-0 px-5 py-2">Submit</button>
          </div>
        </div>
      </section>


      <!-- detail Section -->
      <section class="detail_section pb-5">
        <div class="container mb-4" id="detail_section_container">
          <div class="row mx-5 " id="detail_section_row">
            <div class="col-lg-4 col-md-6 col-sm-12 col-xs-12 pb-5" id="detail_section_1st_col-lg">
              <div>
                <div class="card border-0 rounded-0" id="detail_section_1st_card">
                  <div class="detail_section_1st_card_img">
                  <img src="src/assets/running.png" style="width: 50px; height: 50px;"/>
                </div>
                  <div class="detail_section_1st_card_h5 pt-5">
                    <h5>About Club</h5>
                  </div>
                  <div class="detail_section_1st_card_p pt-1 pb-3">
                    <p>Running Guide<br>Workouts</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 col-xs-12 pb-5" id="detail_section_1st_col-lg">
              <div>
                <div class="card border-0 rounded-0" id="detail_section_1st_card">
                  <div class="detail_section_1st_card_img">
                  <img src="src/assets/call.png" style="width: 50px; height: 50px;"/>
                </div>
                  <div class="detail_section_1st_card_h5 pt-5">
                    <h5>Phone (Landline)</h5>
                  </div>
                  <div class="detail_section_1st_card_p pt-1 pb-3">
                    <p>+ 912 3 567 8987<br>+ 912 5 252 3336</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-4 col-md-6 col-sm-12 col-xs-12 " id="detail_section_1st_col-lg">
              <div>
                <div class="card border-0 rounded-0" id="detail_section_1st_card">
                  <div class="detail_section_1st_card_img">
                  <img src="src/assets/marker.png" style="width: 50px; height: 50px;"/>
                </div>
                  <div class="detail_section_1st_card_h5 pt-5">
                    <h5>Our Office Location</h5>
                  </div>
                  <div class="detail_section_1st_card_p pt-1 pb-3">
                    <p>The Interior Design Studio Company<br>The Courtyard, Al Quoz 1, Colorado, USA</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
</template>


<style scoped>

/* Detail Section */
.detail_section{
  background-color: #2590f4;
}
/* #detail_section_1st_card_img  img{
  background-color: #2590f4;
  padding: 1rem;
} */
.detail_section_1st_card_img img {
    padding: 5px;
}
div#detail_section_1st_col-lg {
    display: flow-root;
    justify-content: center;
}
div#detail_section_1st_card {
    text-align: center;
    margin-top: -4rem;
    margin-bottom: 2rem;
}
.detail_section_1st_card_h5 h5 {
    font-weight: 400;
    font-size: x-large;
}
.detail_section_1st_card_img {
    background: #2590f4;
    background-size: cover;
    width: fit-content;
    padding: 2.1rem;
    align-self: center;
    border-radius: 50%;
}
.detail_section_1st_card_p{
  font-size: 16px;
}


/* Second Section */
section.second_section1 {
    display: flex;
    position: relative;
    text-align: center;
    padding-bottom: 7rem !important;
}
.second_section_for_Email_name {
    display: flex;
    position: relative;
    justify-content: center;
    padding: 3px 0 8px 0;
}
.second_section_for_Email_name p {
    padding: 0 !important;
    margin-bottom: 0 !important;
    text-align: left;
}
.second_section_for_Email {
    padding: 0 2rem 3px 0px;
}
button.btn.btn-primary.rounded-0.px-5.py-2 {
    font-size: larger;
}
input[type="text"] {
    border: none;
    background: #f0f0f0d4;
    padding: 10px 15px 10px 15px;
    text-align: left;
    font-size: large;
    outline: none;
    margin: 0px 72px 0 0;
    width: 100%;
    font-family: system-ui;
}
::placeholder{
  color: rgb(106, 106, 106);
}
.second_section_h4.pt-2.pb-2 h4 {
    font-weight: 300;
    font-size: xx-large;
}

/* First section */
.first_section{
  background-image: linear-gradient(0deg, rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url("https://assets.nicepagecdn.com/11a8ddce/3667110/images/pexels-photo-1666667.png");
  background-position: 50% 50%;
  background-size: contain;
  min-height: 645px;
  background-size: cover;
  display: flex-root;
  text-align: -webkit-center;
}
.paragraph {
  width: fit-content;
  text-align: center;
  display: flex;
}
.paragraph div{
  border:15px solid #2590f4;
  padding: 40px 60px 40px 60px;
  margin-top: 80px;
  background-color: #f6f6f63d;
  
}
.paragraph h2{
  font-weight: 700;
  font-family: sans-serif !important;
  font-size: 3.3rem;
  color: white;
  line-height: 3.9rem;
}
.paragraph p{
  color: white;
  font-family: Montserrat, sans-serif !important;
  font-size: 1.150rem;
  margin-top: 5px;
}
button a{  
    color: white;
    padding: 8px 15px 8px 15px;

}





</style>