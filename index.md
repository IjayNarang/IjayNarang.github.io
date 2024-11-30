<html>
<head>
  <title>Ijay Narang</title>
  <meta http-equiv="content-type" content="text/html; charset=utf-8" />
  <meta name="description" content="" />
  <meta name="keywords" content="" />
  <link href="css/fonts.css" rel="stylesheet" type="text/css" />
  <link rel="stylesheet" href="css/bootstrap.min.css" />
  <link rel="stylesheet" href="css/bootstrap-theme.min.css" />
  <link rel="stylesheet" href="css/style.css" />
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" rel="stylesheet">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
  <script src="http://netdna.bootstrapcdn.com/bootstrap/3.1.1/js/bootstrap.min.js"></script>
  <style>
    /* Sidebar styling */
    #sidebar {
      position: relative;
      width: 250px;
      height: 100%;
      background: #f8f9fa;
      padding: 20px;
      border-right: 1px solid #ddd;
      flex-shrink: 0;
      overflow-y: auto;
    }

    #main-content {
      flex-grow: 1;
      padding: 20px;
    }

    #logo img {
      width: 100%;
      height: auto;
      max-width: 110px;
      margin: 0 auto;
      display: block;
    }

    #logo h1, #logo .byline {
      text-align: center;
    }

    nav .list-group-item {
      margin-bottom: 10px;
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 5px;
      padding: 10px 15px;
      font-size: 16px;
      display: flex;
      align-items: center;
    }

    nav .list-group-item i {
      margin-right: 10px;
    }

    /* Flex container for layout */
    .flex-container {
      display: flex;
      flex-direction: row;
      min-height: 100vh; /* Full height for the container */
    }

    /* Adjustments for smaller screens */
    @media (max-width: 768px) {
      .flex-container {
        flex-direction: column;
      }

      #sidebar {
        width: 100%;
        border-right: none;
        border-bottom: 1px solid #ddd;
      }

      #main-content {
        margin-left: 0;
      }
    }
  </style>
</head>
<body>
  <div class="flex-container">
    <!-- Sidebar -->
    <div id="sidebar">
      <div id="logo" class="clearfix">
        <span class="image"><img src="profile_pic.PNG" alt="Me" class="img-circle" /></span>
        <h1 id="title">Ijay Narang</h1>
      </div>
      <div id="logo" class="clearfix">
        <span class="byline">in5787_at_princeton.edu</span>
        <span class="byline">ijay.narang_at_gmail.com</span>
      </div>
      <nav>
        <div class="list-group">
          <a href="#pubs" class="list-group-item">
            <i class="fa-solid fa-file"></i><span>Publications</span>
          </a>
          <a href="#talks" class="list-group-item">
            <i class="fa-solid fa-circle-play"></i><span>Talks</span>
          </a>
          <a href="#teach" class="list-group-item">
            <i class="fa-solid fa-graduation-cap"></i><span>Teaching</span>
          </a>
          <a href="#projects" class="list-group-item">
            <i class="fa-solid fa-toolbox"></i><span>Projects</span>
          </a>
          <a href="#about" class="list-group-item">
            <i class="fa-solid fa-user"></i><span>About Me</span>
          </a>
        </div>
      </nav>
    </div>

    <!-- Main Content -->
    <div id="main-content">
      <div class="container-fluid">
        <div class="row">
          <div id="main" class="col-md-12">
            <section>
              <p>I'm a Senior at <a href="http://cs.princeton.edu" target="_blank">Princeton University</a> in the Department of Computer Science.</p>
              <p>My primary research interest is in <strong>Theoretical Computer Science</strong>. In particular I am interested in: <br />
                <u>Spectral Graph Theory</u>, <u>Coding Theory</u>, <u>Combinatorics</u>, and <u>Optimization</u>. I am fortunate to be advised by Dr. Pedro Paredes and Dr. Noga Alon.</p>
              <h3 id="pubs">Research</h3>
              <ul>
                <li><strong>Expanding Square Complexes from Graph Products</strong>, Junior Thesis (Advised by Dr. Pedro Paredes), Giving Talk at Duke University Math Conference
                  <a href="works/expanding_square_complexes_from_graph_products.pdf" target="_blank"> [View Paper Here] </a></li>
                <li><strong>An Overview of Utilizing Expanders to enhance Error-Correcting Codes</strong>
                  <a href="works/survey_on_expanders_in_coding_theory.pdf" target="_blank"> [View Paper Here] </a></li>
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
                <li>
                  <strong>Compass:</strong> all-in-one Princeton University course planning app -- now reached 700+ users!
                  The application is currently being maintained by Hoagie Club and (has thus) been renamed to HoagiePlan.
                  <a href="https://pucompass.com/" target="_blank">See the App Here</a>
                </li>
              </ul>
              <h3 id="about">About Me</h3>
              <p>Outside of math + CS, I enjoy lifting and playing basketball + chess.</p>
            </section>
          </div>
        </div>
        <div class="row">
          <div class="col-md-12 footer">
            <footer>
              <div class="copyright">
                <p>&copy; 2024 Ijay Narang (Last Update: 10/31/2024)</p>
              </div>
            </footer>
          </div>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
