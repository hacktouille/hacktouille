<script setup></script>

<template>
  <main>
    <header class="header">
      <nav class="navbar navbar-expand-lg py-6">
        <div class="container">
          <a href="#" class="navbar-brand text-uppercase font-weight-bold"
            >if cachorros</a
          >
          <button
            type="button"
            data-toggle="collapse"
            data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
            class="navbar-toggler navbar-toggler-right"
          >
            <i class="fa fa-bars"></i>
          </button>

          <div id="navbarSupportedContent" class="collapse navbar-collapse">
            <ul class="navbar-nav ml-auto">
              <li class="nav-item active">
                <a href="#" class="nav-link text-uppercase font-weight-bold"
                  >Home <span class="sr-only">(current)</span></a
                >
              </li>
              <li class="nav-item">
                <router-link to="/about">
                  <a href="#" class="nav-link text-uppercase font-weight-bold"
                    >About
                  </a>
                </router-link>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link text-uppercase font-weight-bold"
                  >Gallery</a
                >
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link text-uppercase font-weight-bold"
                  >Portfolio</a
                >
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link text-uppercase font-weight-bold"
                  >Contact</a
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
  </main>
</template>

<style>
.navbar {
  transition: all 0.4s;
}

.navbar .nav-link {
  color: rgb(192, 83, 83);
}

.navbar .nav-link:hover,
.navbar .nav-link:focus {
  color: rgb(100, 62, 62);
  text-decoration: none;
}

.navbar .navbar-brand {
  color: rgb(204, 63, 63);
}

.navbar.active {
  background: rgb(255, 255, 255);
  box-shadow: 1px 2px 10px rgba(0, 0, 0, 0.1);
}

.navbar.active .nav-link {
  color: #555;
}

.navbar.active .nav-link:hover,
.navbar.active .nav-link:focus {
  color: #555;
  text-decoration: none;
}

.navbar.active .navbar-brand {
  color: #555;
}

/* Change navbar styling on small viewports */
@media (max-width: 100%) {
  .navbar {
    background: rgb(202, 43, 43);
  }

  .navbar .navbar-brand,
  .navbar .nav-link {
    color: #555;
  }
}

/*
*
* ==========================================
* FOR DEMO PURPOSES
* ==========================================
*
*/
.text-small {
  font-size: 0.9rem !important;
}

body {
  min-height: 110rem;
  background-color: #ffffff;
  background-image: linear-gradient(135deg, #ffffff 0%, #c4e0e5 100%);
}
</style>
