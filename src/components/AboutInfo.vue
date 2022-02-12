<template>

<section id="About" style="min-height: 87vh; justify-content: center; flex-direction: column; display: flex;">

<h2>About Me</h2>
<div class="container">
  <div class="row">
   <div class="col">

    <!-- Transparent -->
    <img src="../assets/images/Daniel2-removebg-preview.png" width="750" height="500">
  
   </div>
   <div class="col">
 
<br>

    <span>
    <h4 class="h4typewriter" 
    style="color: rgb(231, 231, 231);
           font-size: 20px;
           text-shadow: 3px 3px rgb(94, 1, 1); 
           font-family: 'Courier New', Courier, monospace;"> 
           Hi, I'm Daniel Bowers
           </h4>
           </span>

    <br>

    <span><h6>Web Developer</h6></span>

    <br>

 <h5> 
      An aspiring Web Developer - Photographer & I persue physical activities often, such as; Basketball, Long Walks, Soccer and Exercise. 
      <br>
      <br>
        I am an open-minded, hard-working, enthusiastic person that is always determined to learn new things. I feel that gaining knowledge every day benefits me and makes me a better person. I am also a very kind, respectful, and humble person and will always try to help those in need.
    </h5>

    <br>

    <span><h3>Email : dwwildfire295@gmail.com</h3></span>
    <span><h3>Language : English - Afrikaans</h3></span>
    <span><h3>Date Of Birth : 20-05-2002</h3></span>
    <span><h3>Hobbies : Basketball - Photography</h3></span>

    <br>
    <br>
    
  </div>
   </div>
</div>

</section>
</template>

<script>

</script>

<style>
#About {
    background:linear-gradient(0deg, rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('../assets/images/blur3.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed; 
    backface-visibility:visible;
    background-size: 100% 100%;
  }
  
  .h4typewriter{font-family: 'Courier New', Courier, monospace;

    overflow: hidden; 
    white-space: nowrap;
    margin: 0 auto; 
    letter-spacing: .3em;
    animation: 
      typing 2.0s steps(40, end),
      blink-caret .70s step-end infinite;
    animation-iteration-count: inherit;
  }

  @keyframes typing {
    from { width: 0 }
    to { width: 44% }
  } 
  
</style>