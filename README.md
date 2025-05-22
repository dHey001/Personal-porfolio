https://roadmap.sh/projects/portfolio-website

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Personal Portfolio</title>
    <style>
      body {
        font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
        margin: auto;
        padding: auto;
      }

      .sect {
        display: flex;
        justify-content: space-evenly;
      }

      /* 1 */

      .first {
        border: 2px solid black;
        max-width: 800px;
      }

      .head {
        padding: 30px;
        text-align: center;
        font-size: small;
      }

      .img {
        width: 40px;
        height: 40px;
      }

      .name {
        padding: 5px;
        display: block;
      }

      a {
        text-decoration: none;
      }

      .description {
        padding-bottom: 25px;
      }

      .front {
        display: block;
        text-align: center;
        font-family: monospace;
        font-weight: bold;
        font-size: 17px;
      }

      .no {
        font-family: monospace;
        text-align: center;
        display: block;
        font-size: 10px;
      }

      .contain {
        border-top: 2px solid black;
        text-align: center;
        border-bottom: 2px solid black;
      }

      .t {
        font-weight: bold;
      }

      .s {
        border-top: 2px solid black;
        background-color: #ccc;
        margin: 0px;
        padding: 8px;
      }

      .ex {
        text-align: center;
        font-weight: bold;
      }

      .yt {
        padding-left: 15px;
        border-top: 2px solid black;
      }

      .r {
        background-color: #ccc;
        padding: 15px;
        border-top: 2px solid black;
      }

      .ui {
        border-top: 2px solid black;
        font-weight: bold;
        padding-top: 15px;
        padding-left: 20px;
      }

      .ux {
        border: 2px solid black;
        border-radius: 10px;
        padding-left: 15px;
        margin: 5px auto;
        display: block;
        max-width: 200px;
      }

      .foot {
        display: block;
        text-align: center;
      }

      /* 2 */

      .second {
        border: 2px solid black;
        max-width: 800px;
      }
      .header {
        padding: 20px;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }

      .span {
        padding: 5px;
        display: inline-flex;
        align-items: center;
        justify-content: center;
      }

      .img {
        width: 40px;
        height: 40px;
        display: inline-flex;
        margin-right: 10px;
      }

      .div {
        display: block;
        margin-bottom: 60px;
      }

      .span2 {
        font-family: monospace;
        text-align: center;
        margin-top: 80px;
        display: block;
        font-size: 40px;
        font-weight: bold;
      }

      .span3 {
        font-family: monospace;
        text-align: center;
        display: block;
      }

      .container {
        border-top: 2px solid black;
        border-bottom: 2px solid black;
        display: flex;
      }

      .hero {
        width: 30%;
        box-sizing: border-box;
        border-right: 2px solid black;
      }

      .hero:last-child {
        border-right: none;
      }

      .type {
        font-weight: bold;
        padding-left: 20px;
      }

      .d {
        padding-left: 20px;
      }

      .w {
        border-top: 2px solid black;
        padding-top: 10px;
        padding-left: 20px;
      }

      .e {
        padding-left: 20px;
      }

      .g {
        border-top: 2px solid black;
        padding-left: 20px;
        padding-top: 15px;
        font-weight: bold;
      }

      .f {
        font-weight: bold;
        padding-left: 20px;
        margin-top: 30px;
      }

      .section {
        display: flex;
        justify-content: space-between;
        padding: 20px;
      }

      .b {
        padding: 10px;
        margin: 10px;
        border: 2px solid black;
        border-radius: 10px;
      }

      .footer {
        display: block;
        text-align: center;
        margin-top: 70px;
      }
    </style>
  </head>

  <!-- 1 -->
  <body>
    <section class="sect">
      <div class="first">
        <header class="head">
          <img src="/Images/icon.png" alt="logo" class="img" />
          <span class="name">Your name</span>
          <nav class="nav">
            <a href="#home" class="a">Home</a> /
            <a href="#projects" class="a">Projects</a> /
            <a href="#articles" class="a">Articles</a> /
            <a href="#contact" class="a">Contact</a>
          </nav>
        </header>

        <div class="description">
          <span class="front">Frontend Developer</span>
          <span class="no">html only with proper layout, no styling</span>
        </div>

        <div class="contain">
          <div>
            <p class="t">Projects</p>
            <p class="s">HTML Only Portfolio</p>
            <p class="s">Calculator</p>
            <p class="s">Quiz App</p>
            <p class="s">Countdown Timer</p>
            <p class="s">Product Upcoming Page</p>
          </div>
        </div>

        <p class="ex">Work Experience</p>

        <div class="r">
          <p>roadmap.sh</p>
          <p>Solved all the frontend problems</p>
          <p><a href="">Visit my profile</a></p>
        </div>
        <div class="r">
          <p class="t">Opensource Work</p>
          <p>
            Contributed to 50 opensource <br />
            projects. Made my own projects with <br />
            200 Github Stars.
          </p>
          <p><a href="">Visit my Github Profile</a></p>
        </div>

        <div class="yt">
          <p class="t">Education</p>
          <p>
            Graduated with 3.76 out 4 <br />
            CGPA. Won Acme Hackathon. <br />
            Organized 30 sessions.
          </p>
          <p>Courses I took:</p>
          <ul>
            <li>Object Oriented Programming</li>
            <li>Data Structures and Algorithm</li>
            <li>Web Engineering</li>
            <li>Artificial Intelligence</li>
            <li>Human Computer Interation</li>
            <li>Computer Graphics</li>
            <li>Database Management Systems</li>
            <li>Distributed Database Systems</li>
            <li>Discrete Mathematics</li>
          </ul>
        </div>

        <p class="ui">Reviews from my Teachers</p>

        <div class="ux">
          <p>
            John doe was brilliant student; always stood out with his
            assignments.
          </p>
          <p>
            Jane Doe <br />
            Assistant Professor
          </p>
        </div>

        <footer class="foot">
          <p>&copy all rights reserved 2025</p>
        </footer>
      </div>

      <!-- 2 -->
      <div class="second">
        <header class="header">
          <span class="span"
            ><img src="/Images/icon.png" alt="logo" class="img" />Your
            name</span
          >
          <nav class="nav">
            <a href="#home" class="a">Home</a> /
            <a href="#projects" class="a">Projects</a> /
            <a href="#articles" class="a">Articles</a> /
            <a href="#contact" class="a">Contact</a>
          </nav>
        </header>

        <div class="div">
          <span class="span2">Frontend Developer</span>
          <span class="span3">html only with proper layout, no styling</span>
        </div>

        <div class="container">
          <div class="hero">
            <p class="type">Projects</p>
            <p class="d">HTML Only Portfolio</p>
            <p class="w">Calculator</p>
            <p class="w">Quiz App</p>
            <p class="w">Countdown Timer</p>
            <p class="w">Product Upcoming Page</p>
          </div>

          <div class="hero">
            <p class="type">Work Experience</p>
            <p class="e">roadmap.sh</p>
            <p class="e">Solved all the frontend problems</p>
            <p><a href="" class="e">Visit my profile</a></p>
            <p class="g">Opensource Work</p>
            <p class="e">
              Contributed to 50 opensource <br />
              projects. Made my own projects with <br />
              200 Github Stars.
            </p>
            <p class="e"><a href="">Visit my Github Profile</a></p>
          </div>

          <div class="hero">
            <p class="type">Education</p>
            <p class="e">
              Graduated with 3.76 out 4 <br />
              CGPA. Won Acme Hackathon. <br />
              Organized 30 sessions.
            </p>
            <p class="e">Courses I took:</p>
            <ul>
              <li>Object Oriented Programming</li>
              <li>Data Structures and Algorithm</li>
              <li>Web Engineering</li>
              <li>Artificial Intelligence</li>
              <li>Human Computer Interation</li>
              <li>Computer Graphics</li>
              <li>Database Management Systems</li>
              <li>Distributed Database Systems</li>
              <li>Discrete Mathematics</li>
            </ul>
          </div>
        </div>

        <p class="f">Reviews from my Teachers</p>
        <section class="section">
          <div class="b">
            <p>
              John doe was brilliant student; always stood out with his
              assignments.
            </p>
            <p>
              Jane Doe <br />
              Assistant Professor
            </p>
          </div>

          <div class="b">
            <p>
              John doe was brilliant student; always stood out with his
              assignments.
            </p>
            <p>
              Jane Doe <br />
              Assistant Professor
            </p>
          </div>

          <div class="b">
            <p>
              John doe was brilliant student; always stood out with his
              assignments.
            </p>
            <p>
              Jane Doe <br />
              Assistant Professor
            </p>
          </div>
        </section>

        <footer class="footer">
          <p>&copy all rights reserved 2025</p>
        </footer>
      </div>
    </section>
  </body>
</html>
