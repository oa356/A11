<html lang="en">

<head>
  <meta charset="utf-8">
  <title>San Joaquin Valley Town Hall</title>
  <link rel="shortcut icon" href="images/favicon.ico">
  <style>
    body {
      width: 800px;
      margin: 0 auto;
      font-family: Arial, sans-serif;
    }

    header {
      background: url("images/town_hall_logo.gif") no-repeat left center, linear-gradient(to right, #f2c779, #f2c779);
      padding: 10px 0 10px 90px;
      color: #800000;
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
    }

    nav#nav_menu li a {
      display: block;
      width: 160px;
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
      width: 160px;
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
      width: 525px;
      float: right;
      padding: 0 20px 20px 20px;
    }

    aside {
      width: 215px;
      float: right;
      padding: 0 0 20px 20px;
    }

    section h2, aside h2 {
      color: #800000;
    }

    section h1, aside h1 {
      font-size: 150%;
      padding-top: 0.5em;
      padding-bottom: 0.25em;
      margin: 0;
    }

    article img {
      float: right;
      margin: 10px 0 10px 10px;
      border: 1px solid black;
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
  </style>
</head>

<body>
  <header>
    <h2>San Joaquin Valley Town Hall</h2>
    <h3>Celebrating our <span class="shadow">75<sup>th</sup></span> Year</h3>
  </header>

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
      <h2>Our Mission</h2>
      <p>San Joaquin Valley Town Hall is a non-profit organization that is run by an 
         all-volunteer board of directors. Our mission is to bring nationally and 
         internationally renowned, thought-provoking speakers who inform, educate, 
         and entertain our audience! As one or our members told us:</p>
      <blockquote>&ldquo;Each year I give a ticket package to each of our family members. 
        I think of it as the gift of knowledge...and that is priceless.&rdquo;</blockquote>

      <h1>Speaker of the Month</h1>
      <article>
        <h2>Fossil Threads in the Web of Life</h2>
        <img src="images/sampson_dinosaur.jpg" alt="Scott Sampson with dinosaur" width="200">
        <h3>February<br>
          Scott Sampson</h3>
        <p>What's 75 million years old and brand spanking new? A teenage Utahceratops! 
          Come to the Saroyan, armed with your best dinosaur roar, when Scott Sampson, Research 
          Curator at the Utah Museum of Natural History, steps to the podium. Sampson's research 
          has focused on the ecology and evolution of late Cretaceous dinosaurs and he has conducted 
          fieldwork in a number of countries in Africa.</p>
        <p><a href="speakers/c6_sampson.html">Read more.</a>&nbsp;<b>Or meet us there!</b></p>
      </article>

      <h2>Our Ticket Packages</h2>
      <ul>
        <li>Season Package: $95</li>
        <li>Patron Package: $200</li>
        <li>Single Speaker: $25</li>
      </ul>
    </section>

    <aside>
      <h2>Guest speakers</h2>
      <h3>October<br><a href="speakers/brancaccio.html">David Brancaccio</a></h3>
      <img src="images/brancaccio75.jpg" alt="David Brancaccio photo">
      <h3>November<br><a href="speakers/sorkin.html">Andrew Ross Sorkin</a></h3>
      <img src="images/sorkin75.jpg" alt="Andrew Ross Sorkin photo">
      <h3>January<br><a href="speakers/chua.html">Amy Chua</a></h3>
      <img src="images/chua75.jpg" alt="Amy Chua photo">
      <h3>February<br><a href="speakers/c6_sampson.html">Scott Sampson</a></h3>
      <img src="images/sampson75.jpg" alt="Scott Sampson photo">
    </aside>
  </main>

  <footer>
    <p>&copy; Olumuyiwa Akinde, oa356, 2025 </p>
  </footer>
</body>
</html>
