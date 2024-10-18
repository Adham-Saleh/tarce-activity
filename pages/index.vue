<template>
  <div class="container mt-3 bg-dark">
    <div class="row">
      <div class="col">
        <div class="alert alert-danger">
          This web app is made with Nuxt js and its not my final portfolio yet
          <a
            href="https://github.com/Adham-Saleh/tarce-activity"
            target="_blank"
          >
            gitHub
            <svg
              xmlns="http://www.w3.org/2000/svg"
              height="15px"
              viewBox="0 -960 960 960"
              width="15px"
              fill="blue"
            >
              <path
                d="m216-160-56-56 464-464H360v-80h400v400h-80v-264L216-160Z"
              />
            </svg>
          </a>
        </div>
      </div>
    </div>
    <!-- Tabs Navigation -->
    <ul class="nav nav-tabs" id="myTab" role="tablist">
      <li class="nav-item" role="presentation">
        <a
          class="nav-link active"
          id="about-tab"
          data-bs-toggle="tab"
          href="#about"
          role="tab"
          aria-controls="about"
          aria-selected="false"
          >About</a
        >
      </li>
      <li class="nav-item" role="presentation">
        <a
          class="nav-link"
          id="schedule-tab"
          data-bs-toggle="tab"
          href="#schedule"
          role="tab"
          aria-controls="schedule"
          aria-selected="false"
          >Schedule</a
        >
      </li>
    </ul>

    <!-- Tabs Content -->
    <div class="tab-content mt-3" id="myTabContent">
      <div
        class="tab-pane fade show active"
        id="about"
        role="tabpanel"
        aria-labelledby="about-tab"
      >
        <about />
      </div>
      <div
        class="tab-pane fade"
        id="schedule"
        role="tabpanel"
        aria-labelledby="schedule-tab"
      >
        <schedual />
      </div>
      <div
        class="tab-pane fade"
        id="projects"
        role="tabpanel"
        aria-labelledby="projects-tab"
      >
        <p>This is the content for the Projects tab.</p>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
