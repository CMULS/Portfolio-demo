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
        text-align: centre;
      }
    } 
          #img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 50%;
            display: block;
            margin: 20px auto;
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
        <h1>Hello</h1>
        <h4>I'm David a web developer</h4><img id="img" src="https://raw.githubusercontent.com/CMULS/kisekicorp.com/refs/heads/main/IMG_20210418_193526%20(2).jpg"/>
      </section>
      </div>
      
      <section id="projects">
        <h2>Here are some of my projects</h2>
        <div class="project-tile">
          <a href="https://cmuls.github.io/Galaxy-Webers/">Frosted Glass Page</a>
          <p>This is a page with a transparent visa card</p>
        </div>
         <div class="project-tile">
          <a href="https://cmuls.github.io/Galaxi-2/">Visa Card with black hole background</a>
          <p>This is a page with a transparent visa card with black hole background</p>
        </div>
      </section>

      <footer>
        <a id="profile-link" href="https://.com/your-github-profile" target="_blank">Checkout my Github Profile</a>
      </footer>
    </body>
    </html>
