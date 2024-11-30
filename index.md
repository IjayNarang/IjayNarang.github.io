<html>
<head>
  <title>Ijay Narang</title>
  <meta http-equiv="content-type" content="text/html; charset=utf-8" />
  <meta name="description" content="" />
  <meta name="keywords" content="" />
  <link href="css/fonts.css" rel="stylesheet" type="text/css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

  <style>
    /* Flexbox container for responsiveness */
    .flex-container {
      display: flex;
      flex-wrap: nowrap;
      min-height: 100vh;
    }

    /* Sidebar styling */
    #sidebar {
      flex: 1 1 20%;
      background: #f8f9fa;
      padding: 20px;
      border-right: 1px solid #ddd;
      min-width: 200px;
      max-width: 300px;
    }

    #main-content {
      flex: 3 1 80%;
      padding: 20px;
    }

    #logo img {
      width: 100%;
      max-width: 150px;
      border-radius: 50%;
      display: block;
      margin: 0 auto;
    }

    #logo h1, #logo .byline {
      text-align: center;
      margin-top: 10px;
    }

    nav .list-group {
      margin-top: 20px;
    }

    nav .list-group-item {
      margin-bottom: 10px;
      font-size: 16px;
    }

    nav .list-group-item i {
      margin-right: 10px;
    }

    /* Mobile-first adjustments */
    @media (max-width: 768px) {
      .flex-container {
        flex-direction: column;
      }

      #sidebar {
        border-right: none;
        border-bottom: 1px solid #ddd;
        min-width: 100%;
        max-width: 100%;
      }

      #main-content {
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <div class="flex-container">
    <!-- Sidebar -->
    <div id="sidebar">
      <div id="logo">
        <img src="profile_pic.PNG" alt="Me" />
        <h1>Ijay Narang</h1>
        <p class="byline">in5787_at_princeton.edu</p>
        <p class="byline">ijay.narang_at_gmail.com</p>
      </div>
      <nav>
        <div class="list-group">
          <a href="#pubs" class="list-group-item list-group-item-action">
            <i class="fa-solid fa-file"></i>Publications
          </a>
          <a href="#talks" class="list-group-item list-group-item-action">
            <i class="fa-solid fa-circle-play"></i>Talks
          </a>
          <a href="#teach" class="list-group-item list-group-item-action">
            <i class="fa-solid fa-graduation-cap"></i>Teaching
          </a>
          <a href="#projects" class="list-group-item list-group-item-action">
            <i class="fa-solid fa-toolbox"></i>Projects
          </a>
          <a href="#about" class="list-group-item list-group-item-action">
            <i class="fa-solid fa-user"></i>About Me
          </a>
        </div>
      </nav>
    </div>

    <!-- Main Content -->
    <div id="main-content">
      <p>I'm a Senior at <a href="http://cs.princeton.edu" target="_blank">Princeton University</a> in the Department of Computer Science.</p>
      <p>My primary research interest is in <strong>Theoretical Computer Science</strong>. In particular, I am interested in:
        <br><u>Spectral Graph Theory</u>, <u>Coding Theory</u>, <u>Combinatorics</u>, and <u>Optimization</u>. I am fortunate to be advised by Dr. Pedro Paredes and Dr. Noga Alon.</p>

      <h3 id="pubs">Research</h3>
      <ul>
        <li><strong>Expanding Square Complexes from Graph Products</strong>, Junior Thesis (Advised by Dr. Pedro Paredes), Giving Talk at Duke University Math Conference
          <a href="works/expanding_square_complexes_from_graph_products.pdf" target="_blank">[View Paper Here]</a></li>
        <li><strong>An Overview of Utilizing Expanders to Enhance Error-Correcting Codes</strong>
          <a href="works/survey_on_expanders_in_coding_theory.pdf" target="_blank">[View Paper Here]</a></li>
      </ul>

      <h3 id="talks">Talks</h3>
      <ul>
        <li><strong>Duke University Math Conference</strong>, Talk titled: <em>Expanding Square Complexes from Graph Products</em>
          <a href="https://math.duke.edu/research/research-grants/research-training-group/undergrad/undergrad-symposium24" target="_blank">[Details]</a></li>
      </ul>

      <h3 id="teach">Teaching</h3>
      <ul>
        <li>Fall 2024: UCA for COS 326 (Functional Programming) and Lab TA for COS 240 (Intro to TCS)</li>
        <li>Spring 2024: Lab TA for COS 240 and Grader for COS 445 (Algorithmic Game Theory)</li>
        <li>Spring 2023: COS 445 Grader</li>
        <li>Fall 2022: COS 445 Grader</li>
        <li>Spring 2022: COS 126 (Intro to Programming) Grader</li>
      </ul>

      <h3 id="projects">Projects</h3>
      <ul>
        <li><strong>Compass:</strong> all-in-one Princeton University course planning app -- now reached 700+ users!
          The application is currently being maintained by Hoagie Club and renamed to HoagiePlan.
          <a href="https://pucompass.com/" target="_blank">See the App Here</a>
        </li>
      </ul>

      <h3 id="about">About Me</h3>
      <p>Outside of math + CS, I enjoy lifting and playing basketball + chess.</p>
    </div>
  </div>

  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
