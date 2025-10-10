<!DOCTYPE html>
<html>
<head>
  <title>CMulz Portfolio</title> 
  <link href="style.css">
  <style>
    #welcome section {
      height: 100vh;
    } 
    #navbar {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background-color: black ;
    }  

    @media (max-width: 650px) {
      body {
        background-color: #023020;
      }
      h1 {
        color: white;
      } 
      h4 {
        color: red;
      }
    } 
  </style>
</head>
<body>
    
     <div>
      <header id="navbar">
        <nav>
          <ul>
            <li><a href="#welcome-section">Welcome</a></li>
            <li><a href="#projects">Projects</a></li>
         </ul>
        </nav>
      </header> 
      </div>
      <div>
      <section id="welcome-section">
        <h1>Hi I'm Cmulz</h1>
        <h4>a web developer</h4>
      </section>
      </div>
      
      <section id="projects">
        <h2>Here are some of my projects</h2>
        <div class="project-tile">
          <a href="#">Frosted Glass Page</a>
          <p>This is a page with a transparent visa card</p>
        </div>
         <div class="project-tile">
          <a href="#">Visa Card with black hole background</a>
          <p>This is a page with a transparent visa card with black hole background</p>
        </div>
      </section>

      <footer>
        <a id="profile-link" href="https://.com/your-github-profile" target="_blank">Checkout my Github Profile</a>
      </footer>
    </body>
    </html>
