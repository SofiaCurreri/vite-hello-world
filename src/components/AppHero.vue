<script></script>

<template>
  <!-- Jumbotron -->
  <section id="jumbotron" class="text-center">
    <div
      class="container d-flex flex-column justify-content-center align-items-center"
    >
      <!-- Title and subtitle -->
      <h1 class="mb-4">BUILDING INSPIRING SPACES</h1>
      <h3 class="mb-5 mt-4">
        We Build Inspiring Residential & Commercial Spaces
      </h3>

      <!-- Buttons -->
      <div class="d-flex justify-content-center">
        <button class="btn secondary fs-4 px-5 py-3">
          EXPLORE RECENT WORK
        </button>
        <button class="btn primary ms-4 fs-4 px-5 py-3">
          GET A QUOTE TODAY
        </button>
      </div>
    </div>
  </section>
</template>

<style scoped>
#jumbotron {
  height: 85vh;
  background-image: url("./images/home-slider.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}

#jumbotron .container {
  height: 100%;
}

#jumbotron h1 {
  color: #ffffff;
  font-size: 5rem;
}

#jumbotron h3 {
  color: #fed03d;
}

h1 {
  font-weight: 900;
  line-height: 5rem;
}

h1,
h3 {
  color: #333333;
}
.btn {
  border-radius: 0px;
}

.btn.secondary {
  color: #ffffff;
  background-color: #333333;
}
.btn.primary {
  background-color: #fed03d;
}
</style>
