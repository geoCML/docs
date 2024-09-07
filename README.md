# geoCML documentation

This repository hosts the documentation for the geoCML project. geoCML documentation is rendered to HTML and PDF from [Asciidoc](https://asciidoc.org/) files (.adoc) using [docToolchain](http://doctoolchain.org/docToolchain/v2.0.x/index.html). _docToolchain requires that you have Docker installed on your system, as builds are rendered inside of a container._

## Writing new documentation topics

You may choose to extend the default geoCML documentation (distributed with all [geoCML Base Deployments](https://github.com/geoCML/geocml-base-deployment)) as you customize your deployment. All Asciidoc topics are found in the project's topics/ directory. Simply add your new topics as a .adoc file to this directory and build using docToolchain's command line tool.

## How to build your documentation

Requirements:

 - asciidoctor
 - asciidoctor-pdf
 - asciidoctor-diagram

*nix / Bash:
> Run `./gradlew generateHTML generatePDF`

Windows:
> Run `"./gradlew.bat" generateHTML generatePDF`
