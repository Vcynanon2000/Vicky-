<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Home</title>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="css/screen.css" />
  </head>
  <!-- CSS only -->
  <script src="js/clock.js"></script>
  <body onload="startTime()">
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx"
      crossorigin="anonymous"
    />

    <header class="bg-dark" style="position: relative; width: 100%">
      <div class="bg-dark py-4 text-light">
        <div class="container">
          <h1>(n.) Happines</h1>
          <p class="hide-small">Vicky Hermawan</p>
          <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container-fluid">
              <button
                class="navbar-toggler"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#navbarText"
                aria-controls="navbarText"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarText">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a
                      class="nav-link active"
                      aria-current="page"
                      href="index.html"
                      >Home</a
                    >
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="about.html">About</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="article.html">Article</a>
                  </li>
                </ul>
                <span class="navbar-text"
                  >it's about how u appreciate your moments</span
                >
                &ensp; &ensp;
                <span id="clock"></span>
              </div>
            </div>
          </nav>
        </div>
      </div>
    </header>
    <section style="height: 100vh; background-color: rgb(73, 81, 150)">
      <div class="row div-in-section">
        <div class="col-4">
          <h1 class="teks-section transition" style="animation-delay: 0s">
            Welcome Home<3
          </h1>
          <br />
          <h3 class="bot-trans" style="animation-delay: 0.4s">
            Know Your Worth
          </h3>
          <h4 class="transition" style="animation-delay: 0.8s">
            If u want to see more, go to
            <a href="about.html" style="color: black">About</a> or
            <a href="article.html" style="color: black">Article</a>
          </h4>
        </div>
      </div>
    </section>
  </body>
</html>
