# Nature Photography Website Code of Conduct

## Our Commitment

As contributors and users of this nature photography website, we are committed to creating a welcoming and respectful environment for everyone. We embrace diversity and inclusion and aim to foster a positive community that appreciates and celebrates the beauty of nature through photography.

## Our Standards

Examples of behavior that contribute to our positive community include:

- Respecting and valuing the opinions and experiences of others.
- Encouraging constructive and supportive feedback on nature photographs.
- Sharing knowledge and insights about nature photography techniques and conservation.
- Engaging in discussions with kindness, empathy, and open-mindedness.
- Giving proper credit to photographers and sources when using or sharing their images.

Examples of unacceptable behavior include:

- Harassment, discrimination, or bullying based on any personal characteristics or beliefs.
- Posting or sharing explicit, offensive, or harmful content related to nature or individuals.
- Engaging in activities that may harm or disturb wildlife or natural habitats for the sake of photography.
- Violating copyright or intellectual property rights of photographers or content creators.

## Our Responsibilities

As website administrators and maintainers, we are responsible for enforcing these standards. We have the right to remove, edit, or reject any content or contributions that do not align with this Code of Conduct. We may also temporarily or permanently ban any user or contributor for behaviors we find inappropriate, harmful, or disruptive to our community.

## Scope

This Code of Conduct applies to all interactions within the nature photography website, including discussions, comments, photo submissions, and other contributions.

## Enforcement

If you encounter any instances of abusive, harassing, or unacceptable behavior, please report it to the website administrators at fatima2mushtaq@gmail.com. All reports will be reviewed and handled with the utmost discretion and seriousness. We are committed to creating a safe and inclusive environment for all users.
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Photography Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
color: #333;
      padding: 0;
background-color:  #E6F1F8;
    }
    header {
      background-color: #F8D7E9;
      padding: 20px;
      color: #fff;
      text-align: center;
    }
    nav {
      background-color: #f5f5f5;
      padding: 10px 0;
      text-align: center;
    }
    nav a {
      text-decoration: none;
      color: #333;
      margin: 0 10px;
    }
    section {
      padding: 50px;
    }
    h2 {
      color: #333;
    }
    footer {
      background-color: #F8D7E9;;
      padding: 20px;
      color: #fff;
      text-align: center;
    }
    .image-container {
      text-align: center;
      margin-bottom: 20px;
    }
    .image-container img {
      max-width: 100%;
      width: 200px; /* Adjust the width as desired */
      height: 200px; /* Adjust the height as desired */
    }
    #about {
      min-height: 400px; /* Adjust the minimum height as desired */
      min-width: 600px; /* Adjust the minimum width as desired */
    }
.scroll-to-top {
      position: fixed;
      bottom: 20px;
      right: 20px;
      width: 50px;
      height: 50px;
      background-color: #00FF00;
      color: #fff;
      border-radius: 50%;
      text-align: center;
      line-height: 50px;
      cursor: pointer;
backgroung:green;
      display: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Photography Website</h1>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="about">
    <h2>About</h2>
    <div class="image-container">
      <img src="about_image.jpg" alt="Photographer" width="200" height="200">
    </div>
    <p>Welcome to the Photography Website, where we capture precious moments and create stunning visual stories. Our team of professional photographers is dedicated to preserving your special memories with exceptional artistry and expertise. From weddings to landscapes, we strive to deliver breathtaking images that speak to your soul.</p>
  </section>
  <section id="portfolio">
  <h2>Portfolio</h2>
  <div class="image-container">
    <img src="image1.jpg" alt="Photo 1" width="200" height="200">
    <p>Beautiful sunset at the beach.</p>
  </div>
  <div class="image-container">
    <img src="image2.jpg" alt="Photo 2" width="200" height="200">
    <p>Colorful flowers in a garden.</p>
  </div>
  <div class="image-container">
    <img src="image3.jpg" alt="Photo 3" width="200" height="200">
    <p>Majestic mountain peak covered in snow.</p>
  </div>
</section>

  </section>
  <section id="contact">
    <h2>Contact</h2>
    <p>If you would like to discuss your photography needs or have any inquiries, please reach out to us:</p>
    <p>Email: info@photographywebsite.com</p>
    <p>Phone: 123-456-7890</p>
  </section>
  <footer>
    <p>&copy; 2023 Photography Website</p>
  </footer>
  <div class="scroll-to-top" onclick="scrollToTop()">
    <span>&uarr;</span>
  </div>

  <script>
    window.addEventListener('scroll', function() {
      var scrollButton = document.querySelector('.scroll-to-top');
      if (window.scrollY > 300) {
        scrollButton.style.display = 'block';
      } else {
        scrollButton.style.display = 'none';
      }
    });

    function scrollToTop() {
      window.scrollTo({
        top: 0,
        behavior: 'smooth'
      });
    }
  </script>
</body>
</html>

