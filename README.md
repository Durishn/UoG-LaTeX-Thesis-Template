<!--
*** Thanks for checking out the Ender-README-Template. This repository was forked
*** from othneildrew's Best-README-Template available at
*** https://github.com/othneildrew/Best-README-Template
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** Durishn, UoG-LaTeX-Thesis-Template, University of Guelph Masters Thesis LaTeX Template, An updated LaTeX template which conforms to the University of Guelphs 2020 Masters Thesis formatting requirements, project_url
-->
<!-- To change the stability level, replace 'stable' with 'stable', 'unstable', 'experimental', or 'deprecated'-->

![Project State][stable-shield]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">University of Guelph Masters Thesis LaTeX Template</h3>

  <p align="center">
    An updated LaTeX template which conforms to the University of Guelphs 2020 Masters Thesis formatting requirements
    <br />
    <br />
    <a href='https://www.buymeacoffee.com/nicdurish' target='_blank' style='margin-top:50px;'><img height='30' src='https://az743702.vo.msecnd.net/cdn/kofi1.png?v=0' border='0' alt='Buy Me a Coffee' /></a>
    <br />
    <br/ >
    <a href="https://github.com/Durishn/UoG-LaTeX-Thesis-Template/blob/master/output/thesis.pdf">View Demo</a>
    ·
    <a href="https://github.com/Durishn/UoG-LaTeX-Thesis-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/Durishn/UoG-LaTeX-Thesis-Template/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

As my thesis came to it's completion in August of 2020, I was met with a problematic conflict between the expectations of my department and the school at large. The School of Computer Science and my advisor required that I use LaTeX for my thesis, which was only a problem given that the template that was provided did not abide by the Universities required formatting for a Thesis submitted to the Atrium. A back and forth ensued, before I pulled up my bootstraps and recreated the Thesis Latex Template based off the old one provided from the university.  Since the thesis style guidelines are revised occasionally, you should review them and make sure that your thesis conforms.

This repository includes the Thesis style (`ugthesis_ND.cls`), a template directory for your frontmatter and chapters (`/sections`), a template directory for you bibliography, docs, and images (`/bibliography`, `/doc`, and `/images`) a template for the thesis
(`thesis_final.tex`).

### Built With

This project was built with the use of the following frameworks.
* [latexmk](https://mg.readthedocs.io/latexmk.html)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Before using this software, ensure you have the necessary prerequisites:
* latexmk: if you're on linux or windows, you already have it. If you're on Mac, enter the following
  ```sh
  sudo tlmgr install latexmk
  ```

### Installation

* Clone the repo
   ```sh
   git clone https://github.com/Durishn/UoG-LaTeX-Thesis-Template.git
   ```

### Building

* Use the following command to build the project
  ```sh
  latexmk -pdf -quiet -f -jobname=./output/thesis ; latexmk -pdf -quiet -c -jobname=./output/thesis
  ```


<!-- USAGE EXAMPLES -->
## Usage

The following options may be used within the main `.tex` file to build this template under different contexts

- `draft`: Do not build hyper links, include graphics, and highlight over full boxes.
Used by the underlying memoir class and other packages.

- `final`: Hide all hyperlinks.  Option is also used by other packages

- `10pt`: Typeset the body of the thesis using a 10 point font (default)

- `11pt`: Typeset the body of the thesis using a 11 point font

- `12pt`: Typeset the body of the thesis using a 12 point font

- `boxlink`: Draw coloured boxes around the hyperlinks (including citations and cross
references) instead of colouring the text

- `single`: Typeset the body text of the thesis single spaced (default)

- `onehalf`: Typeset the body text of the thesis with one and a half spacing

- `double`: Typeset the body text of the thesis double spaced

- `ebook`: Used by the underlying memoir class.  Format the thesis with a smaller page
size suitable for reading on tablets and e-readers.  Single spacing and a 10pt
font are strongly recommended with this option.  Also note that the maximum
size for a diagram is:  100mm x 174mm.

- `modern`: Format the thesis on letter sized paper with LaTeX's default margins.  It works
out to about 1.5" on all sides and is generally considered to be the easiest to
read. (default)

- `traditional`: Format the thesis on letter sized paper with 1" margins on the top bottom and
right, and a 1.5" on the left (for binding).  This is the more traditional
style, commonly used with word processors.



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/Durishn/UoG-LaTeX-Thesis-Template/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- Authors -->
## Authors
Nic Durish - [@Durishn](https://twitter.com/Durishn) - [mail@nicdurish.ca](mailto:mail@nicdurish.ca)

See the [contributors](https://github.com/Durishn/UoG-LaTeX-Thesis-Template/contributors) page for an updated list of contributors to this project



<!-- LICENSE -->
## License
Distributed under the MIT License. See [`LICENSE`][license-url] for more information.



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->


[stable-shield]: https://img.shields.io/badge/stability-stable-green.svg
[unstable-shield]: https://img.shields.io/badge/stability-unstable-yellow.svg
[deprecated-shield]: https://img.shields.io/badge/stability-deprecated-orange.svg
[experimental-shield]: https://img.shields.io/badge/stability-experimental-red.svg

[contributors-shield]: https://img.shields.io/github/contributors/Durishn/UoG-LaTeX-Thesis-Template.svg
[contributors-url]: https://github.com/Durishn/UoG-LaTeX-Thesis-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Durishn/UoG-LaTeX-Thesis-Template.svg
[forks-url]: https://github.com/Durishn/UoG-LaTeX-Thesis-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/Durishn/UoG-LaTeX-Thesis-Template.svg
[stars-url]: https://github.com/Durishn/UoG-LaTeX-Thesis-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/Durishn/UoG-LaTeX-Thesis-Template.svg
[issues-url]: https://github.com/Durishn/UoG-LaTeX-Thesis-Template/issues
[license-shield]: https://img.shields.io/github/license/Durishn/UoG-LaTeX-Thesis-Template.svg
[license-url]: https://github.com/Durishn/UoG-LaTeX-Thesis-Template/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-Github-black.svg?logo=github&colorB=555
[linkedin-url]: https://github.com/Durishn
[product-screenshot]: docs/images/screenshot.png
