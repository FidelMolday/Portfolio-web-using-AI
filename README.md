Prompt engineering test
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Moldays - Portfolio</title>
</head>

<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#services">My Services</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>
            <h1>I `m a developer
                <br> Molday Fidel
            </h1>
           I'm a front-end developer with many years of experience.                                                 
        </p>
        <h3 class="role">UI / UX Designer & Web Developer</h3>
        <div class="btn">LEARN MORE</div>
        
    </section>
    <section id="about" class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>
            It`s  Molday Fidel the most popular web developer
        </p>
    </section>
    <section id="services" class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>
     I do web development,
     web Hosting, and android Development.
            
        </p>
    </section>
    <section id="blog" class="hero">
        <h1>My Official blog page</h1>
        <p>
     I do web development,
     web Hosting, and android Development.
            
        </p>
    </section>






    <!-- Your content for the home page goes here -->

    <footer>
        <p>&copy; 2023 Your Name. All rights reserved.</p>
    </footer>
    <style>
        body, h1, h2, p {
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: rebeccapurple;
}

header {
    background-color: #333;
    color: #fff;
    padding: 15px 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 100;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

.hero {
    text-align: center;
    padding: 150px 0;
    background-image: url('');
    background-size: cover;
    background-position: center;
    color: #fff;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

.hero h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2em;
    margin-bottom: 40px;
}

section {
    padding: 40px 0;
    text-align: center;
}
/* Styles for the role text */
.role {
    font-size: 1.5em;
    color: #007BFF; /* Change to your desired text color */
}

/* Styles for the button */
.btn {
    background-color: #007BFF;
    color: #fff;
    padding: 10px 0px; /* Adjust the padding for the desired size */
    border: none;
    text-align: center;
    width: 150px;
    border-radius: 15px; /* Adjust the border radius for a rounded shape */
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s, box-shadow 0.3s; /* Add box-shadow to the transition */
}
btn-center {
    display: flex;
    justify-content: center; /* Center horizontally */
    align-items: center; /* Center vertically */
    height: 100vh; /* Ensure the container spans the full viewport height */
}

.btn:hover {
    background-color: #0056b3;
    box-shadow: 0 0 10px rgba(0, 123, 255, 0.7); /* Add a box-shadow to create the glowing effect */
}



section h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

section p {
    font-size: 1.2em;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Style links in the navigation bar */
nav a {
    text-decoration: none;
    color: #fff;
    transition: color 0.3s;
}

nav a:hover {
    color: #ff9900;
}

/* Add styles for testimonial section, services section, and about section */
/* For example: */
#testimonial {
    background-color: #fff;
    padding: 40px 0;
}

.services {
    background-color: #f4f4f4;
    padding: 40px 0;
}

.about {
    background-color: #fff;
    padding: 40px 0;
}
/* Testimonial section styles */
#testimonial {
    background-color: #fff;
    padding: 60px 0;
}

.testimonials-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.testimonial-card {
    background-color: #f4f4f4;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    margin: 20px;
    padding: 20px;
    text-align: center;
    width: 300px;
}

.testimonial-card h3 {
    font-size: 1.5em;
    margin: 10px 0;
}

.testimonial-card p {
    font-size: 1.2em;
}

/* Services section styles */
.services {
    padding: 60px 0;
     background-image: url('/home/fidel/Pictures/Wallpapers/DSC03717.jpg');
    background-size: cover;
    background-position: center;
}

.service-card {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    margin: 20px;
    padding: 20px;
    text-align: center;
    width: 300px;
}



.service-card h3 {
    font-size: 1.5em;
    margin: 10px 0;
}

.service-card p {
    font-size: 1.2em;
}

/* About section styles */
.about {
    background-color: #fff;
    padding: 60px 0;
}

.about-content {
    display: flex;
    justify-content: center;
    align-items: center;
}
/* Apply the background image to the home page hero section */
.about-hero {
    text-align: center;
    padding: 150px 0;
    background-image: url('/home/fidel/Pictures/Wallpapers/DSC03717.jpg'); /* Replace 'your-background-image.jpg' with the path to your image */
    background-size: cover;
    background-position: center;
    color: #fff;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}


.about-image {
    border-radius: 50%;
    height: 200px;
    width: 200px;
}

.about-text {
    margin-left: 20px;
    text-align: left;
}

.about-text h2 {
    font-size: 2em;
    margin: 10px 0;
}

.about-text p {
    font-size: 1.2em;
}

/* Add specific styles for different sections as needed */


/* Add specific styles for different sections as needed */

/* Responsive design for smaller screens */
@media (max-width: 768px) {
    nav ul {
        text-align: center;
        padding: 10px 0;
    }
    
    nav ul li {
        display: block;
        margin: 10px 0;
    }
    
    header {
        padding: 10px 0;
    }
    
    .hero {
        padding: 100px 0;
    }
}

    </style>
    <script src="script.js"></script>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
    const navLinks = document.querySelectorAll("nav a");

    navLinks.forEach(link => {
        link.addEventListener("click", smoothScroll);
    });

    function smoothScroll(e) {
        e.preventDefault();
        const targetId = this.getAttribute("href").substring(1);
        const targetElement = document.getElementById(targetId);
        const offset = targetElement.offsetTop - 80; // Adjust this value to your preference

        window.scroll({
            top: offset,
            behavior: "smooth"
        });
    }
});

    </script>
</body>

</html>
