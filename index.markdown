---
layout: home
---

<style>
  .container {
    /* Center the whole block on the page */
    display: flex;
    flex-direction: column;
    align-items: center;
    /* optional: control overall width for both image and text */
    max-width: 700px;
    margin: 0 auto;
    padding: 0 20px;
  }

  /* Apply a shared width to each column */
  .column {
    width: 85%;            /* fill container width */
    max-width: 600px;       /* the “measure” of your text and image */
    margin: 0 auto 24px;    /* spacing between image and text */
  }

  .column img {
    display: block;         /* removes inline gap */
    width: 85%;            /* make image match column width */
    height: auto;           /* keep aspect ratio */
    margin: 0 auto 20px;    /* space below image */
  }

  /* Optional: nicer text line length */
  .column p {
    line-height: 1.6;
  }
</style>

<div class="container">
  <div class="column">
    <img src="files/portrait_Jan2026.JPG" alt="Portrait of Edith Zink" />
  </div>
  <div class="column">
    I am an applied micro-economist studying integration and currently employed as a Post-Doc at the <a href="https://www.economics.ku.dk/">Department of Economics, University of Copenhagen</a>. <br>
    My PhD was on the political economy of social exclusion, with case studies in Tunisia, Tanzania, and Denmark. 
    As a post-doc, I have since successfully developed this research, in an interdisciplinary approach with political scientists and psychologists, 
    to study the social and economic assimilation of Ukrainian refugees in Denmark. In the future, I will continue to contribute to a better understanding of the social fabric of our societies, with a focus on policy implications for immigrant integration in Europe.
  </div>
</div>



