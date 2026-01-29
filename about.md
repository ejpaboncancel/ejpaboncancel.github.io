---
layout: page
title: About
permalink: /about/
---

<p style="text-align: justify;">
I am proud to be product of the Puerto Rican Public School System. I have always been passionate for STEM, all the way from elementary school, 
to participating in the Puerto Rico Public School Math Olympiad and The National Society of Professional Surveyors Trig-Star National Competition. I started
my formal mathematical journey when I took the abstract algebra course at UPRM, and received mentorship from Prof. Reyes M. Ortiz Albino. This led me to participate 
in Summer REUs, as well as undergraduate research programs at UPRM. My motivation to continue doing research in mathematics led me to apply to graduate
school to earn a graduate degree in mathematics. Attached are some links related to my academic journey.
</p>

<br>
<hr>
<br>

<style>
  /* ==================== URA-Style Fellowship Grid ==================== */
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

  /* URA-Style Toggle/Accordion */
  .ura-fellow-card {
    margin-bottom: 20px;
  }

  .ura-fellow-image {
    text-align: center;
    margin-bottom: 20px;
  }

  .ura-fellow-image img {
    width: 100%;
    max-width: 100%;
    height: auto;
    display: block;
  }

  .ura-toggle {
    border: 1px solid #d9d9d9;
    background-color: #f4f4f4;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }

  .ura-toggle-title {
    padding: 20px;
    margin: 0;
    font-weight: 700;
    font-size: 14px;
    color: #666;
    position: relative;
    cursor: pointer;
    text-align: center;
  }

  .ura-toggle-title:before {
    content: "\25BC"; /* Down arrow */
    position: absolute;
    right: 20px;
    top: 50%;
    transform: translateY(-50%);
    font-size: 12px;
    color: #ccc;
    transition: transform 0.3s ease;
  }

  .ura-toggle.active .ura-toggle-title {
    color: #333;
  }

  .ura-toggle.active .ura-toggle-title:before {
    content: "\25B2"; /* Up arrow */
  }

  .ura-toggle.active {
    background-color: #fff;
  }

  .ura-toggle-content {
    display: none;
    padding: 20px;
    background-color: #fff;
    text-align: justify;
    line-height: 1.7em;
  }

  .ura-toggle-content p {
    margin: 0;
    padding-bottom: 0;
  }

  .ura-toggle.active .ura-toggle-content {
    display: block;
  }

  /* Fellowship Logo */
  .fellowship-logo {
    text-align: center;
    margin-top: 20px;
  }

  .fellowship-logo img {
    max-width: 100%;
    width: 80%;
    height: auto;
    display: block;
    margin: 0 auto;
  }

  /* Facebook post container - keeping original */
  .fb-post-container {
    max-width: 100%;
    width: 100%;
    margin: 20px auto;
    text-align: center;
    box-sizing: border-box;
  }

  /* Responsive adjustments */
  @media (max-width: 768px) {
    .fellowship-grid {
      grid-template-columns: 1fr;
      gap: 20px;
    }
  }
</style>

<div class="fellowship-grid">
  <!-- URA-Sandia Fellowship Section -->
  <div class="fellowship-section">
    <h4 style="margin-top: 0; text-align: center;">2025 URA-Sandia Graduate Student Summer Fellowship</h4>
    <p style="text-align: justify;">
      Article posted by URA, as part of the 2025 cohort of the URA-Sandia Graduate Student Summer Fellowship, a research fellowship program by the Universities Research Association and Sandia National Laboratories.
      Learn more about the 2025 Fellows <a href="https://ura-hq.org/stem-research/sandia-graduate-student-summer-fellowship/2025-sandia-graduate-fellows/" style="color: rgb(51, 113, 55);">here</a>.
    </p>

    <div class="ura-fellow-card">
      <div class="ura-fellow-image">
        <img src="https://ura-hq.org/wp-content/uploads/2025/03/Eric-P.jpg" alt="Eric J. Pabón Cancel">
      </div>
      <div class="ura-toggle">
        <h5 class="ura-toggle-title">Eric J. Pabón Cancel, Purdue University</h5>
        <div class="ura-toggle-content">
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
    <p style="text-align: justify;">
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
  // Toggle functionality for URA-style accordion
  document.addEventListener('DOMContentLoaded', function() {
    const toggles = document.querySelectorAll('.ura-toggle');
    
    toggles.forEach(function(toggle) {
      const title = toggle.querySelector('.ura-toggle-title');
      
      title.addEventListener('click', function() {
        // Close other toggles (optional - remove if you want multiple open at once)
        toggles.forEach(function(otherToggle) {
          if (otherToggle !== toggle) {
            otherToggle.classList.remove('active');
          }
        });
        
        // Toggle current
        toggle.classList.toggle('active');
      });
    });
  });
</script>

<br>
<hr>
<br>

<h4 style="margin-top: 0;">Summer@ICERM 2022: Computational Combinatorics</h4>
<p style="text-align: justify;">
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
<p style="text-align: justify;">
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
