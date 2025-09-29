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
    

      <header id="navbar">
        <nav>
          <ul>
            <li><a href="#welcome-section">Welcome</a></li>
            <li><a href="#projects">Projects</a></li>
         </ul>
        </nav>
      </header> 
      
      <section id="welcome-section">
        <h1>Hi I'm Cmulz</h1>
        <h4>a web developer</h4>
      </section>
      
      <section id="projects">
        <h2>Here are some of my projects</h2>
        <div class="project-tile">
          <h3>Tribute Page</h3>
          <p>This is tribute to Dr Norman Borlaug</p>
          <a href="#">View project</a>
      </div>
      </section>

      <footer>
        <a id="profile-link" href="https://.com/your-github-profile" target="_blank">Checkout my Github Profile</a>
      </footer>
    </body>
    </html>
