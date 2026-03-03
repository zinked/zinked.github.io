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
  Welcome! <br>
    I am a Post-Doc at the <a href="https://www.economics.ku.dk/">Department of Economics, University of Copenhagen</a>. <br>
	My main research interests are economic and social integration, with a current focus on the early integration outcomes of Ukrainian refugees in Denmark. <br>
	I will be visiting Stanford from April until June 2026. 
  </div>
</div>



