# My-portfolio.kamlakant
#index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>KAMLAKANT KUMAR</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#profiles">Profiles</a></li>
                    <li><a href="#Experience">Experience</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello everyone! my self kamlakant kumar currently ,I am 2nd year student at parul university vadodra gujarat india.</p>
            <p>Skills:-Front-end-Web dev |c |c++ |python |java |Data Structure & Algorithm |javascript||</p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>Tic Tac Toe game project with the help of html,css & javascript.</p>
                <a href=""></a>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>ATM machine project by the help of c language.</p>
            </div>
            <div>
                <div class="project">
                    <h3>Project 3</h3>
                    <p>Navigation baar with the help of html ,css &javascript. </p>
            </div>
            <div>
                <div class="project">
                    <h3>Project 4</h3>
                    <p>Guess the number with the help of python programming language.</p>
            </div>
            <div class="project">
                <h3>Project 5</h3>
                <p>Random password generator with the help of python.</p>
            </div>
        </div>
    </section>

    <section id="Profiles">
        <div class="container">
            <a href="https://www.linkedin.com/in/kamlakant-kumar-300379209/">linkedin</a>
        </div>
        <div class="container">
            <a href="https://x.com/kamlakant__">twitter</a>
        </div>
        <div class="container">
            <a href="https://leetcode.com/u/kamlakant_/">leetcode</a>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact</h2>
            <form id="contact-form">
                <input type="text" id="Name" name="name" placeholder="Your Name" required>
                <input type="email" id="Email" name="email" placeholder="Your Email" required>
                <textarea id="message" name="Message" placeholder="Write Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 @Kamlakant kumar. All rights reserved.</p>
        </div>
    </footer>

    <script src="portfolio.js"></script>
</body>
</html>
