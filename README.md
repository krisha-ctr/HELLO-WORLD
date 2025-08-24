# HELLO-WORLD
This my first repository of Git

## About Me
Hi! I’m Krisha Shrimali, a student exploring programming and data analysis.  
This is my first repository on GitHub 🚀.  

## Goals
- Learn and practice coding in Python, C, and Java  
- Explore data analysis and visualization  
- Share my learning journey here  

✨ Stay tuned for updates!

![data-analysis-skills-duties-responsibilities](https://github.com/user-attachments/assets/af6d300e-666c-41fe-a8cc-023597d9b849)
[home.html](https://github.com/user-attachments/files/21956144/home.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
	<script src="jquery-3.6.0.min.js"></script>
    <script>
    $(document).ready(function(){
        // Smooth scrolling for same-page links
        $('a[href*="#"]').on('click', function (e) {
            e.preventDefault();
    
            var target = $(this.hash);
            if (target.length) {
                $('html, body').animate({
                    scrollTop: target.offset().top
                }, 1000);
            }
        });
    });
    $(document).ready(function(){
    // Show or hide the scroll up button based on scroll position
    $(window).scroll(function() {
        if ($(this).scrollTop() > 100) {
            $('#scrollUpBtn').fadeIn();
        } else {
            $('#scrollUpBtn').fadeOut();
        }
    });

    // Smooth scrolling to the top when the button is clicked
    $('#scrollUpBtn').click(function() {
        $('html, body').animate({scrollTop: 0}, 800);
        return false;
    });
});
</script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            background-image: url('background.jpg');
            background-size: cover;
        }

        header {
            background-color: #feb9b9;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        nav {
            background-color: #b7ffff;
            color: #fff;
            text-align: center;
            padding: 4em;
			font-size:40px;
			padding:40px;
			width: 100%;
			margin: auto;
        }

        nav a {
            color: #b76d9d;
            text-decoration: none;
            margin: 0 15px;
            font-size: 25px;
        }

        section {
            padding: 20px;
            text-align: center;
            background-color: rgb(149, 149, 201);
            background-color: rgba(140, 149, 201, 0.7); /* White with 80% opacity */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            width:600px;
            margin-left:auto;
            margin-right: auto;
            margin-top: 20px;
            opacity: 70%;
        }

        footer {
            background-color: #feb9b9;
            color: #fff;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>BEAUTY WORLD</h1>
    </header>

    <nav>
        <a href="home.html">Home</a>
        <a href="aboutus.html">Aboutus</a>
        <a href="registration.html">Registration</a>
		<a href="product.html">Products</a>
		<a href="contactus.html">Contactus</a>
		<a href="review.html">Review</a>
    </nav>

    <section>
        <h2>Welcome to my Website</h2>
        <div style="width: 500px;color: rgba(0, 0, 0, 1);margin:auto;text-align: justify;">Step into a world where beauty knows no bounds with our makeup business. Delve into a palette of endless possibilities, where each stroke of color tells a unique story. From the subtle glow of dawn to the captivating allure of dusk, our products accentuate every facet of your personality. With formulas as rich as your dreams and hues as vibrant as your spirit, we invite you to discover the artistry of self-expression. Unleash your inner artist and embrace the canvas of your own beauty with us.</div>
    </section>

    <footer>
        &copy; 2024 Your Website. All rights reserved.
    </footer>
</body>
</html>
