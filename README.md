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

## TL;DR
* **Clone**: ```git clone --recursive https://github.com/RPTU-EIS/thesis-template.git```
* Before using the template with **Overleaf**, follow the steps in [Using the Template with Overleaf](#using-the-template-with-overleaf)!
* In Overleaf, you need to make sure to choose "LuaLaTeX" as the compiler and "binder.tex" as the main document in order to build the PDF file.

## About
This LaTeX thesis template is based on the template provided by the Department of Electrical and Computer Engineering at RPTU Kaiserslautern-Landau, designed by Christian De Schryver, Matthias Jung and Julian Puderbach.

## How to use
This LaTeX report template can be used easily with any TeX distribution or with any LaTeX IDE. Just start with the file ```binder.tex``` and go ahead with your changes. Everything is documented in the file itself.

*Important*: This repository depends on a Git submodule (style-eis-latex/RedHatFont) that holds the font used by RPTU. Therefore, a regular ```git clone``` command is not sufficient to obain the submodule as well! Please use ```git clone --recursive``` instead.

## Using the Template with Overleaf
The included subrepositories are quite large and will prevent Overleaf from compiling or even make the upload impossible. When using Overleaf, a lot of functionality in this repository is not necessary and can be removed. This is done by executing the ```cleanup.py``` script. Do not run this script if you won't
use Overleaf afterwards, as the script will also remove all git functionality!

In Overleaf, you need to make sure to choose "LuaLaTeX" as the compiler and "binder.tex" as the main document in the top-left menu in order to build the PDF file.

## Build
Use your favorite LaTeX IDE / editor or optionally open a terminal and use make. 

The template has been tested and successfully compiled with TeX Live, LuaLaTeX (Version 1.10.0) and BibTeX.


## Known Dependencies
* texlive-science
* texlive-fonts-extra
* Git submodule RedHatFont
