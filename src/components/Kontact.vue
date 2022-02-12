<template>
  
<section id="Kontact" style="min-height: 87.2vh; justify-content: center; flex-direction: column; display: flex;">

        <h2>Contact</h2>

        <form id ="my_form" action="https://formspree.io/f/xpzknqlr" method="POST">

          <h1>Enter your details below:</h1>

          <div class="row">
            <div class="col-6">
              <input type="text" id="fname" name="fname" cols="50" placeholder="First Name:" required>
            </div>

            <div class="col-6">
              <input type="text" id="lname" name="lname" cols="50" placeholder="Last Name:" required>
            </div>
          </div>

           <div class="row">
            <div class="col-6">
              <input type="email" id="mail" name="mail" cols="50" placeholder="Email:" required>
            </div>
            <div class="col-6">
              <input type="text" id="cell" name="p_number" cols="50" placeholder="Cell:" required>
          </div>
    </div>

              <textarea name="y_message" id="message" cols="50" rows="10" placeholder="Subject">
        </textarea>

      <div id="buttons"> 
      <button type="submit" class="beetn" value="submit">Submit</button>
      <button type="reset" class="beetn">Reset</button>

      </div>

      </form>


    </section>

</template>

<script>
export default {

}
</script>

<style>

.row {
  padding-bottom: 50px;
}

.beetn {
  background: pink;
  color: black;
  display: inline-block;
}

input {
  width: 80%;
  border: none;
  border-radius: 25px;
}

#message {
  width: 90%;
  border-radius: 25px;
  margin: auto;
}


form {
  background: rgba( 255, 255, 255, 0.1 );
box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
backdrop-filter: blur( 20px );
-webkit-backdrop-filter: blur( 20px );
border-radius: 10px;
border: 1px solid rgba( 255, 255, 255, 0.18 );
  width: 50%;
  margin: auto;
}

#Testies {
    background:linear-gradient(0deg, rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('../assets/images/background.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed; 
    backface-visibility:visible;
    background-size: 100% 100%;
  }
</style>