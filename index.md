<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Pierre Bertrand</title>

  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      background-color: #f4f7fb;
      color: #222;
      line-height: 1.6;
    }

    .page {
      max-width: 1000px;
      margin: 40px auto;
      background-color: white;
      padding: 50px;
      border-radius: 14px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
    }

    header {
      border-bottom: 3px solid #1f4e79;
      padding-bottom: 25px;
      margin-bottom: 35px;
    }

    h1 {
      font-size: 42px;
      color: #1f4e79;
      margin-bottom: 5px;
    }

    .subtitle {
      font-size: 18px;
      color: #555;
      margin-top: 0;
    }

    h2 {
      color: #1f4e79;
      margin-top: 40px;
      border-bottom: 1px solid #d6e0ea;
      padding-bottom: 6px;
    }

    h3 {
      color: #333;
      margin-bottom: 4px;
    }

    .institution {
      color: #555;
      font-weight: bold;
      margin-top: 0;
    }

    .card {
      background-color: #f8fbff;
      border-left: 4px solid #1f4e79;
      padding: 18px 22px;
      margin: 20px 0;
      border-radius: 8px;
    }

    .keywords {
      font-size: 14px;
      color: #555;
      background-color: #eef4fa;
      padding: 8px 12px;
      border-radius: 6px;
    }

    ul {
      padding-left: 22px;
    }

    li {
      margin-bottom: 5px;
    }

    .skills {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 15px;
    }

    .skill-box {
      background-color: #f8fbff;
      padding: 15px;
      border-radius: 8px;
      border: 1px solid #d6e0ea;
    }

    footer {
      margin-top: 50px;
      padding-top: 20px;
      border-top: 1px solid #d6e0ea;
      color: #555;
    }

    a {
      color: #1f4e79;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>

  <div class="page">

    <header>
      <h1>Pierre Bertrand</h1>
      <p class="subtitle">
        Master’s student in Biology, Ecology and Evolution — University of Lille, France
      </p>
    </header>

    <section>
      <h2>About me</h2>
      <p>
        I am a Master’s student in <strong>Biology, Ecology and Evolution</strong> at the
        University of Lille, with a strong interest in evolutionary ecology, functional
        diversity, intraspecific trait variability, freshwater fish ecology, and species
        conservation.
      </p>

      <p>
        My academic background combines field ecology, biodiversity monitoring, morphometric
        analyses, statistical modelling, and data analysis in R.
      </p>
    </section>

    <section>
      <h2>Research interests</h2>
      <ul>
        <li>Evolutionary ecology</li>
        <li>Functional diversity</li>
        <li>Intraspecific trait variability</li>
        <li>Phenotypic plasticity and local adaptation</li>
        <li>Freshwater fish ecology</li>
        <li>Community ecology and conservation biology</li>
      </ul>
    </section>

    <section>
      <h2>Education</h2>

      <div class="card">
        <h3>Master’s Degree in Biology, Ecology and Evolution</h3>
        <p class="institution">University of Lille, France — Evolutionary Biology track</p>
        <p>
          Training in ecology, evolutionary biology, biostatistics, scientific writing,
          multivariate analyses, and data analysis in R.
        </p>
      </div>

      <div class="card">
        <h3>Bachelor’s Degree in Biology</h3>
        <p class="institution">University of Lille, France</p>
        <p>
          Broad background in biological sciences, including ecology, evolution, biodiversity,
          physiology, molecular biology, and biostatistics.
        </p>
      </div>
    </section>

    <section>
      <h2>Research experience</h2>

      <div class="card">
        <h3>Master’s internship — CRBE, Toulouse, France</h3>
        <p class="institution">
          Centre de Recherche sur la Biodiversité et l’Environnement — Team AQUAECO
        </p>
        <p>
          This internship focused on the role of <strong>intraspecific trait variability</strong>
          in the functional diversity of freshwater fish communities from French Guiana.
        </p>

        <ul>
          <li>Morphometric data analysis</li>
          <li>Functional trait analysis</li>
          <li>Comparison between individual-level and species-centroid approaches</li>
          <li>PCA and multivariate analyses</li>
          <li>Statistical analyses in R</li>
        </ul>

        <p class="keywords">
          Keywords: freshwater fish ecology · functional diversity · morphometrics · French Guiana
        </p>
      </div>

      <div class="card">
        <h3>Research internship — Stockholm University, Sweden</h3>
        <p class="institution">Department of Ecology, Environment and Plant Sciences</p>
        <p>
          This project investigated how vegetation cover and predator communities influence
          the survival of gammarids in coastal ecosystems.
        </p>

        <ul>
          <li>Fieldwork in coastal ecosystems</li>
          <li>Experimental tethering of gammarids</li>
          <li>Analysis of predator effects</li>
          <li>Statistical modelling in R</li>
        </ul>

        <p class="keywords">
          Keywords: predator–prey interactions · coastal ecology · vegetation cover · trophic interactions
        </p>
      </div>

      <div class="card">
        <h3>Marine biology internship — Wimereux Marine Station, France</h3>
        <p class="institution">UMR 8187 LOG — Oceanology and Geosciences Laboratory</p>
        <p>
          Internship focused on benthic macrofauna, macroflora, and foraminifera identification.
        </p>

        <ul>
          <li>Sampling and identification of benthic organisms</li>
          <li>Marine biodiversity analysis</li>
          <li>Microscopy-based observation and identification</li>
        </ul>

        <p class="keywords">
          Keywords: marine biology · benthic ecology · foraminifera · coastal biodiversity
        </p>
      </div>

      <div class="card">
        <h3>Coral reef monitoring project — Bali, Indonesia</h3>
        <p class="institution">Indonesian Marine Education & Research Organisation</p>
        <p>
          Project focused on the ecological impacts of discarded fishing gear on coral reefs
          and the development of monitoring approaches.
        </p>

        <ul>
          <li>Coral reef monitoring using SCUBA diving</li>
          <li>Hard coral and nudibranch identification</li>
          <li>Field data collection and database curation</li>
        </ul>

        <p class="keywords">
          Keywords: coral reefs · conservation biology · SCUBA · tropical marine ecology
        </p>
      </div>
    </section>

    <section>
      <h2>Technical skills</h2>

      <div class="skills">

        <div class="skill-box">
          <h3>Data analysis</h3>
          <ul>
            <li>R and RStudio</li>
            <li>Data cleaning</li>
            <li>Data visualization</li>
            <li>Statistical modelling</li>
            <li>GLM and GLMM approaches</li>
          </ul>
        </div>

        <div class="skill-box">
          <h3>Scientific methods</h3>
          <ul>
            <li>Morphometric analysis</li>
            <li>Functional trait analysis</li>
            <li>Biodiversity monitoring</li>
            <li>Species identification</li>
            <li>Image-based measurements</li>
          </ul>
        </div>

      </div>
    </section>

    <footer>
      <h2>Contact</h2>
      <p>
        <strong>Pierre Bertrand</strong><br>
        University of Lille, France<br>
        Email: your.email@example.com
      </p>
    </footer>

  </div>

</body>

</html>
