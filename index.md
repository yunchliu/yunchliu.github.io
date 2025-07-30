---
layout: homepage
---

<!-- 
  This style block defines the A4 page effect and the title styling.
-->
<style>
  /* Define the styles for our A4 page container */
  .a4-page {
    width: 21cm;
    min-height: 29.7cm;
    padding: 2cm;
    margin: 2em auto; 
    background: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    box-sizing: border-box; 
  }

  /* NEW: Style for all h2 titles inside the A4 page */
  .a4-page h2 {
    /* Creates the line directly under the text */
    border-bottom: 1px solid #ccc; 
    
    /* Adds a little space between the text and the line */
    padding-bottom: 0.3em;
    
    /* Adjusts the space below the line and the content that follows */
    margin-bottom: 0.8em; 
  }

  /* Responsive design for small screens */
  @media screen and (max-width: 21cm) {
    .a4-page {
      width: 100%;
      min-height: auto;
      margin: 0;
      box-shadow: none;
      padding: 1.5em 1em;
    }
  }
</style>

<!-- 
  This div wraps all content and applies the .a4-page style.
  The `markdown="1"` attribute is CRITICAL for rendering Markdown inside the div.
-->
<div class="a4-page" markdown="1">

<!-- Profile Section (this part is already HTML, so it works fine) -->
<div style="display: flex; align-items: flex-start; margin-bottom: 2em;">
  <img src="lyc.jpg" alt="Yuncheng Liu" style="width: 160px; margin-right: 25px; border-radius: 8px;">
  <div style="flex-grow: 1;">
    <h2 style="margin-top: 0; border-bottom: none; padding-bottom: 0;">Yuncheng Liu (刘云程)</h2>
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

I am a lecturer at ISE of USC Viterbi working with Prof. [Johannes O. Royset](https://sites.google.com/a/nps.edu/royset/). Before relocating to Los Angeles, I spent four wonderful years in Hong Kong and received my Ph.D. from [The Chinese University of Hong Kong (CUHK)](https://www.cuhk.edu.hk/english/index.html), where I was advised by Prof. [Anthony Man-Cho So](https://www.se.cuhk.edu.hk/people/anthony-man-cho-so/).

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
