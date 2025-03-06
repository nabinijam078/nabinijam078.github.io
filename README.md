<!DOCTYPE html>
<html>
  <head>
    <title>My Portfolio</title>
    <style>
      /* General Styles */
      body {
        background-color: #f4f4f4;
        font-family: 'Arial', sans-serif;
        margin: 0;
        padding: 0;
        line-height: 1.6;
      }

      /* Header Styles */
      h1 {
        background-color: #0078d7;
        color: white;
        text-align: center;
        padding: 20px;
        margin: 0;
        font-size: 28px;
        font-weight: bold;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      }

      /* Navigation Bar Styles */
      nav {
        background-color: #333;
        padding: 10px;
        text-align: center;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      }

      nav a {
        color: white;
        text-decoration: none;
        padding: 10px 15px;
        margin: 0 5px;
        font-size: 16px;
        border-radius: 5px;
        transition: background-color 0.3s ease;
      }

      nav a:hover {
        background-color: #0078d7;
      }

      /* Content Styles */
      .content {
        max-width: 1200px;
        margin: 20px auto;
        padding: 20px;
        background-color: white;
        border-radius: 10px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      }

      img {
        float: right;
        margin: 0 0 20px 20px;
        border-radius: 10px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        width: 300px;
        height: auto;
      }

      p {
        font-size: 16px;
        color: #333;
        text-align: justify;
      }

      p b {
        color: #0078d7;
      }

      /* Footer Styles */
      footer {
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        background-color: #333;
        color: white;
        text-align: center;
        padding: 10px;
        font-size: 12px;
        box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.1);
      }

      footer p {
        margin: 0;
        color: white;
      }

      /* Responsive Design */
      @media (max-width: 768px) {
        img {
          float: none;
          display: block;
          margin: 0 auto 20px;
        }

        nav a {
          display: block;
          margin: 10px 0;
        }
      }
    </style>
  </head>
  <body>
    <h1>WELCOME TO MY PORTFOLIO</h1>

    <!-- Navigation Bar -->
    <nav>
      <a href="Home.html"><b>HOME</b></a>
      <a href="My background.html"><b>MY BACKGROUND</b></a>
      <a href="Civil Engineering Notes.html"><b>CIVIL ENGINEERING NOTES</b></a>
      <a href="Others.html"><b>OTHERS</b></a>
      <a href="Downloads.html"><b>DOWNLOADS</b></a>
      <a href="images.html"><b>IMAGES</b></a>
      <a href="Contacts.html"><b>CONTACTS</b></a>
    </nav>

    <!-- Main Content -->
    <div class="content">
      <img src="unnamed.jpg" alt="Nabin Kumar Ijam">
      <p>This is my personal website. In this website, you can know my personal information, my work, and some Civil Engineering information.</p>
      <p>I am <b>Nabin Kumar Ijam</b>. I am from Nepal and currently working in Malaysia. I am professionally a Civil Engineer. I am mainly specialized in Structural Engineering and Hydropower Engineering. My specializations are in structural design of hydraulic structures, buildings, and steel structures. I have deep knowledge of Concrete design based on Indian Standard, British Standard, Euro codes, and ACI.</p>
      <p>I graduated from <b>Saitama University</b>, Japan in 2017, 8 years after the completion of my Bachelor of Civil Engineering from Tribhuvan University, Institute of Engineering, Pulchowk Campus, Pulchowk, Nepal. During these 8 years, I completed one hydropower project when I worked in Sanima Hydropower.</p>
      <p>For more information about me, please visit <a href="My Background.html">My Background</a>.</p>
    </div>

    <!-- Footer -->
    <footer>
      <p><i>Copyright © Nabin Kumar Ijam</i></p>
    </footer>
  </body>
</html>
