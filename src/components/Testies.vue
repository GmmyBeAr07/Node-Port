<template>

    <section id="Testies" style="min-height: 87.2vh; justify-content: center; flex-direction: column; display: flex;">

     
      <h2>Testimonial</h2>

      
      <!-- <div class="cardBox"> 
        <div class="card">
          <div class="front"> 
            <h3>Wandelene Maronicia Josop</h3>
            <p> </p> 
            <strong>&#x21bb;</strong>
          </div>

          <div class="back">
            <h3>Thoughts</h3>
            <p>Daniel is a humbled and trusted person, he looks out for everyone's best interest dispite everyone pushing him away. </p> 
          
          <img src="../assets/images/Testies/wandelene.jpg" alt="Avatar" style="width:300px;height:300px;">
          </div>
        </div>
      </div>
      <div class="cardBox">
        <div class="card">
          <div class="front">
            <h3>Sergio Rodgers</h3>
            <p> </p>
            <strong>&#x21bb;</strong>
          </div>
          <div class="back">
            <h3>Thoughts</h3>
            <p>Daniel, dispite being silly his a funny guy, never serious unless its needed so the times is always vibrant. His a man of principle and morals.</p> 
          
          <img src="../assets/images/Testies/sergio.jpg" alt="Avatar" style="width:300px;height:300px;">
          </div>
        </div>
      </div>

      <div class="cardBox">
        <div class="card">
          <div class="front">
            <h3>Uchenna Steven Innocent</h3>
            <p> </p>
            <strong>&#x21bb;</strong>
          </div>

          <div class="back">
            <h3>Thoughts</h3>
            <p>Daniel brings a vibe to the areas he enters and tries to help those who needs it, his a kind hearted guy. He works well in a team and has a friendly personality.</p>
          <img src="../assets/images/Testies/ui.jpg" alt="Avatar" style="width:300px;height:300px;">
          </div>
        </div>
      </div>

      <div class="cardBox">
        <div class="card">
          <div class="front">
            <h3>Mr. Godwin</h3>
            <p> </p>
            <strong>&#x21bb;</strong>
          </div>

        <div class="back">
        <h3>Thoughts</h3>
        <p>Daniel Bowers is a spirited young man. He works hard to achieve his goals and takes initiative.</p>
        <img src="../assets/images/Testies/godwin.png" alt="Avatar" style="width:300px;height:300px;">
        </div>
      </div>
    </div>
    </section> -->

<div class="row" style="margin: auto">
    <div class="col-3">
      <figure class="snip1192">
  <blockquote>Daniel brings a vibe to the areas he enters and tries to help those who needs it, his a kind hearted guy. He works well in a team and has a friendly personality.</blockquote>
  <div class="author">
    <img src="../assets/images/Testies/cha-had.png" alt="Avatar" style="width:150px;height:150px;">
    <h5>Chad Liam Hendricks<span>Student / Acquaintance</span>
      </h5>
    </div>
  </figure>
</div>

    <div class="col-3">
      <figure class="snip1192 hover">
  <blockquote>Daniel is a humbled and trusted person, he looks out for everyone's best interest dispite everyone pushing him away.</blockquote>
  <div class="author">
    <img src="../assets/images/Testies/wandelene.jpg" alt="Avatar" style="width:150px;height:150px;">
    <h5>Wandelene Maronicia Josop<span>Acquaintance</span></h5>
  </div>
</figure>
    </div>

    <div class="col-3">
      <figure class="snip1192 hover">
  <blockquote>Thank you. before I begin, I'd like everyone to notice that my report is in a professional, clear plastic binder...When a report looks this good, you know it'll get an A. That's a tip kids. Write it down.</blockquote>
  <div class="author">
   <img src="../assets/images/Testies/sergio.jpg" alt="Avatar" style="width:150px;height:150px;">
    <h5>Sergio Marco Rodgers<span>Student / Acquaintance</span></h5>
  </div>
</figure>
    </div>

    <div class="col-3">
      <figure class="snip1192">
  <blockquote>Daniel Bowers is a spirited young man. He works hard to achieve his goals and takes initiative.</blockquote>
  <div class="author">
    <img src="../assets/images/Testies/godwin.png" alt="Avatar" style="width:150px;height:150px;">
    <h5>Godwin Dzvapatsva<span>Lecturer</span></h5>
      </div>
    </figure>
  </div>  
</div>
    </section>
  </template>

<script>
export default {

}
</script>

<style scoped>
#Testies {
    background:linear-gradient(0deg, rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('../assets/images/blur3.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed; 
    backface-visibility:visible;
    background-size: 100% 100%;
  }

@import url(https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css);
@import url(https://fonts.googleapis.com/css?family=Raleway:400,800);
figure.snip1192 {
  font-family: 'Raleway', Arial, sans-serif;
  position: relative;
  float: left;
  overflow: hidden;
  margin: 10px 1%;
  min-width: 220px;
  max-width: 310px;
  width: 100%;
  color: #333;
  text-align: left;
  box-shadow: none !important;
}
figure.snip1192 * {
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}
figure.snip1192 img {
  max-width: 100%;
  height: 100px;
  width: 100px;
  border-radius: 50%;
  margin-bottom: 15px;
  display: inline-block;
  z-index: 1;
  position: relative;
}
figure.snip1192 blockquote {
  margin: 0;
  display: block;
  border-radius: 8px;
  position: relative;
  background-color: #fafafa;
  padding: 30px 50px 65px 50px;
  font-size: 0.8em;
  font-weight: 500;
  margin: 0 0 -50px;
  line-height: 1.6em;
  box-shadow: 0 0 5px rgba(0, 0, 0, 0.15);
}
figure.snip1192 blockquote:before,
figure.snip1192 blockquote:after {
  font-family: 'FontAwesome';
  content: "\201C";
  position: absolute;
  font-size: 50px;
  opacity: 0.3;
  font-style: normal;
}
figure.snip1192 blockquote:before {
  top: 35px;
  left: 20px;
}
figure.snip1192 blockquote:after {
  content: "\201D";
  right: 20px;
  bottom: 35px;
}
figure.snip1192 .author {
  margin: 0;
  text-transform: uppercase;
  text-align: center;
  color: #ffffff;
}
figure.snip1192 .author h5 {
  opacity: 0.8;
  margin: 0;
  font-weight: 800;
}
figure.snip1192 .author h5 span {
  font-weight: 400;
  text-transform: none;
  display: block;
}
/* Demo purposes only */
body {
  background-color: #212121;
}

</style>