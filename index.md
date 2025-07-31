---
layout: homepage
---

<!-- 
  This style block defines the A4 page effect and the title styling.
-->
<style>
  /* Define the styles for our A4 page container */
  .a4-page {
    width: 26cm;
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
    padding-bottom: 0.1em;
    
    /* Adjusts the space below the line and the content that follows */
    margin-bottom: 0.5em; 
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
      Lecturer<br>
      <a href="https://sxxy.swun.edu.cn/">Department of Mathematics</a><br>
      <a href="https://www.swun.edu.cn/">Southwest Minzu University</a>
    </p>
    <p style="margin: 1em 0;">
      <strong>Office:</strong> BC 208<br>
      <strong>Email:</strong>yuncheng.liu (at) swun.edu.cn
    </p>
  </div>
</div>


## About Me

I am currently a Lecturer at Department of Mathematics, Southwest Minzu University. From July 2023 to August 2024, I worked as a postdoctoral fellow with [Professor Ting Kei Pong](https://www.polyu.edu.hk/ama/profile/pong/) at [the Hong Kong Polytechnic University](https://www.polyu.edu.hk/). In 2021, I obtained my Ph.D. degree in Pure Mathematics at the [Sichuan Normal University](https://www.sicnu.edu.cn/), under the supervision of [Professor Fuquan Xia](http://139.155.71.72:81/HomePage.aspx?ID=14). I completed my M.S. degree in 2018 in Operational Research and Cybernetics at the [China West Normal University](https://www.cwnu.edu.cn/), under the supervision of [Professor Minglu Ye](). Prior to that, I obtained my B.A. degree in 2015 in Mathematics and Applied Mathematic at the [Sichuan Minzu colloge](https://www.scun.edu.cn/).

My research interests lie in the nonlinear optimization and its applications, and first-order methods for large-scale convex or nonconvex problems.

## Selected Recent Works [[Google Scholar]](URL_TO_GOOGLE_SCHOLAR_PROFILE)

- **Approximating Rockafellians Mitigate Perturbations** \
  L. Tian, J. O. Royset \
  *Preprint, 2025.* \
  [[arXiv]](URL_TO_ARXIV_PAPER_1)

- **Testing Approximate Stationarity Concepts for Piecewise Affine Functions** \
  L. Tian, A. M.-C. So \
  *Preprint.* \
  [[arXiv]](URL_TO_ARXIV_PAPER_2)

## Visits
- 2025.07 - 2025.08, Department of Applied Mathematics, The Hong Kong Polytechnic University, hosted by [Professor Ting Kei Pong](https://www.polyu.edu.hk/ama/profile/pong/).
  

</div> <!-- This closes the .a4-page wrapper -->
