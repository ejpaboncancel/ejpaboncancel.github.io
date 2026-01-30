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

  /* URA Iframe Container */
  .ura-iframe-container {
    width: 100%;
    height: 780px;
    border: 1px solid #d9d9d9;
    border-radius: 4px;
    overflow: hidden;
    background-color: #fff;
  }

  .ura-iframe-container iframe {
    width: 100%;
    height: 100%;
    border: none;
  }

  /* Facebook Iframe Container - matching URA style */
  .fb-iframe-container {
    width: 100%;
    height: 780px;
    border: 1px solid #d9d9d9;
    border-radius: 4px;
    overflow: hidden;
    background-color: #fff;
  }

  .fb-iframe-container iframe {
    width: 100%;
    height: 100%;
    border: none;
  }

  /* Responsive adjustments */
  @media (max-width: 768px) {
    .fellowship-grid {
      grid-template-columns: 1fr;
      gap: 20px;
    }
    
    .ura-iframe-container,
    .fb-iframe-container {
      height: 780px;
    }
  }
</style>

<div class="fellowship-grid">
  <!-- URA-Sandia Fellowship Section - Scrollable iframe to my profile -->
  <div class="fellowship-section">
    <h4 style="margin-top: 0; text-align: center;">2025 URA-Sandia Graduate Student Summer Fellowship</h4>
    <p style="text-align: justify;">
      Article posted by URA, as part of the 2025 cohort of the URA-Sandia Graduate Student Summer Fellowship, a research fellowship program by the Universities Research Association and Sandia National Laboratories.
    </p>

    <!-- Iframe that scrolls to Eric's profile -->
    <div class="ura-iframe-container">
      <iframe 
        id="ura-profile-iframe"
        src="https://ura-hq.org/stem-research/sandia-graduate-student-summer-fellowship/2025-sandia-graduate-fellows/"
        title="Eric J. Pabón Cancel - URA Sandia Fellow Profile"
        scrolling="yes"
        loading="lazy">
      </iframe>
    </div>

    <script>
      // Try to scroll the iframe to Eric's profile section
      document.addEventListener('DOMContentLoaded', function() {
        const iframe = document.getElementById('ura-profile-iframe');
        
        // Wait for iframe to load
        iframe.addEventListener('load', function() {
          try {
            // Attempt to access iframe content and scroll to Eric's profile
            const iframeDoc = iframe.contentDocument || iframe.contentWindow.document;
            const ericProfile = iframeDoc.querySelector('#et_pb_toggle_7');
            
            if (ericProfile) {
              // Scroll the iframe content to Eric's profile
              ericProfile.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
          } catch (e) {
            // Cross-origin security will likely block this
            // Fallback: add anchor to URL
            console.log('Cannot access iframe content due to cross-origin restrictions');
            iframe.src = 'https://ura-hq.org/stem-research/sandia-graduate-student-summer-fellowship/2025-sandia-graduate-fellows/#et_pb_toggle_7';
          }
        });
      });
    </script>
  </div>

  <!-- Facebook Section -->
  <div class="fellowship-section">
    <h4 style="margin-top: 0; text-align: center;">Vega Baja Te Informa: <br> Vegabajeños que hacen historia | Educación</h4>
    <p style="text-align: justify;">
      Article posted by the electronic newspaper of my hometown, <i>Vega Baja Te Informa</i>, explaining my cultural and academic journey.
    </p>
    
    <!-- Facebook post iframe -->
    <div class="fb-iframe-container">
      <iframe 
        src="https://m.facebook.com/vegabajateinforma/posts/642005397959682"
        title="Vega Baja Te Informa Facebook Post"
        scrolling="yes"
        allow="encrypted-media"
        loading="lazy">
      </iframe>
    </div>
  </div>
</div>

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
