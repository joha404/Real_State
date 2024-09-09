<template>
  <div>
    <nav class="navbar navbar-expand-sm">
      <div class="container">
        <a class="navbar-brand">
          <img src="../assets/logo.png" class="logo" alt="" />
          <span class="logo-right-side mt-5">Estatein</span>
        </a>
        <button
          class="navbar-toggler custom-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#mynavbar"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="mynavbar">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item mx-4">
              <a class="nav-link">Home</a>
            </li>
            <li class="nav-item mx-4">
              <a class="nav-link">About Us</a>
            </li>
            <li class="nav-item mx-4">
              <a class="nav-link">Properties</a>
            </li>
            <li class="nav-item mx-4">
              <a class="nav-link">Services</a>
            </li>
          </ul>
          <button class="btn ms-auto" id="navBtn" type="button">
            Contact Us
          </button>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
nav {
}
.navbar {
  display: flex;
  justify-content: space-between;
  background-color: #1a1a1a;
}
.logo-right-side {
  font-size: 22px;
  font-weight: bold;
  color: white;
  margin-left: 10px;
  position: relative;
  top: 1px !important;
}
.logo {
  width: 48px;
  height: 48px;
}

.nav-item .nav-link {
  color: white !important;
  padding: 6px 20px;
  cursor: pointer;
  border-radius: 8px;
}

.nav-item:hover {
  background-color: #121212;
}
#navBtn {
  background-color: #121212;
  color: white;
}
.custom-toggler {
  background-color: transparent; /* No background color */
  color: white; /* White text color */
  border: 1px solid #191919; /* No border */
}

.custom-toggler:hover,
.custom-toggler:active,
.custom-toggler:focus {
  background-color: transparent; /* No background color on hover, active, or focus */
  border: 1px solid #191919;
  box-shadow: none !important;
}

.custom-toggler .navbar-toggler-icon {
  background-image: none; /* Remove default icon */
}

.custom-toggler .navbar-toggler-icon::before {
  content: "\2630"; /* Unicode for hamburger menu icon */
  color: white; /* White icon color */
  font-size: 1.25em; /* Adjust icon size as needed */
}
</style>
<!-- #141414 -->
