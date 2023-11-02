index.html
<!DOCTYPE html>
<html>
    <head>
        <title>Your Name - Portfolio</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                margin: 0;
                padding: 0;
                background-color:#ffd4e157;
            }

            header {
                background-color:#ff9575cd;
                color:black;
                text-align: center;
                padding: 2rem 0;
                position: relative;
            }
            .header-content h1 {
                font-size:2rem;
            }
            .profile-picture {
                width:100px; /*Adjust the size as needed */
                height:100px;
                border-radius: 75%;/*Create a circular shape */ 
                object-fit: cover;/*To ensure the image files the circular */
                position:absolute;/*Add this */
                center:75px;/*Adjust top position as needed */
                left:20px;/*adjust left position as needed */
            }
            nav {
                background-color:#f176;
                color:#aa0e90;
                text-align:center;
            }
            nav ul {
                list-style-type:none;
                padding:0;
            }
            nav ul {
                display:inline;
                margin:020px;
            }
            nav ul li a {
                text-decoration:none;
                color#ffffff;
            }
            .section-content {
                background-color:#ff212121;
                padding:2rem;
                margin:1rem;
                border-radius:20px;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            }
            .download-button {
                background-color:black;
                color:#ffefebe9;
                padding: 0.5rem 2rem;
                text-decoration: none;
                border-radius: 20px;
                display:inline-block;
                margin-top:10px;
            }
            .download-button:hover{
                background-color:#5ac6f1;
            }
            footer {
                text-align:center;
                padding:2rem;
                background-color:black;
                color:#fff;
            }
            ul {
                list-style-type: disc;
                padding-left: 20px;
            }
        </style>
    </head>
    <body>
    <header>
            <div class="header-content">
                <!-- Add your profile picture here-->
                <img src="abi.jpg"alt="your profile picture" class="profile-picture">
                <h1>abinaya</h1>
                <p>Student</p>
            </div>
        </header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#resume">Resume</a></li>
            </ul>
        </nav>
        <section id="about">
            <div class="section-content">
                <h2>About Me</h2>
                <p>Hello Everyone!I am Computer Science student.</p><p>I consider myself a responsible and orderly person.</p>
                        </div>
        </section>
        <section id="Contact">
            <div class="section-content">
                <h2>Contact</h2>
                <ul>
                    <li>8883232579</li>              <li>abinayaabinaya49631@gmail.com</li>                 <li>163/B, colony street townstation mayiladuthurai.</li>
                </ul>
            </div>
        </section>
        <section id="education">
            <div class="section-content">
                <h2>Education</h2>
                <p>Annamalai University</p>
                <p>Bachelor of Science(Computer Science)</p>
                <p>Dharmapuram Adhinam Arts College.</p>
                <p>2021-2024</p>
            </div>
        </section>
        <section id="skills">
            <div class="section-content">
                <h2>Skills</h2>
                <ul>
                    <li>C</li>
                    <li>CPP</li>
                    <li>JAVA</li>             
                    <li>MOBILE APPLICATION DEVELOPMENT</li>
                </ul>
                    </div>
        </section>
        <section id="Language">
            <div class="section-content">
                <h2>Language</h2>
                <ul>
                    <li>Tamil</li>
                    <li>English</li>
                </ul>
            </div>
        </section>
        <section id="resume">
            <center>
            <div  class="section-content">
                <h2>Resume</h2>
                <a href="abi.jpg" class="download-button">Download CV</a>
            </div>
        </center>
        </section>
        <footer>
            <p>&copy; 2023 abinaya</p>
        </footer>

        <script>
            //smooth scrolling to section when clicking on nevigation links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click',function(e){
                    e.preventDefault();

                    const targetId = this.getAttributes('href').substring(1);
                    const targetElement = document.getElementById(targetId);

                    if(targetElement){
                        window.scrollTo({
                            top:targetElement.offsetTop,
                            behavior:'smooth'
                        });
                        }
                });
            });
        </script>
      </body>
     </html>
