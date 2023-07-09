<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Anirban - Freelancer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap"
      rel="stylesheet"
    />
    <style>
      * {
        margin: 0;
        padding: 0;
      }
      body {
        background-color: rgb(2, 2, 83);
        color: white;
        font-family: "Poppins", sans-serif;
      }

      nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 60px;
        background-color: rgb(0, 1, 41);
      }
      nav ul {
        display: flex;
        justify-content: center;
      }
      nav ul li {
        list-style: none;
        margin: 0 23px;
      }
      nav ul li a {
        text-decoration: none;
        color: white;
      }

      nav ul li a:hover {
        color: rgb(123, 123, 236);
        font-size: 1.01rem;
      }

      main hr {
        border: 0;
        background-color: #8782f3;
        height: 1.2px;
        margin: 60px 84px;
      }

      .left {
        font-size: 1.5rem;
      }
      .firstSection {
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin: 250px 0;
      }

      .firstSection > div {
        width: 30%;
      }

      .leftSection {
        font-size: 1.75rem;
      }
      .leftSection .btn {
        padding: 12px;
        background: rgb(61, 61, 199);
        color: white;
        border: 2px solid white;
        border-radius: 6px;
        font-size: 20px;
        cursor: pointer;
      }
      .leftSection .buttons {
        padding: 50px 0;
      }
      .rightSection img {
        width: 80%;
      }
      .purple {
        color: rgb(125, 68, 151);
      }
      .text-gray {
        color: gray;
      }
      #element {
        color: rgb(125, 68, 151);
      }
      .secondSection {
        max-width: 80vw;
        margin: auto;
        height: 80vh;
      }

      .secondSection h1 {
        font-size: 1.9rem;
      }

      .secondSection .box {
        background: white;
        width: 76vw;
        height: 2px;
        margin: 56px 0;
        display: flex;
      }

      .secondSection .vertical {
        height: 93px;
        width: 1px;
        background-color: white;
        margin: 0 95px;
      }

      .image-top {
        width: 23px;
        position: relative;
        top: -32px;
        left: -11px;
      }
      .vertical-title {
        position: relative;
        top: 72px;
        width: 150px;
      }
      .vertical-desc {
        position: relative;
        top: 86px;
        color: gray;
        width: 150px;
        font-size: 9px;
      }
      footer {
        background-color: rgb(10, 3, 31);
      }
      .footer {
        display: flex;
        padding: 23px 122px;
        justify-content: space-evenly;
      }
      .footer  div{
        width: 33%;
      }
      .footer ul {
        list-style: none;
        padding: 0;
        margin: 0;
      }
      .footer ul li {
        display: inline-block;
        margin-right: 10px;
        color: white;
      }
      footer .footer-rights {
        text-align: center;
        color: gray;
        padding: 12px 0;
      }
      .footer-third ul {
        list-style-type: none;
        padding: 0;
        margin: 0;
} 
    </style>
  </head>
  <body>
    <header>
      <nav>
        <div class="left">Anirban's Portfolio</div>
        <div class="right">
          <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/">About</a></li>
            <li><a href="/">Services</a></li>
            <li><a href="/">Projects</a></li>
            <li><a href="/">Contact Me</a></li>
          </ul>
        </div>
      </nav>
    </header>

    <main>
      <section class="firstSection">
        <div class="leftSection">
          Hi, My name is <span class="purple">Anirban Fadikar</span>
          <div>and I am a passionate about</div>
          <span id="element"></span>
          <div class="buttons">
            <button class="btn">Download Resume</button>
            <button class="btn">Visit Github</button>
          </div>
        </div>
        <div class="rightSection">
          <img src="Midjourney(3).jpg" alt="" />
        </div>
      </section>
      <hr />
      <section class="secondSection">
        <span class="text-gray">What I have done so far</span>
        <h1>Work Experience</h1>

        <div class="box">
          <div class="vertical">
            <img class="image-top" src="pngwing.com.png" alt="" />
            <div class="vertical-title">Freelancer</div>
            <div class="vertical-desc">
              I am a fresher freelancer who is embarking on my journey as an
              independent professional, seeking opportunities to showcase their
              skills, deliver quality work, build a portfolio, and establish a
              reputation in the freelancing world.
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="pngwing.com (1).png" alt="" />
            <div class="vertical-title">Graphic Designer</div>
            <div class="vertical-desc">
              I am a fresher graphic designer who is eager to unleash their creativity,
              refine their design skills, and bring visual concepts to life.
              I am excited to collaborate, learn from experienced designers,
              and build an impressive portfolio.
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="pngwing.com (2).png" alt="" />
            <div class="vertical-title">Web Developer</div>
            <div class="vertical-desc">
              I am a web fresher web developer who is excited to gain practical
              experience, collaborating on projects, tackling challenges, and
              acquiring new skills to enhance their proficiency in web
              development.
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="pngwing.com (3).png" alt="" />
            <div class="vertical-title">Content Writer</div>
            <div class="vertical-desc">
              I am a  fresher content writer who is a creative wordsmith, passionate about
              crafting compelling and engaging content. I am eager to
              explore different topics, refine their writing skills, and deliver
              high-quality content that captivates readers and meets clients'
              expectations.
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="pngwing.com (5).png" alt="" />
            <div class="vertical-title">Programmer</div>
            <div class="vertical-desc">
              I am a fresher programmer with experience in C, Java, HTML, CSS,
              JavaScript, and Python possesses a versatile skill set. I am
              ready to tackle diverse programming challenges, build robust
              applications, and adapt to various development environments with a
              thirst for continuous learning and growth.
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="pngwing.com (6).png" alt="" />
            <div class="vertical-title">Game tester/developer</div>
            <div class="vertical-desc">
               I am a fresher game developer/designer who is fueled by their love for
              gaming, eager to dive into the world of game development. I
              aspire to craft immersive experiences, learn new technologies, and
              create captivating games that entertain and engage players.
            </div>
          </div>
          <div class="vertical">
            <img class="image-top" src="pngwing.com (4).png" alt="" />
            <div class="vertical-title">Video editor</div>
            <div class="vertical-desc">
              I am a fresher video editor who is passionate about storytelling through
              visual media. I am eager to sharpen their editing skills,
              experiment with various techniques, and create captivating videos
              that engage and inspire audiences.
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer>
      <div class="footer">
        <div class="footer-first">
          <h3>Anirban's Freelancer Portfolio</h3>
        </div>
        <div class="footer-second">
          <ul>
            <p>LinkedIn Profile :</p>
            <p>Github Profile :</p>
            <p>Mobile No :</p>
            <p>Email ID  :</p>
          </ul>
        </div>
        <div class="footer-third">
          <ul>
            <link>https://github.com/Anirbanf2425</link>
            <link>https://www.linkedin.com/in/anirban-fadikar-ab81ab279/</link>
            <li>+91 9867478541</li>
            <li>fadikaranirban138@gmail.com</li>
          </ul>
        </div>
      </div>
      <div class="footer-rights">
        Copywright &#169;fadikaranirbanportfolio.com | All rights reserved
      </div>
    </footer>

    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script>
      document.addEventListener("DOMContentLoaded", function () {
        var typed = new Typed("#element", {
          strings: ["Web Developer", "&amp; Graphic Designer"],
          typeSpeed: 50,
        });
      });
    </script>
  </body>
</html>
