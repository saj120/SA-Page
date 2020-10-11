
This is one of my ongoing html/css projects (1st to Github, actually).
It is a work in progress, that I will continually upgrade as I learn more JS.


PHP site to make form
https://blog.hubspot.com/marketing/html-form-email

<?php

if($_POST["message"]) {

mail("sarriaga62@gmail.com", "Here is the subject line", $_POST["Work order desribed"]. "From: an@email.address");

}

?>

<!Doctype html>
<html>
  <head>
    <title>Samuel Arriaga, MBA</title>
    <link rel="stylesheet" href="/css/contact.css">
  </head>
    
  <body>
    <div class="contact-nav">
        <ul class="nav">
        <li><a href="index.html">Home</a></li>
        <li><a href="https://github.com/saj120?tab=projects" target="_blank">Portfolio</a></li>
        <li><a href="resume.html">Resume</a></li>
    </div>
    
    <header>
        <img src="/assets/profile-pic.jpg" alt="picture of Samuel at Hyatt" class="contact-image">
        <h1 class="tag">Sam Arriaga</h1>
    </header>

    <section id="middle">    
        <p>Submit your email for quality web development quotes. Our team will provide a fair and quick response.</p>
    </section>

    <div id="form">

      <form method=”POST” action="subscriberform.php">
      
        <textarea name=”message”></textarea><br><br> 
        
        <input type=”submit”> 

      </form>
    
    </div>
    

    <!--
    <div id="form">
        <fieldset id="custinfo">
        <legend>Contact Information</legend>  

        <label for="custname">Name *</label>
        <input name="custname" id="custname" placeholder="First, Last"/>

        <label for="email">E-mail *</label>
        <input name="email" id="email" placeholder="email@info.com"/>

        <label for="phone">Phone *</label>
        <input name="phone" id="phone" placeholder="(000)111-2222"/>

        <label for="zip">Postal Code *</label>
        <input name="zip" id="zip" placeholder="12345-0000"/>
        </fieldset>

        <fieldset id="comments">
        <legend>Comments</legend>  

        <label for="comments">Describe work required *</label>
        <textarea name="comments" id="comments" placeholder="Tell us what you have in mind for this project!"></textarea>
        </fieldset>
    
        <input type="email" placeholder="Your email">
        <input type="submit">
    </div>
    -->
    <footer>

    </footer>
</body>
</html>
    
    <!-- <div id="form">    
      <input type="email" placeholder="Your email">
      <input type="submit">
    </div>
    

    <form action=https://sarriaga62@gmail.com/myform-processor.php></form>


    </html> -->