---
layout: page
title: About
permalink: /about/
---

<p>
I am proud to say that I am product of the Puerto Rican Public School System. I have always been passionate for STEM, all the way from elementary school, 
to participating in the Puerto Rico Public School Math Olympiad and The National Society of Professional Surveyors Trig-Star National Competition. I started
my formal mathematical journey when I took the abstract algebra course at UPRM, and received mentorship from Prof. Reyes M. Ortiz Albino. This led me to participate 
in Summer REUs, as well as undergraduate research programs at UPRM. My motivation to continue doing research in mathematics led me to apply to graduate
school to earn a graduate degree in mathematics. Attached are some links related to my academic journey.
</p>

<br>
<hr>
<br>

<style>
  /* ==================== Fellowship Grid ==================== */
  .fellowship-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
    align-items: start;
    margin: 30px 0;
  }

  .fellowship-section {
    padding: 0;
    width: 100%;
    box-sizing: border-box;
  }

  .fellowship-card {
    text-align: center;
  }

  .fellowship-card img {
    width: 100%;
    max-width: 350px;
    height: auto;
    margin: 0 auto 20px auto;
    display: block;
  }

  .fellow-toggle {
    background-color: #f4f4f4;
    border: 1px solid #d9d9d9;
    border-radius: 4px;
    overflow: hidden;
  }

  .toggle-header {
    padding: 20px;
    cursor: pointer;
    font-weight: 700;
    color: #666;
    background-color: #f4f4f4;
    position: relative;
    text-align: center;
  }

  .toggle-header:hover {
    background-color: #e8e8e8;
  }

  .toggle-header::after {
    content: "▼";
    position: absolute;
    right: 20px;
    top: 50%;
    transform: translateY(-50%);
    font-size: 12px;
    color: #ccc;
  }

  .toggle-content {
    display: none;
    padding: 20px;
    background-color: #fff;
    text-align: justify;
  }

  .toggle-content.active {
    display: block;
  }

  .toggle-header.active::after {
    content: "▲";
  }

  .fellowship-logo {
    text-align: center;
    margin-top: 20px;
  }

  .fellowship-logo img {
    max-width: 100%;
    width: 80%; /* responsive width */
    height: auto;
    display: block;
    margin: 0 auto;
  }

  /* Facebook post container */
  .fb-post-container {
    max-width: 100%;
    width: 100%;
    margin: 20px auto;
    text-align: center;
    padding-left: 5%;
    padding-right: 5%;
    box-sizing: border-box;
  }

  /* ==================== Responsive Adjustments ==================== */
  @media (max-width: 768px) {
    /* Single column grid */
    .fellowship-grid {
      grid-template-columns: 1fr !important;
      gap: 20px;
      justify-items: center;
      text-align: center;
    }

    /* Center sections */
    .fellowship-section {
      max-width: 90%;
      margin: 0 auto;
      padding-left: 0;
      padding-right: 0;
    }

    /* Keep text readable but balanced */
    .fellowship-section p {
      text-align: justify;
      margin: 0 auto;
    }

    /* Facebook post container */
    .fb-post-container {
      text-align: center;
      padding-left: 0;
      padding-right: 0;
    }

    /* Scale down logos/images for mobile */
    .fellowship-logo img {
      width: 90%;
    }
  }
</style>

<div class="fellowship-grid">
  <!-- URA-Sandia Fellowship Section -->
  <div class="fellowship-section">
    <h4 style="margin-top: 0; text-align: center;">2025 URA-Sandia Graduate Student Summer Fellowship</h4>
    <p>
      Article posted by URA, as part of the 2025 cohort of the URA-Sandia Graduate Student Summer Fellowship, a research fellowship program by the Universities Research Association and Sandia National Laboratories.
      Learn more about the 2025 Fellows <a href="https://ura-hq.org/stem-research/sandia-graduate-student-summer-fellowship/2025-sandia-graduate-fellows/" style="color: rgb(51, 113, 55);">here</a>.
    </p>

    <div class="fellowship-card">
      <img src="https://ura-hq.org/wp-content/uploads/2025/03/Eric-P.jpg" alt="Eric J. Pabón Cancel">
      <div class="fellow-toggle">
        <div class="toggle-header" onclick="toggleFellowContent(this)">
          Eric J. Pabón Cancel, Purdue University
        </div>
        <div class="toggle-content">
          <p>Hello there! I am Eric, a 2nd year PhD student in Mathematics at Purdue University. My current research interests are in Dynamical Systems and Machine Learning methods. My latest research was in Generative Artificial Intelligence and Mathematical Algorithms, where I applied clustering methods and Principal Component Analysis to determine the optimal autoencoder for sequences of unlabeled data. My work at Sandia is on Machine Learning applications for Data Driven Closure Models. I earned my Bachelor of Science degree in Mathematics from the University of Puerto Rico, Mayagüez Campus. After completing my graduate studies, I aspire to become a mathematical research scientist, and outside of academics I like to make origami figures and play percussion instruments.</p>
        </div>
      </div>
    </div>

    <div class="fellowship-logo">
      <a href="https://ura-hq.org/stem-research/sandia-graduate-student-summer-fellowship/" target="_blank">
        <img src="https://ura-hq.org/wp-content/uploads/2025/03/URA-SANDIA-.png" alt="URA Sandia Partnership">
      </a>
    </div>
  </div>

  <!-- Facebook Section -->
  <div class="fellowship-section">
    <h4 style="margin-top: 0; text-align: center;">Vega Baja Te Informa: <br> Vegabajeños que hacen historia | Educación</h4>
    <p>
      Article posted by the electronic newspaper of my hometown, <i>Vega Baja Te Informa</i>, explaining my cultural and academic journey.
    </p>
    <div id="fb-root"></div>
    <script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v17.0" nonce="XYZ"></script>
    <div class="fb-post-container">
      <div class="fb-post" 
           data-href="https://www.facebook.com/vegabajateinforma/posts/642005397959682" 
           data-show-text="true" 
           data-width="100%">
      </div>
    </div>
  </div>
</div>

<script>
  function toggleFellowContent(header) {
    const content = header.nextElementSibling;
    const isActive = content.classList.contains('active');

    if (isActive) {
      content.classList.remove('active');
      header.classList.remove('active');
    } else {
      content.classList.add('active');
      header.classList.add('active');
    }
  }
</script>

<br>
<hr>
<br>

<h4 style="margin-top: 0;">Summer@ICERM 2022: Computational Combinatorics</h4>
<p>
Final presentation of the research conducted as part of the Summer@ICERM 2022 REU Program "On Permutation-Invariant Parking Sequences".
</p>

<!-- Panopto responsive embed -->
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 0 auto;">
  <iframe 
    src="https://brown.hosted.panopto.com/Panopto/Pages/Embed.aspx?id=2e350578-3784-48d7-abfc-aee70108ed63&autoplay=false&offerviewer=true&showtitle=false&showbrand=false&start=0"
    frameborder="0" allowfullscreen
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:none;">
  </iframe>
</div>

<br>
<hr>
<br>

<h4 style="margin-top: 0;">2018 UPRM Pre-Engineering Summer Camp</h4>
<p>
Interview posted by the UPRM News Organization, <i>Prensa RUM</i>, regarding my experience in the 2018 UPRM STEM and Pre-Engineering Camp the summer before entering the university.
</p>

<!-- YouTube responsive embed -->
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin: 0 auto;">
  <iframe 
    src="https://www.youtube.com/embed/sNTfmJjSI60?start=144"
    title="YouTube video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
  </iframe>
</div>
