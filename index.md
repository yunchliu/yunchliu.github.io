---
layout: homepage
---

<!-- 
  This style block defines the A4 page effect.
  It's placed here to be self-contained within this file.
-->
<style>
  /* Define the styles for our A4 page container */
  .a4-page {
    /* A4 paper dimensions */
    width: 26cm; /* A4 width */
    min-height: 29.7cm; /* A4 height. Use min-height to allow content to grow. */
    
    /* Page margins (padding inside the container) */
    padding: 2cm;
    
    /* Center the page on the screen */
    margin: 2em auto; 
    
    /* Visual appearance of paper */
    background: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Subtle shadow to lift it off the page */
    
    /* IMPORTANT: Ensures padding is included in the total width/height */
    box-sizing: border-box; 
  }

  /* Responsive design for small screens (like mobile phones) */
  @media screen and (max-width: 21cm) {
    .a4-page {
      /* On small screens, let the content fill the screen width */
      width: 100%;
      min-height: auto;
      
      /* Remove centering and shadow */
      margin: 0;
      box-shadow: none;
      
      /* Reduce padding for smaller screens */
      padding: 1em;
    }
  }
</style>

<!-- This div wraps all content and applies the .a4-page style -->
<div class="a4-page">

  <!-- 
    This section uses HTML to create a two-column layout for the profile.
    - Left column: Profile picture.
    - Right column: Name, title, and contact information.
  -->
  <div style="display: flex; align-items: flex-start; margin-bottom: 2em;">
    <img src="lyc.jpg" alt="Yuncheng Liu" style="width: 160px; margin-right: 25px; border-radius: 8px;">
    <div style="flex-grow: 1;">
      <h2 style="margin-top: 0;">Yuncheng Liu (刘云程)</h2>
      <p style="margin: 0.5em 0;">
        Postdoctoral Scholar<br>
        <a href="https://ise.usc.edu/">Daniel J. Epstein Department of Industrial & Systems Engineering</a><br>
        <a href="https://www.usc.edu/">University of Southern California</a>
      </p>
      <p style="margin: 1em 0;">
        <strong>Office:</strong> OHE 340<br>
        <strong>Email:</strong> tianlai.cs (at) gmail.com; laitian (at) usc.edu
      </p>
    </div>
  </div>


  ## About Me

  I am a Postdoctoral Scholar at ISE of USC Viterbi working with Prof. [Johannes O. Royset](https://sites.google.com/a/nps.edu/royset/). Before relocating to Los Angeles, I spent four wonderful years in Hong Kong and received my Ph.D. from [The Chinese University of Hong Kong (CUHK)](https://www.cuhk.edu.hk/english/index.html), where I was advised by Prof. [Anthony Man-Cho So](https://www.se.cuhk.edu.hk/people/anthony-man-cho-so/).

  My research interests lie in the interface between mathematical optimization and computer science, with a particular emphasis on applications in modern machine learning. Recently, I have been especially focused on the computational and theoretical aspects of various **approximation techniques** in nonsmooth optimization and variational analysis.


  ## What's New?
  - Honored and grateful to share that our work received the **Best Paper Prize** for Young Researchers at [ICCOPT 2025](https://iccopt2025.gerad.ca/)!


  ## Selected Recent Works [[Google Scholar]](URL_TO_GOOGLE_SCHOLAR_PROFILE)

  - **Approximating Rockafellians Mitigate Distributional Perturbations** \
    L. Tian, J. O. Royset \
    *Preprint, 2025.* \
    [[arXiv]](URL_TO_ARXIV_PAPER_1)

  - **Testing Approximate Stationarity Concepts for Piecewise Affine Functions** \
    L. Tian, A. M.-C. So \
    *Preprint.* \
    [[arXiv]](URL_TO_ARXIV_PAPER_2)

</div> <!-- This closes the .a4-page wrapper -->
