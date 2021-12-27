<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="main.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Kumbh+Sans:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" integrity="sha384-DyZ88mC6Up2uqS4h/KRgHuoeGwBcD4Ng9SiP4dIRy0EXTlnuz47vAwmeGwVChigm" crossorigin="anonymous">
    <title>Project 1</title>
</head>
<body>
    <div class="container">
        <div class="profile">
            <div class="profile-picture"><h2>Jane Doe</h2></div>
            <div class="info">
                <p> <i class="fas fa-suitcase" id="info-icon"></i>Designer</p>
                <p><i class="fas fa-home" id="info-icon"></i>London, UK</p>
                <p><i class="fas fa-envelope" id="info-icon"></i>ex@gmail.com</p>
                <p><i class="fas fa-phone-alt" id="info-icon"></i>1224435534</p>
                <hr id="info-break">
            </div>
            <div class="skills">
                <h3><i class="fas fa-star-of-life" id="info-icon"></i>Skills</h3>
                <p>Adobe Photoshop</p>
                <button id="photoshop"></button>
                <p>Photography</p>
                <button id="photography"></button>
                <p>Illustrator</p>
                <button id="illustrator"></button>
                <p>Media</p>
                <button id="media"></button>
            </div>
            <div class="languages">
                <h3><i class="fas fa-globe-americas" id="info-icon"></i>Languages</h3>
                <p>English</p>
                <button id="english"></button>
                <p>Spanish</p>
                <button id="spanish"></button>
                <p>German</p>
                <button id="german"></button>
                <hr class="place-holder">
            </div>
        </div>
        <div class="descriptions">
            <div class="work-experience">
                <h2><i class="fas fa-suitcase"></i>Work Experience</h2>
                <h3 id="heads">Front End Developer / w3schools.com</h3>
                <h4><i class="far fa-calendar-alt" id="calendar"></i>Jan 2015 -  <button>Current</button></h4>
                <p>Jan 2015 - Current
                    Lorem ipsum dolor sit amet. Praesentium magnam consectetur vel in deserunt aspernatur est reprehenderit sunt hic. Nulla tempora soluta ea et odio, unde doloremque repellendus iure, iste.</p>
                    <hr id="description-break">
                <h3 id="other" id="heads">Web Developer / something.com</h3>
                <h4><i class="far fa-calendar-alt" id="calendar"></i> Mar 2012 - Dec 2014</h4>
                <p>Consectetur adipisicing elit. Praesentium magnam consectetur vel in deserunt aspernatur est reprehenderit sunt hic. Nulla tempora soluta ea et odio, unde doloremque repellendus iure, iste.</p>
                <hr id="description-break">

                <h3 id="heads">Graphic Designer / designsomething.com</h3>
                <h4><i class="far fa-calendar-alt" id="calendar"></i>Jun 2010 - Mar 2012</h4>
                <p id="last">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
            </div>
            <div class="education">
                <h2><i class="fas fa-certificate"></i>Education</h2>
                <h3>W3Schools.com</h3>
                <h4><i class="far fa-calendar-alt" id="calendar"></i>Forever</h4>
                <p>Web Development! All I need to know in one place</p>
                    <hr id="description-break">
                <h3 id="other">London Business School</h3>
                <h4><i class="far fa-calendar-alt" id="calendar"></i> 2013 - 2015</h4>
                <p>Master Degree</p>
                <hr id="description-break">
                <h3>School of Coding</h3>
                <h4><i class="far fa-calendar-alt" id="calendar"></i>2010 - 2013</h4>
                <p id="last">Bachelor Degree</p>
            </div>
        </div>
    </div>
    <footer>
        <p>Find me on social media.</p>
        <p><i class="fab fa-facebook"></i><i class="fab fa-instagram"></i><i class="fab fa-snapchat"></i><i class="fab fa-pinterest"></i><i class="fab fa-twitter"></i><i class="fab fa-linkedin"></i></p>
        <p>Powered by w3.css</p>
    </footer>
    <script src="app.js"></script>
</body>
</html>
