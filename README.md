
<head>
  <meta charset="UTF-8">
  <title>Lora Online Shopping Store</title>
  <style>
		/* Your existing CSS styles here */

		h1 {
			color: #db1d49; /* Set the color of the heading to #db1d49 */
		}
	</style>
  <link rel="icon" href="Lora logo test png.png" type="lora logo white.png">
  <style>
    
    
}
  </style>
<!DOCTYPE html>
<html>
<head>
  <title>My HTML Page</title>
  <style>
    body {
      margin: 0;
      padding: 0;
    }
    
    .cover-section {
      background-image: url("FB cover new2.jpg");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      height: 300px; /* Adjust the height as needed */
      display: flex;
      align-items: center;
      justify-content: center;
    }
    
    .logo {
      text-align: center;
    }
    
    .website-name {
      color: #db1d49;
      font-size: 24px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <div class="cover-section"><div class="logo">
  <a href="website2.html">
    <img src="Lora logo test png.png" alt="Lora Logo" width="200" height="200">
  </a>
      <h1 class="website-name">Lora Online Shopping Store</h1>
      
    </div>
  </div>
  
  <!-- Rest of your HTML content goes here -->
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Shop Now</title>
    <style>
        @keyframes blink {
            0% {
                opacity: 1;
            }
            50% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }

        /* Add CSS styles to position the blinking button */
        #shop-now-button {
            position: absolute;
            top: 170px;
            left: 130px;
            z-index: 9999;
            padding: 10px 20px;
            background-color: #da1d48;
            color: #fff;
            font-size: 20px;
            font-weight: bold;
            text-decoration: none;
            border: none;
            cursor: pointer;
            animation: blink 1s infinite;
        }
    </style>
</head>
<body>
    <div class="cover-area">
        <!-- Your cover area content goes here -->
    </div>

    <a href="Products test 02.html" id="shop-now-button">Shop Now</a>
</body>
</html>


   
  </header>
</body>

	<style>
		body {
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
		}
		
		header {
			background-color: #ffffff;
			color: #fff;
			padding: 10px;
			text-align: center;
		}
		
		h1 {
			margin: 0;
			font-size: 36px;
		}
		
		nav {
			background-color: #ffffff;
			border: 1px solid #ddd;
			padding: 10px;
		}
		
		nav a {
			display: inline-block;
			padding: 10px;
			text-decoration: none;
			color: #333;
		}
		
		nav a:hover {
			background-color: #ddd;
		}
		
		.container {
			max-width: 1200px;
			margin: 0 auto;
			padding: 20px;
		}
		
		.product {
			display: inline-block;
			width: 300px;
			margin: 20px;
			border: 1px solid #ddd;
			padding: 10px;
			text-align: center;
		}
		
		.product img {
			max-width: 100%;
			height: auto;
			margin-bottom: 10px;
		}
		
		.product h2 {
			margin-top: 0;
			font-size: 24px;
		}
		
		.product p {
			margin: 0;
			font-size: 18px;
			color: #302b2c;
		}
		
		.product button {
			display: black;
			margin: 10px auto;
			padding: 10px 20px;
			background-color: #f21c51;
			color: #000000;
			border: none;
			font-size: 18px;
			cursor: pointer;
		}
		
		.product button:hover {
			background-color: #f21c51;
		}
		
		footer {
			background-color: #f21c51;
			border-top: 1px solid #ddd;
			padding: 10px;
			text-align: center;
			color: #302b2c;
		}
		
		@media (max-width: 768px) {
			.product {
				width: 100%;
			}
		}
	</style>
</head>
<body>
	
</header>
	<nav>
		<a href="#">Home</a>
		<a href="Contact Us.html">Contact Us</a>
		<a href="PC and mobile.html">Products</a>
                <a href="Gallery 2.html">Gallery</a>
                <a href="About Us.html">About Us</a>
                

	</nav>
	
	<style>
    .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }

    .product {
        flex: 1;
        margin: 10px;
        text-align: center;
    }
</style>
<style>
  a.whatsapp {
    color: #ffffff; /* white color code */
  }
</style>
</style>
<style>
  a.whatsapp {
    color: #ffffff; /* white color code */
  }



		.slideshow-container {
			display: flex;
			justify-content: center; /* Center the images horizontally */
			margin-top: 0px; /* Add margin to move the images down */
		}

		.slideshow-image {
			display: none; /* Hide all images by default */
			width: 1900px; /* Increase the width of the images */
			height: auto; /* Let the height adjust proportionally */
		}

		.slideshow-image.active {
			display: block; /* Display the active image */
		}
	</style>
	<script>
		// JavaScript code for slide effect
		window.addEventListener('load', function() {
			const slideshowImages = document.querySelectorAll('.slideshow-image');
			let currentSlide = 0;

			function showSlide(index) {
				if (index < 0) {
					index = slideshowImages.length - 1;
				} else if (index >= slideshowImages.length) {
					index = 0;
				}

				slideshowImages[currentSlide].classList.remove('active');
				slideshowImages[index].classList.add('active');
				currentSlide = index;
			}

			function nextSlide() {
				showSlide(currentSlide + 1);
			}

			setInterval(nextSlide, 5000); // Automatically move to the next slide every 5 seconds
			showSlide(currentSlide); // Show the initial slide
		});
	</script>
</head>
<body>
	<div class="slideshow-container">
		<img class="slideshow-image" src="gallery-image-16.jpg" alt="Image 16">
                <img class="slideshow-image" src="Plastic bottle 600ml New Design.jpg">
		<img class="slideshow-image" src="gallery-image-15.jpg" alt="Image 15">
		<img class="slideshow-image" src="gallery-image-17.jpg" alt="Image 17">
                <img class="slideshow-image" src="gallery-image-18.jpg" alt="Image 18">
	</div>
<style>
		/* Your existing CSS styles here */

		footer {
			background-color: #f21c51;
			border-top: 1px solid #ddd;
			padding: 5px;
			text-align: center;
			color: #fff; /* Set the text color to white */
		}
	</style>
</head>
<body>
	<!-- Your existing website content here -->

	<footer>
		<p>© 2024 Lora Online Shopping Store. All rights reserved.</p>
	</footer>
</body>
</html>

</body>
</html>
