 Survey Data Viewer – Web-based Interactive Visualization Tool

✨This project is inspired by the research paper:

“A web-based, interactive visualization tool for social environmental survey data”
Published in Environmental Modelling & Software (2016).

The system provides an interactive web interface to explore survey datasets using HTML, CSS, JavaScript (D3.js), and Django. Instead of static charts, users interact with live HTML pages to visualize survey responses dynamically.
Paper: A web-based, interactive visualization tool for social environmental survey data
Journal: Environmental Modelling & Software, 2016

➡️The architecture and idea of this project are derived from the above research work, where survey results are presented as interactive web pages.
How the Architecture Diagram Was Recreated Using HTML & CSS

The original image from the research paper shows a three-layer web architecture:

User Interface Layer (Browser)
Web Framework Layer (Django)
Storage Layer (CSV survey files)

Instead of drawing this in a graphics tool, the same structure was implemented as a web page layout using only HTML and CSS. Each block in the diagram corresponds to a <div> section styled with CSS.

Step-by-Step Mapping (Image → Code)
1️Sections = Layers in the Diagram

The page is divided into two big colored sections:

Yellow section → User Interface Layer
Blue section → Web Framework + Storage Layer
