<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>San Joaquin Valley Town Hall</title>
  <link rel="shortcut icon" href="images/favicon.ico">
  <link rel="stylesheet" href="styles/slicknav.css">
  <script src="js/jquery.min.js"></script>
  <script src="js/jquery.slicknav.min.js"></script>
  <style>
    body {
      width: 98%;
      max-width: 960px;
      margin: 0 auto;
      font-family: Arial, sans-serif;
    }

    header {
      background: url("images/town_hall_logo.gif") no-repeat left center, linear-gradient(to right, #f2c779, #f2c779);
      padding: 10px 0;
      padding-left: 10%;
      padding-right: 10%;
      color: #800000;
      text-align: left;
    }

    header h2 {
      margin: 0;
      font-size: 1.8em;
    }

    header h3 {
      margin: 0;
      font-size: 1.2em;
      font-style: italic;
    }

    .shadow {
      font-weight: bold;
    }

    nav#nav_menu {
      background-color: #800000;
      position: relative;
    }

    nav#nav_menu ul {
      list-style: none;
      margin: 0;
      padding: 0;
    }

    nav#nav_menu li {
      float: left;
      position: relative;
      width: 20%;
    }

    nav#nav_menu li a {
      display: block;
      text-align: center;
      padding: 1em;
      text-decoration: none;
      background-color: #800000;
      color: white;
      font-weight: bold;
    }

    nav#nav_menu li a.current {
      color: yellow;
    }

    nav#nav_menu li ul {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      background-color: #800000;
      width: 100%;
    }

    nav#nav_menu li ul li {
      float: none;
    }

    nav#nav_menu li:hover ul {
      display: block;
    }

    nav#nav_menu::after {
      content: "";
      display: block;
      clear: both;
    }

    main {
      overflow: hidden;
    }

    section {
      width: 65%;
      float: left;
      padding: 0 2% 20px 2%;
    }

    aside {
      width: 28%;
      float: right;
      padding: 0 2% 20px 2%;
    }

    section h2,
    aside h2 {
      color: #800000;
    }

    section h1,
    aside h1 {
      font-size: 150%;
      padding-top: 0.5em;
      padding-bottom: 0.25em;
      margin: 0;
    }

    article img {
      float: right;
      margin: 10px 0 10px 10px;
      border: 1px solid black;
      max-width: 40%;
      min-width: 150px;
      height: auto;
    }

    ul {
      list-style-type: circle;
    }

    footer {
      clear: both;
      text-align: center;
      background-color: #800000;
      color: white;
      padding: 10px;
      font-size: small;
    }

    /* Hide mobile nav by default */
    #mobile_menu {
      display: none;
    }

    /* First Breakpoint */
    @media screen and (max-width: 800px) {
      aside h2 a {
        font-size: 85%;
      }

      section h1 {
        font-size: 125%;
      }

      section h2,
      aside h2 {
        font-size: 110%;
      }
    }

    /* Second Breakpoint */
    @media screen and (max-width: 600px) {
      header {
        background: linear-gradient(to right, #f2c779, #f2c779);
        text-align: center;
        padding-left: 0;
      }

      section,
      aside {
        float: none;
        width: 96%;
        margin: auto;
        padding: 2%;
      }

      article img {
        max-width: 30%;
      }

      aside div {
        column-count: 2;
      }

      nav#nav_menu {
        display: none;
      }

      #mobile_menu {
        display: block;
      }

      .slicknav_menu {
        background-color: #800000 !important;
      }
    }

    /* Smallest screens */
    @media screen and (max-width: 480px) {
      body {
        font-size: 90%;
      }
    }
  </style>
  <script>
    $(document).ready(function () {
      $('#nav_menu > ul').slicknav({
        prependTo: "#mobile_menu"
      });
    });
  </script>
</head>
<body>
  <header>
    <h2>San Joaquin Valley Town Hall</h2>
    <h3>Celebrating our <span class="shadow">75<sup>th</sup></span> Year</h3>
  </header>

  <!-- Mobile Menu Container -->
  <nav id="mobile_menu"></nav>

  <!-- Main Navigation -->
  <nav id="nav_menu">
    <ul>
      <li><a href="index.html" class="current">Home</a></li>
      <li><a href="#">Speakers</a></li>
      <li><a href="#">Luncheons</a></li>
      <li><a href="#">Tickets</a></li>
      <li><a href="#">About Us</a>
        <ul>
          <li><a href="#">Our History</a></li>
          <li><a href="#">Board of Directors</a></li>
          <li><a href="#">Past Speakers</a></li>
          <li><a href="#">Contact Information</a></li>
        </ul>
      </li>
    </ul>
  </nav>

  <main>
    <section>
      <h1>Welcome</h1>
      <article>
        <img src="images/anderson.jpg" alt="M.T. Anderson">
        <p>M.T. Anderson is the author of several celebrated books including *Feed*, a satirical novel set in a future where people connect to the internet via brain implants, and *The Astonishing Life of Octavian Nothing*, winner of the National Book Award. His work spans multiple genres and audiences, from young adults to historical fiction.</p>
      </article>
    </section>
    <aside>
      <h1>Upcoming Events</h1>
      <div>
        <h2><a href="#">Oct 15 – M.T. Anderson</a></h2>
        <p><em>Author of Feed and National Book Award winner.</em></p>
        <h2><a href="#">Nov 12 – Jane Smith</a></h2>
        <p><em>Renowned climate scientist and speaker.</em></p>
      </div>
    </aside>
  </main>

  <footer>
    &copy; 2025 San Joaquin Valley Town Hall. All rights reserved.
  </footer>
</body>
</html>
