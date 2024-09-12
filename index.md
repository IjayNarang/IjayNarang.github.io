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
      /* Additional custom styling for sidebar */
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
        margin-left: 270px; /* adjust according to sidebar width */
        padding: 20px;
      }

      #logo img {
        width: 100%;
        height: auto;
        max-width: 110px;
      }

      #logo h1, #logo .byline {
        text-align: center;
      }

      nav .list-group-item {
        margin-bottom: 10px;
        background-color: #fff;
        border: 1px solid #ddd;
        border-radius: 5px;
      }

      nav .list-group-item i {
        margin-right: 10px;
      }
    </style>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
    <script src="http://netdna.bootstrapcdn.com/bootstrap/3.1.1/js/bootstrap.min.js"></script>
  </head>
  <body>
    <div id="sidebar">
      <!-- Left Pane -->
      <div id="logo" class="clearfix">
        <span class="image"><img src="images/photo01.jpg" alt="Me" class="img-circle" /></span>
        <h1 id="title">Ijay Narang</h1>
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

    <!-- Main Content -->
    <div id="main-content">
      <div class="container">
        <div class="row">
          <!-- Body -->
          <div id="main" class="col-md-12">
            <!-- Intro -->
            <section>
              <header>
                <h2 class="alt">I'm <strong>Pedro Paredes</strong> from <a href="http://cs.princeton.edu" target="_blank" >Princeton University</a></h2>
              </header>	  
              <p>I'm a Teaching Professor at <a href="http://cs.princeton.edu" target="_blank">Princeton University</a> in the Department of Computer Science.</p>

              <p>My primary research interest is in <strong>Theoretical Computer Science</strong>. In particular I am interested in: <br /> <u>Spectral Graph Theory</u>, <u>Pseudorandomness</u>, <u>Coding Theory</u>, <u>Combinatorics</u>, <u>Quantum Information Theory</u>.</p>

              <h3 id="pubs">Publications</h3>
              <ul>
                <li>Publication 1</li>
                <li>Publication 2</li>
                <li>Publication 3</li>
              </ul>

              <h3 id="talks">Talks</h3>
              <ul>
                <li>Talk 1</li>
                <li>Talk 2</li>
                <li>Talk 3</li>
              </ul>

              <h3 id="teach">Teaching</h3>
              <ul>
                <li>Course 1</li>
                <li>Course 2</li>
                <li>Course 3</li>
              </ul>

              <h3 id="projects">Projects</h3>
              <ul>
                <li>Project 1</li>
                <li>Project 2</li>
                <li>Project 3</li>
              </ul>

              <h3 id="about">About Me</h3>
              <p>Short description about me.</p>
            </section>
          </div>
        </div>

        <div class="row">
          <div class="col-md-12 footer">
            <!-- Footer -->
            <footer>
              <!-- Copyright -->
              <div class="copyright">
                <p>&copy; 2024 Pedro Paredes (Last Update: 02/23/2024)</p>
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
