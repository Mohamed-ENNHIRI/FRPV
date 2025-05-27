# FRPV - Rooftop Photovoltaic System Detection Results Viewer

## Overview

Welcome to the FRPV repository! This project hosts an interactive map tool designed to visualize the results of the comprehensive research on Rooftop Photovoltaic (RPV) system detection across French territories.

The visualization is based on the findings from the paper:

**"A comprehensive building-wise rooftop photovoltaic system detection in heterogeneous urban and rural areas: application to French territories"** [cite: 1]
by Martin Thebault, Boris Nerot, Benjamin Govehovitch, and Christophe Ménézo.
Published in *Applied Energy, 388 (2025) 125630*. [cite: 1]

**Access the Interactive Map Visualization:**
[https://mohamed-ennhiri.github.io/FRPV/avec_carte.html](https://mohamed-ennhiri.github.io/FRPV/avec_carte.html)

## About the Research

The foundational research for this visualization introduces a novel methodology for identifying RPV systems. It utilizes a convolutional neural network (CNN) trained on high-resolution aerial imagery and building registry data. [cite: 6] A key aspect of this study is its building-by-building approach, ensuring individual assessment for each structure, as an alternative to traditional tile-based methods. [cite: 7]

Key highlights of the research include:
* A detailed, building-by-building approach to detect rooftop PV systems using aerial images. [cite: 1]
* A comprehensive analysis of RPV systems across diverse metropolitan French territories, covering both urban and rural areas. [cite: 2]
* The model processed images of over 40 million buildings, identifying approximately 600,000 RPV systems across the entire metropolitan French territory. [cite: 10]
* The study found high detection accuracy, though performance can be influenced by factors such as roofing material (e.g., better accuracy on tiled roofs compared to slate roofs) and local urban characteristics. [cite: 9, 11]
* The neural network's performance was shown to improve with the use of heterogeneous training data, accounting for France's diverse architectural styles. [cite: 3, 8, 53, 60]
* The research provides open-access datasets and tools to promote reproducible research in PV identification. [cite: 3, 67, 68]

## Data Source for the Visualization

The data displayed by this interactive map is derived from the prediction results of the CNN model presented in the research paper. [cite: 441] Specifically, it shows the identified locations of RPV systems on buildings across metropolitan France. [cite: 10, 56]

The original authors have made their research data and models publicly accessible:
* **Training material and the CNN model:** Accessible at [https://doi.org/10.57745/CH6QN4](https://doi.org/10.57745/CH6QN4) [cite: 440]
* **Prediction results for the metropolitan French territory (primary data for this visualization):** Accessible at [https://doi.org/10.57745/BXXYW4](https://doi.org/10.57745/BXXYW4) [cite: 441]
* **Dataset of individual building images for French departments:** Accessible at [https://doi.org/10.57745/V2LFQS](https://doi.org/10.57745/V2LFQS) [cite: 442]
* **Original research code:** The Python code used in the study is available on GitHub under an AGPL-3.0 license (see paper for specific link [cite: 439]).

## How to Use This Visualization Tool

1.  Navigate to the interactive map: [https://mohamed-ennhiri.github.io/FRPV/avec_carte.html](https://mohamed-ennhiri.github.io/FRPV/avec_carte.html)
2.  Explore the map to see the locations of detected RPV systems.
    

## Citing the Original Research

If you use the underlying data or insights that this visualization tool is based upon, please ensure you cite the original scientific publication:

Thebault, M., Nerot, B., Govehovitch, B., & Ménézo, C. (2025). A comprehensive building-wise rooftop photovoltaic system detection in heterogeneous urban and rural areas: application to French territories. *Applied Energy, 388*, 125630. [cite: 1]
DOI: [https://doi.org/10.1016/j.apenergy.2025.125630](https://doi.org/10.1016/j.apenergy.2025.125630) [cite: 19]


## Acknowledgements

* This visualization tool is made possible by the extensive research and openly shared data from Martin Thebault, Boris Nerot, Benjamin Govehovitch, and Christophe Ménézo. [cite: 3, 12, 66, 67]
* The original research was supported by the French National Research Agency under the "Investissements d'Avenir" programme (ref. ANR-18-EURE-0016 Solar Academy). [cite: 436]

---
