# style-eis-latex
LaTeX style for the Chair of Electronic Design Automation at RPTU in Kaiserslautern

This template is a modified version of the TUK-EIT department template by Christian De Schryver, Matthias Jung and Julian Puderbach


## Build
There is nothing to build right here in this repository. It is included as a submodule into the document templates where required.
However, if you really want to use it directly in your own documents, you can do so by including:

```
% for English documents (standard)
\usepackage{style-eis-latex/EIS}

```

or

```
% use [de] option for German documents
\usepackage[de]{style-eis-latex/EIS}

```

## Known Dependencies
* submodule RedHatText - Fonts
   * clone with `git clone --recursive` if font download is desired
* LaTeX packages
   * texlive-science

