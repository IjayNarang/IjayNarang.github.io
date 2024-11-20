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
    <style>
      /* Sidebar styling */
      #sidebar {
        position: fixed;
        top: 0;
        left: 0;
        width: 250px;
        height: 100%;
        background: #f8f9fa;
        padding: 20px;
        overflow-y: auto;
        border-right: 1px solid #ddd;
      }

      #main-content {
        margin-left: 10px; /* Adjust according to sidebar width */
        padding: 20px;
      }

      #logo img {
        width: 100%;
        height: auto;
        max-width: 110px;
        margin: 0 auto; /* Center the image */
        display: block; /* Make it block-level to apply auto margins */
      }

      #logo h1, #logo .byline {
        text-align: center;
      }

      nav .list-group {
        display: flex;
        flex-direction: column;
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
        justify-content: flex-start;
      }

      nav .list-group-item i {
        margin-right: 10px;
      }

      /* Content section styling */
      h3 {
        border-bottom: 1px solid #ddd;
        padding-bottom: 10px;
        margin-top: 30px;
      }

      section {
        margin: 0;
      }

      section p {
        font-size: 16px;
        line-height: 1.6;
        margin: 0 0 20px 0;
      }

      section ul {
        padding-left: 20px;
        margin: 0;
      }

      section ul li {
        margin-bottom: 10px;
      }
    </style>


  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
  <script src="http://netdna.bootstrapcdn.com/bootstrap/3.1.1/js/bootstrap.min.js"></script>
  </head>
  <body>
    <div id="sidebar">
      <!-- Profile Pic -->
      <div id="logo" class="clearfix">
        <span class="image"><img src="profile_pic.PNG" alt="Me" class="img-circle" /></span>
        <h1 id="title">Ijay Narang</h1>
      </div>

      <!-- Emailz -->

      <div id="logo" class="clearfix">
        <span class="byline">in5787_at_princeton.edu</span>
        <span class="byline">ijay.narang_at_gmail.com</span>
      </div>


      <!-- Nav -->
      <nav>
        <div class="list-group">
          <a href="#pubs" class="list-group-item"><i class="fa-solid fa-file"></i><span>Publications</span></a>
          <a href="#talks" class="list-group-item"><i class="fa-solid fa-circle-play"></i><span>Talks</span></a>
          <a href="#teach" class="list-group-item"><i class="fa-solid fa-graduation-cap"></i><span>Teaching</span></a>
          <a href="#projects" class="list-group-item"><i class="fa-solid fa-toolbox"></i><span>Projects</span></a>
          <a href="#about" class="list-group-item"><i class="fa-solid fa-user"></i><span>About Me</span></a>
        </div>
      </nav>
    </div>

    

    <style>
      .custom-separator {
        border: 0;
        border-top: 1px solid #ddd;
        margin: 20px 0; /* Adjusts space above and below the separator */
      }
    
      .list-group {
        margin-top: 30px; /* Adds space between the separator and the buttons */
      }
    </style>
    

    <!-- Main Content -->
    <div id="main-content">
      <div class="container-fluid">
        <div class="row">
          <!-- Body -->
          <div id="main" class="col-md-12">
            <!-- Intro -->
            <section>  
              <p>I'm a Senior at <a href="http://cs.princeton.edu" target="_blank">Princeton University</a> in the Department of Computer Science.</p>

              <p>My primary research interest is in <strong>Theoretical Computer Science</strong>. In particular I am interested in: <br /> <u>Spectral Graph Theory</u>, <u>Coding Theory</u>, <u>Combinatorics</u>, and <u>Optimization</u>. I am fortunate to be advised by Dr. Pedro Paredes and Dr. Noga Alon.</p>

              <h3 id="pubs">Research</h3>
              <ul>
                <li><strong>Expanding Square Complexes from Graph Products</strong>, Junior Thesis (Advised by Dr. Pedro Paredes), Giving Talk at Duke University Math Conference <a href="works/expanding_square_complexes_from_graph_products.pdf" target="_blank"> [View Paper Here] </a></li>
                
                <li><strong>An Overview of Utilizing Expanders to enhance Error-Correcting Codes</strong><a href="works/survey_on_expanders_in_coding_theory.pdf" target="_blank">  [View Paper Here] </a></li>
              </ul>

              <h3 id="talks">Talks</h3>
              <ul>
                <li> <strong> Duke University Math Conference</strong>, Talk titled: <em>Expanding Square Complexes from Graph Products </em> <a  href = "https://math.duke.edu/research/research-grants/research-training-group/undergrad/undergrad-symposium24" target= "_blank">   [Details] </a></li>
              </ul>

              <h3 id="teach">Teaching</h3>
              <ul>
                <li>Fall 2024: UCA for <a href="https://www.cs.princeton.edu/courses/archive/fall24/cos326/info.php" target="_blank">COS 326</a> (Functional Programming) and Lab TA for <a href="https://www.cs.princeton.edu/courses/archive/fall24/cos240/" target="_blank">COS 240 </a>(Intro to TCS)</li>
                <li>Spring 2024: Lab TA for COS 240 and Grader for COS 445 (Algorithmic Game Theory) </li>
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
              <p> Outside of math + CS, I enjoy lifting and playing basketball + chess.</p>
            </section>
          </div>
        </div>

        <div class="row">
          <div class="col-md-12 footer">
            <!-- Footer -->
            <footer>
              <!-- Copyright -->
              <div class="copyright">
                <p>&copy; 2024 Ijay Narang (Last Update: 10/31/2024)</p>
              </div>
            </footer>
          </div>
        </div>
      </div>
    </div>

    <script>
      const tooltipTriggerList = document.querySelectorAll('[data-bs-toggle="tooltip"]')
      const tooltipList = [...tooltipTriggerList].map(tooltipTriggerEl => new bootstrap.Tooltip(tooltipTriggerEl))
    </script>
  </body>
</html>
