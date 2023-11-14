[![CC BY 4.0][cc-by-shield]][cc-by]
# GCW Data Portal Overview

## Introduction
This document provides a high level overview of the GCW portal.

Automatic processing from the source documents in ASCIIDOC to PDF and HTML is set up when changes to the documents are submitted, as well as automatic generation of diagrams using plantuml. The most recent versions of the documentation is available below:

- [PDF](https://github.com/GlobalCryosphereWatch/dataportaloverview/blob/master/doc/gcw-add.pdf)

## License
This information is licensed under the terms of the [Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

## How to build the PDF and HTML
ASCIIDOC documents can be converted into other formats using asciidoctor. This is available for both Linux and Windows environments. In order to create a PDF document asciidoctor-pdf is used. The Makefile in this repository will perform the conversion of the ASCIIDOC code to a PDF document provided you have access to asciidoctor.

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
