<!DOCTYPE html>

<html>

<head>

    <title>Abinayasri.github</title>

    <style>

        body {

            font-family: Arial, sans-serif;

            margin: 0;

            padding: 0;

            background-color: #84a6e9;

        }



        header {

            background-color: #941919;

            color: #fff;

            text-align: center;

            padding: 2rem 0;

            position: relative; /* Add this */

        }



        .header-content h1 {

            font-size: 2.5rem;

        }



        /* Add styles for the round profile picture */

        .profileabi.jpg.pdf{

            width: 100px; /* Adjust the size as needed */

            height: 100px;

            border-radius: 75%; /* Create a circular shape */

            object-fit: cover; /* To ensure the image fills the circular area */

            position: absolute; /* Add this */

            top: 75px; /* Adjust top position as needed */

            left: 75px; /* Adjust left position as needed */

        }



        nav {

            background-color: #333;

            color: #fff;

            text-align: center;

        }



        nav ul {

            list-style-type: none;

            padding: 0;

        }



        nav ul li {

            display: inline;

            margin: 0 20px;

        }



        nav ul li a {

            text-decoration: none;

            color: #fff;

        }



        .section-content {

            background-color: #fff;

            padding: 2rem;

            margin: 1rem;

            border-radius: 20px;

            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

            text-align: justify;

        }



        .download-button {

            background-color: #333;

            color: #fff;

            padding: 0.5rem 1rem;

            text-decoration: none;

            border-radius: 20px;

            display: inline-block;

            margin-top: 10px;

            align-self: center;

        }



        .download-button:hover {

            background-color: #555;

        }



        footer {

            text-align: center;

            padding: 1rem 0;

            background-color: #333;

            color: #fff;

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

            <!-- Add your abi.jpg.pdf -->

            <img src="abi.jpg" alt="Your Profile Picture" class="profile-picture">

            <h1>Abinayasri P</h1>

            <p>Am web designer</p>

        </div>

    </header>



    <nav>

        <ul>

            <li><a href="#about">About</a></li>

            <li><a href="#education">Education</a></li>

            <li><a href="#skills">Skills</a></li>

            <li><a href="#projects">Projects</a></li>

            <li><a href="#abi.resume">Abi.Resume</a></li>

           

        </ul>

    </nav>



    <section id=AbinayaSri P">

        <div class="section-content">

            <h2>About Me</h2>

            <p>I'm a <b>web development</b> expert who is passionate about creating dynamic and user-friendly websites. 

                I'm driven by the desire to craft high-performance web applications that enhance user experience and provide

                 seamless digital solutions.I am fresher, I'm dedicated to staying up to date 

                 with the latest trends and innovations in the 

                 web development landscape. I'm also committed to helping others learn more about web technologies, 

                 best practices, and how to build secure and scalable websites.</p>



        </div>

    </section>



    <section id="Bsc computer science and Msc computer science,mphil,phd">

        <div class="section-content">

            <h2>Bsc computer science and Msc,Mphil,phd</h2>

            <p>Anna University  - comp</p>

            

            

        </div>

    </section>



    <section id="html,cyber security,creating website so on">

        <div class="section-content">

            <h2>id="html,cyber security,creating website so on"></h2>

            <ul>

                <li>advance exeal</li>

                <li>Python</li>

                <li>Photoshop</li>

                <li>html</li>

                <li>java</li>

                <li>c++</li>

            </ul>

        </div>

    </section>



    <section id="project 1">

        <div class="section-content">

            <h2>this is my first Project1</h2>

        </div>

    </section>



    <section id="abi.resume">

    

        <div class="section-content">

            <center>

            <h2>abi.resume</h2>

            <a href="abi.resume.pdf" target="_blank" class="download-button">Download CV</a>

        </center>

        </div>

        

    </section>



    <footer>

        <p>&copy; 2025 Abinayasri P</p>

    </footer>



    <script>

        // Smooth scrolling to section when clicking on navigation links

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {

            anchor.addEventListener('click', function(e) {

                e.preventDefault();



                const targetId = this.getAttribute('href').substring(1);

                const targetElement = document.getElementById(targetId);



                if (targetElement) {

                    window.scrollTo({

                        top: targetElement.offsetTop,

                        behavior: 'smooth'

                    });

                }

            });

        });

    </script>

</body>

</html>
