<!DOCTYPE html>
<html lang="en">

<head>
  <title>devfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="icon" href="favicon.png" type="image/x-icon">
  <link rel="stylesheet" href="css/main.bundle.css">
  <script src="https://kit.fontawesome.com/4e5a72c756.js"></script>
</head>

<body>
  <nav class="navbar is-primary" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <div class="navbar-item is-hidden-desktop">
        <a href="https://github.com/mmacneil" class="icon is-large has-text-light">
          <i class="fab fa-2x fa-github"></i>
        </a>
      </div>
      <div class="navbar-item is-hidden-desktop">
        <a href="https://fullstackmark.com" class="icon is-large has-text-light">
          <i class="fas fa-2x fa-globe"></i>
        </a>
      </div>
    </div>
    <div class="navbar-menu">
      <div class="navbar-end">
        <div class="navbar-item">
          <a href="https://github.com/mmacneil" class="icon is-large has-text-light">
            <i class="fab fa-2x fa-github"></i>
          </a>
        </div>
        <div class="navbar-item">
          <a href="https://fullstackmark.com" class="icon is-large has-text-light">
            <i class="fas fa-2x fa-globe"></i>
          </a>
        </div>
      </div>
    </div>
  </nav>

  <section class="hero is-primary">
    <div class="hero-body">
      <div class="container">
        <div class="level">
          <div class="level-item has-text-centered">

          </div>
        </div>
        <div class="columns has-text-centered">
          <div class="column">
            <h1 class="title is-1">
              Ayça Demirel
            </h1>
            <h2 class="subtitle">
              Designer
            </h2>
            <p>
              <a href="docs/resume.txt" class="icon has-text-light">
                <i class="fas fa-file-word"></i> <strong>Resume</strong>
              </a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <h1 class="title">About Me</h1>
      <hr />
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore
        magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
        pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est
        laborum.</p>
    </div>
  </section>
  <section class="section">
    <div class="container">
      <h1 class="title">Experience</h1>
      <hr />
      <div class="card">
        <div class="card-content">
          <div class="media">
            <div class="media-left">
              <figure class="image is-48x48">
                <img src="img/dunder-mifflin-logo.png" alt="Placeholder image">
              </figure>
            </div>
            <div class="media-content">
              <p class="title is-4">Company Name</p>
              <p class="subtitle is-6">Title - <time datetime="2018-1">January 2018</time> - <time
                  datetime="2019-9">Sepemter 2019</time> </p>
            </div>
          </div>
          <div class="content">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.</p>
            <ul>
              <li>Noteworthy achievment here.</li>
              <li>Noteworthy achievment here.</li>
              <li>Noteworthy achievment here.</li>
            </ul>
            <div class="tags">
              <span class="tag">c#</span>
              <span class="tag">xamarin</span>
              <span class="tag">asp.net core</span>
              <span class="tag">.net core</span>
              <span class="tag">azure</span>
              <span class="tag">devops</span>
            </div>
          </div>
        </div>
      </div>
      <div class="card card-gap">
        <div class="card-content">
          <div class="media">
            <div class="media-left">
              <figure class="image is-48x48">
                <img src="img/pied-piper-logo.png" alt="Placeholder image">
              </figure>
            </div>
            <div class="media-content">
              <p class="title is-4">Company Name</p>
              <p class="subtitle is-6">Title - <time datetime="2018-1">August 2017</time> - <time
                  datetime="2017-9">January 2018</time></p>
            </div>
          </div>
          <div class="content">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.</p>
            <ul>
              <li>Noteworthy achievment here.</li>
              <li>Noteworthy achievment here.</li>
              <li>Noteworthy achievment here.</li>
            </ul>
            <div class="tags">
              <span class="tag">c#</span>
              <span class="tag">xamarin</span>
              <span class="tag">asp.net core</span>
              <span class="tag">.net core</span>
              <span class="tag">azure</span>
              <span class="tag">devops</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <h1 class="title">Projects</h1>
      <hr />
      <div class="tile is-ancestor">
        <div class="tile is-vertical is-12">
          <div class="tile">
            <div class="tile is-parent">
              <article class="tile is-child notification">
                <p class="title">Project title</p>
                <figure class="image is-3by2">
                  <img class="modal-trigger" data-target="project-1-modal" src="img/project-1-cover.png">
                </figure>
              </article>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child notification">
                <p class="title">Project title</p>
                <figure class="image is-4by3">
                  <img class="modal-trigger" data-target="project-2-modal" src="img/project-2-cover.png">
                </figure>
              </article>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child notification">
                <p class="title">Project title</p>
                <figure class="image is-4by3">
                  <img class="modal-trigger" data-target="project-3-modal" src="img/project-3-cover.png">
                </figure>
              </article>
            </div>
          </div>
        </div>
      </div>
      <div class="tile is-ancestor">
        <div class="tile is-vertical is-12">
          <div class="tile">
            <div class="tile is-parent">
              <article class="tile is-child notification">
                <p class="title">Project title</p>
                <figure class="image is-4by3">
                  <img class="modal-trigger" data-target="project-4-modal" src="img/project-4-cover.png">
                </figure>
              </article>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child notification">
                <p class="title">Project title</p>
                <figure class="image is-4by3">
                  <img class="modal-trigger" data-target="project-5-modal" src="img/project-5-cover.png">
                </figure>
              </article>
            </div>
            <div class="tile is-parent">
              <article class="tile is-child notification">
                <p class="title">Project title</p>
                <figure class="image is-4by3">
                  <img class="modal-trigger" data-target="project-6-modal" src="img/project-6-cover.png">
                </figure>
              </article>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <h1 class="title">Education / Training</h1>
      <hr />
      <div class="card">
        <div class="card-content">
          <div class="content">
            <p class="title is-4">School Name</p>
            <p class="subtitle is-6">Program/Course - <time datetime="2016-9">September 2016</time> - <time
                datetime="2019-9">Sepemter 2019</time></p>
          </div>
          <div class="content">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Phasellus nec iaculis mauris.
            <ul>
              <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
              <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="card card-gap">
        <div class="card-content">
          <div class="content">
            <p class="title is-4">School Name</p>
            <p class="subtitle is-6">Program/Course - <time datetime="2015-9">September 2014</time> - <time
                datetime="2015-9">Sepemter 2015</time></p>
          </div>
          <div class="content">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Phasellus nec iaculis mauris.
            <ul>
              <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
              <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <h1 class="title">Contact</h1>
      <hr />
      <nav class="level">
        <div class="level-item has-text-centered">
          <div>
            <a href="https://github.com/mmacneil" class="icon is-large">
              <i class="fab fa-2x fa-github"></i>
            </a>
            <p class="heading"><a href="https://github.com/mmacneil">github.com/mmacneil</a></p>
          </div>
        </div>
        <div class="level-item has-text-centered">
          <div>
            <a href="https://fullstackmark.com" class="icon is-large">
              <i class="fas fa-2x fa-globe"></i>
            </a>
            <p class="heading"><a href="https://fullstackmark.com">fullstackmark.com</a></p>
          </div>
        </div>
        <div class="level-item has-text-centered">
          <div>
            <a href="mailto:markmacneil@gmail.com" class="icon is-large">
              <i class="fas fa-2x fa-envelope"></i>
            </a>
            <p class="heading"><a href="mailto:markmacneil@gmail.com">markmacneil@gmail.com</a></p>
          </div>
        </div>
        <div class="level-item has-text-centered">
          <div>
            <a href="https://www.linkedin.com/in/markmacneilhfx" class="icon is-large">
              <i class="fab fa-2x fa-linkedin-in"></i>
            </a>
            <p class="heading"><a href="https://www.linkedin.com/in/markmacneilhfx">linkedin</a></p>
          </div>
        </div>
      </nav>
    </div>
  </section>

  <!-- Modals -->
  <div id="project-1-modal" class="modal">
    <div class="modal-background"></div>
    <div class="modal-card">
      <header class="modal-card-head">
        <p class="modal-card-title">Project title</p>
        <button class="delete" aria-label="close"></button>
      </header>
      <section class="modal-card-body">

        <div id="project-1-modal-carousel" class="carousel">
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/1.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/2.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/3.png">
          </figure>
        </div>

        <div class="content">

          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
            commodo
            consequat.</p>

          <div class="tags">
            <span class="tag">angular</span>
            <span class="tag">mongo</span>
            <span class="tag">typscript</span>
            <span class="tag">node</span>
          </div>

        </div>

      </section>
      <footer class="modal-card-foot">
        <button class="button is-success">Close</button>
      </footer>
    </div>
  </div>

  <div id="project-2-modal" class="modal">
    <div class="modal-background"></div>
    <div class="modal-card">
      <header class="modal-card-head">
        <p class="modal-card-title">Project title</p>
        <button class="delete" aria-label="close"></button>
      </header>
      <section class="modal-card-body">

        <div id="project-2-modal-carousel" class="carousel">
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/1.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/2.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/3.png">
          </figure>
        </div>

        <div class="content">

          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
            commodo
            consequat.</p>

          <div class="tags">
            <span class="tag">angular</span>
            <span class="tag">mongo</span>
            <span class="tag">typscript</span>
            <span class="tag">node</span>
          </div>

        </div>

      </section>
      <footer class="modal-card-foot">
        <button class="button is-success">Close</button>
      </footer>
    </div>
  </div>

  <div id="project-3-modal" class="modal">
    <div class="modal-background"></div>
    <div class="modal-card">
      <header class="modal-card-head">
        <p class="modal-card-title">Project title</p>
        <button class="delete" aria-label="close"></button>
      </header>
      <section class="modal-card-body">
        <div id="project-3-modal-carousel" class="carousel">
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/1.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/2.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/3.png">
          </figure>
        </div>

        <div class="content">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
            commodo
            consequat.</p>
          <div class="tags">
            <span class="tag">angular</span>
            <span class="tag">mongo</span>
            <span class="tag">typscript</span>
            <span class="tag">node</span>
          </div>
        </div>

      </section>
      <footer class="modal-card-foot">
        <button class="button is-success">Close</button>
      </footer>
    </div>
  </div>

  <div id="project-4-modal" class="modal">
    <div class="modal-background"></div>
    <div class="modal-card">
      <header class="modal-card-head">
        <p class="modal-card-title">Project title</p>
        <button class="delete" aria-label="close"></button>
      </header>
      <section class="modal-card-body">
        <div id="project-4-modal-carousel" class="carousel">
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/1.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/2.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/3.png">
          </figure>
        </div>

        <div class="content">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
            commodo
            consequat.</p>
          <div class="tags">
            <span class="tag">angular</span>
            <span class="tag">mongo</span>
            <span class="tag">typscript</span>
            <span class="tag">node</span>
          </div>
        </div>

      </section>
      <footer class="modal-card-foot">
        <button class="button is-success">Close</button>
      </footer>
    </div>
  </div>

  <div id="project-5-modal" class="modal">
    <div class="modal-background"></div>
    <div class="modal-card">
      <header class="modal-card-head">
        <p class="modal-card-title">Project title</p>
        <button class="delete" aria-label="close"></button>
      </header>
      <section class="modal-card-body">
        <div id="project-5-modal-carousel" class="carousel">
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/1.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/2.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/3.png">
          </figure>
        </div>

        <div class="content">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
            commodo
            consequat.</p>
          <div class="tags">
            <span class="tag">angular</span>
            <span class="tag">mongo</span>
            <span class="tag">typscript</span>
            <span class="tag">node</span>
          </div>
        </div>

      </section>
      <footer class="modal-card-foot">
        <button class="button is-success">Close</button>
      </footer>
    </div>
  </div>

  <div id="project-6-modal" class="modal">
    <div class="modal-background"></div>
    <div class="modal-card">
      <header class="modal-card-head">
        <p class="modal-card-title">Project title</p>
        <button class="delete" aria-label="close"></button>
      </header>
      <section class="modal-card-body">
        <div id="project-6-modal-carousel" class="carousel">
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/1.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/2.png">
          </figure>
          <figure class="image is-4by3 carousel-cell">
            <img src="img/carousel/3.png">
          </figure>
        </div>

        <div class="content">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore
            magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
            commodo
            consequat.</p>
          <div class="tags">
            <span class="tag">angular</span>
            <span class="tag">mongo</span>
            <span class="tag">typscript</span>
            <span class="tag">node</span>
          </div>
        </div>

      </section>
      <footer class="modal-card-foot">
        <button class="button is-success">Close</button>
      </footer>
    </div>
  </div>

  <footer class="footer">
    <div class="content has-text-centered">
      <p>
        <a href="https://github.com/mmacneil/devfolio" target="_blank" class="icon has-text-primary">
          <i class="fab fa-github"></i> <strong>devfolio</strong></a>
      </p>
    </div>
  </footer>

  <script src="js/bundle.js"></script>
</body>

</html>
