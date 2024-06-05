<br />
<div align="center">
  <a href="https://github.com/RPTU-EIS/thesis-template">
    <img src="images/EIS-Logo.png" alt="Logo" height="200">
  </a>
  <h3 align="center">
  Thesis Template
  <br />
  Chair of Electronic Design Automation 
  </h3>

  <p align="center">
    University of Kaiserslautern (RPTU)
    <br />
    <br />
    <a href="https://github.com/RPTU-EIS/thesis-template/issues">Report Bug</a> 
  </p>
</div>

<br />


## About
This LaTeX thesis template is based on the template provided by the Department of Electrical and Computer Engineering at RPTU Kaiserslautern-Landau, designed by Christian De Schryver, Matthias Jung and Julian Puderbach.

## How to use
This LaTeX report template can be used easily with any TeX distribution by running ```make``` or with any LaTeX IDE. Just start with the file ```main.tex``` and go ahead with your changes. Everything is documented in the file itself.

*Important*: This repository depends on a Git submodule (style-eis-latex/RedHatFont) that holds the font used by RPTU. Therefore, a regular ```git clone``` command is not sufficient to obain the submodule as well! Please use ```git clone --recursive``` instead.



## Build
Use your favorite LaTeX IDE / editor or optionally open a terminal and use make. 

The template has been tested and successfully compiled with TeX Live, LuaTeX (Version 1.10.0) and BibTeX.


## Known Dependencies
* texlive-science
* texlive-fonts-extra
* Git submodule RedHatFont
