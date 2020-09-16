<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/NJaku01/NJaku01.github.io">
    <img src="public/logo2.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Bachelor Thesis - Combining Augmented Reality and Reproducibilityto convey spatio-temporal results </h3>

  <p align="center">
    This repository contains all source code developed and data collected during the bachelor thesis
    <br/>
    <a href="njaku01.github.io">View App</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
* [Contributing](#contributing)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project
Spatio-temporal research results are usually published in a static format, for example, as PDF. Herethe results are not directly linked to their spatial reference.  Therefore, it is difficult for the userto understand these results.  To improve the user’s understanding, we link these results with thereal world. To archive this, we use the raising concept of Augmented Reality, where it is possibleto integrate the results into the view of the user and to display the results on site.  The resultsare often calculated out of a specified dataset.  The results must be reproducible, to ensure thedata used for the application indicates the same result presented in the article. The goal is to tocombine the reproducibility and Augmented Reality to convey spatio-temporal results. We answeredthe research question about how to create an Augmented Reality application out of a reproduciblearticle.  Therefore, we performed a literature research and developed a concept which provides aguideline and explains the important steps. Starting with extracting the data used to calculate theresults. Designing the app and deciding which types of visualization and devices fit best for the resultand implementing the application. To show the feasibility of the concept, we created an application toconvey the results of one scientific article. This application was evaluated with an expert user study,with the goal to indicate whether the application is understandable and easy to use. Furthermore,the general interest in using AR applications to inspect spatio-temporal results got researched.The results of our research show that is possible to convey spatio-temporal results through AugmentedReality. The results are displayed understandable. Overall, AR is an interesting approach to displayresults out of scientific articles which should be further researched.

The article "Modelling of Urban Air Pollutant Concentrations with Artificial Neural Networks Using Novel Input Variables is displayed. It was written by Laura Goulier, Bastian Paas, Laura Ehrnsperger, and Otto Klemm. It was published
          in the International Journal of Environmental Research and Public Health 17, no. 6 (January 2020) page number
          2025. The paper is accessible under <a style="pointer-events: all;"
            href="https://doi.org/10.3390/ijerph17062025" target="_blank">https://doi.org/10.3390/ijerph17062025</a>

This repository contains all data and sourcecode which was used during the thesis:

* [dataExtraction](https://github.com/NJaku01/NJaku01.github.io/tree/master/dataExtraction) contains source code used to reproduce and extract the results out of the paper
* [dataExtraction/Paper](https://github.com/NJaku01/NJaku01.github.io/tree/master/dataExtraction/Paper) contians all data and source code written and collected by the authors of the paper display. The data are also accessible under https://osf.io/rjw8d/

* [studyEvalition](https://github.com/NJaku01/NJaku01.github.io/tree/master/studyEvaluation) contains the results of the study and source code to analyze these. The results are also accessible as Exectuable Research Compendium under:

* [public](https://github.com/NJaku01/NJaku01.github.io/tree/master/public) contains all CSS and JavaScript files that were used for the Application PapAR.

* [index.html](https://github.com/NJaku01/NJaku01.github.io/blob/master/index.html) is the main HTML-File for the developed application.


### Built With

* [JQuery](https://jquery.com/)
* [jQuery-csv](https://github.com/typeiii/jquery-csv)
* [A-Frame](https://aframe.io/)
* [AR.js](https://ar-js-org.github.io/AR.js-Docs/)
* [Metro 4](https://metroui.org.ua/)
* [aframe-particle-system-component](https://github.com/IdeaSpaceVR/aframe-particle-system-component)
* [D3](https://d3js.org/)
* [node.js](https://nodejs.org/en/) for development
* [Express](http://expressjs.com/) for development



<!-- GETTING STARTED -->
## Getting Started
The app is accessible and useable under njaku01.github.io.


To get a local copy up and running follow these simple steps.

### Prerequisites

Install npm
* npm
```sh
npm install npm@latest -g
```

### Installation

1. Clone the repo
```sh
git clone https://github.com/NJaku01/NJaku01.github.io.git
```
2. Install NPM packages
```sh
npm install
```

3. Start the application
```sh
npm start
```

4. Go to the application under https://localhost:3000


<!-- CONTACT -->
## Contact

[Nick Jakuschona](https://github.com/NJaku01) - [njaku01@wwu.de](njaku01@wwu.de)

Project Link: https://github.com/NJaku01/NJaku01.github.io


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Dr. Markus Konkol](https://github.com/MarkusKonk)
* [Prof. Dr. Christian Kray](https://orcid.org/0000-0002-4199-8976)
* [Laura Goulier](https://orcid.org/0000-0002-0333-6613)