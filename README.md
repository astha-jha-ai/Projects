<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background-color: rgb(0, 0, 32);
            color: white;
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 18, 139);
            padding: 0 40px;
        }
        nav .left {
            font-size: 2.5rem;
        }
        nav ul {
            display: flex;
        }
        nav ul li {
            list-style: none;
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: 500;
            font-size: 120%;
            transition: color 0.3s ease, font-size 0.3s ease;
        }
        nav ul li a:hover {
            color: lavender;
            font-size: 1.1rem;
        }
        section {
            padding: 60px 40px;
            text-align: center;
            background-color: rgb(0, 0, 50);
            color: white;
            margin-bottom: 20px;
        }
        section h2 {
            font-size: 2.5rem;
            color: lavender;
            margin-bottom: 20px;
        }
        section p {
            font-size: 1.1rem;
            margin: 10px auto;
            max-width: 800px;
        }
        .first-section {
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 60px 40px;
            flex-wrap: wrap;
        }
        .first-section .left-section {
            flex: 1;
            max-width: 500px;
        }
        .first-section .left-section h1 {
            font-size: 3rem;
        }
        .first-section .left-section .purple {
            color: rgb(181, 159, 202);
        }
        .first-section .left-section p {
            margin-top: 10px;
            font-size: 1.2rem;
        }
        .first-section .left-section hr {
            margin: 15px 0;
            border: 0;
            height: 2px;
            background: lavender;
            width: 50%;
        }
        .first-section .right-section {
            flex: 1;
            max-width: 500px;
            text-align: center;
        }
        .first-section .right-section img {
            width: 100%;
            max-width: 500px;
            border-radius: 50%;
            border: 5px solid lavender;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
        }
        .about-section {
            background-color: rgb(35, 82, 126);
        }
        .services-section {
            background-color: rgb(28, 28, 83);
        }
        .service-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .service {
            background: rgb(70, 70, 243);
            border-radius: 8px;
            padding: 20px;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4);
        }
        .service h3 {
            color: lavender;
            margin-bottom: 10px;
        }
        .projects-section {
            background-color: rgb(35, 82, 126);
        }
        .project-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .project {
            background: rgb(9, 9, 240);
            border-radius: 8px;
            padding: 20px;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4);
        }
        .project h3 {
            color: lavender;
            margin-bottom: 10px;
        }
        .contact-section {
            background-color: rgb(28, 28, 83);
        }
        form {
            margin-top: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }
        form input, form textarea {
            width: 80%;
            max-width: 500px;
            padding: 10px;
            border: 1px solid lavender;
            border-radius: 5px;
            background: rgb(40, 40, 100);
            color: white;
            font-size: 1rem;
        }
        form button {
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background: lavender;
            color: rgb(0, 0, 32);
            font-size: 1rem;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        form button:hover {
            background: white;
            color: rgb(0, 0, 32);
        }
        @media (max-width: 768px) {
            nav {
                flex-wrap: wrap;
                height: auto;
                padding: 20px;
            }
            .first-section {
                flex-direction: column;
                text-align: center;
            }
            .first-section .left-section,
            .first-section .right-section {
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="left">My Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="#Home">Home</a></li>
                    <li><a href="#About">About</a></li>
                    <li><a href="#Services">Services</a></li>
                    <li><a href="#Projects">Projects</a></li>
                    <li><a href="#Contact Me">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="first-section" id="Home">
            <div class="left-section">
                <h1>Hi, I'm <span class="purple">Astha</span></h1>
                <p>I am a passionate web developer dedicated to learn more about softwares.</p>
            </div>
            <div class="right-section">
                <img src="astha.jpg" alt="My Picture">
            </div>
        </section>
        <section class="about-section" id="About">
            <h2>About Me</h2>
            <p>  I am a B.Tech 3rd-year student at B.P. Poddar Institute of Management and Technology, pursuing my degree in Electronics and Communication Engineering. Apart from academics, I am a core member of the <strong>Anti-Ragging Department</strong> of my college and an active volunteer in the National Service Scheme (NSS). I completed my schooling in Bihar, where I was born and brought up. My passion for learning and contributing to society drives me to actively participate in various initiatives and projects.</p>
        </section>
        <section class="services-section" id="Services">
            <h2>Services</h2>
            <div class="service-container">
                <div class="service">
                    <h3><u>Web Development</u></h3>
                    <p>Created this personal portfolio and To-do list using HTML, CSS and Java Script and also working on other projects like calculator, Tic-tac-toe and others to excel my knowledge in web developement</p>
                </div>
                <div class="service">
                    <h3><u>Graphics Design</u></h3>
                    <p>Designing intuitive and aesthetically pleasing user interfaces and thumbnails. Learnt social media management and video and thumbnail editing and currently working as part time Social media manager of Singer Ashutosh Kumar Jha. </p>
                </div>
                <div class="service">
                    <h3><u>Cybersecurity</u></h3>
                    <p>Completed cybersecurity basic concepts certification exam through the Digital Academic Platform 
                        of CSCOE Kolkata from WEBEL in October 2024 and working to make a project based on secure login system using my knowledge of web developement.</p>
                </div>
            </div>
        </section>
        <section class="projects-section" id="Projects">
            <h2>Projects</h2>
            <div class="project-container">
                <div class="project">
                    <h3><u>Portfolio Website</u></h3>
                    <p>A portfolio website is an excellent place to display our projects, writing samples, code, or any other work we want to share. This personal portfolio is showcasing my skills and projects in an organized and professional way.</p>
                </div>
                <div class="project">
                    <h3><u>To-do list</u></h3>
                    <p>To-Do List is a simple and effective tool used to organize tasks, goals, or activities. There are various  benefits of to do list like it helps in task management, boosts productivity,and reduces stress.</p>
                </div>
            </div>
        </section>
        <section class="contact-section" id="Contact Me">
            <h2>Contact Me</h2>
            <p>If you'd like to work together or have any questions, feel free to reach out!</p>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>
</body>
</html>
