# GeoPython 2025: Geospatial analysis tools to connect every school to the internet

Training materials for an ITU provided workshop as part of the GeoPython 2025 conference:

[GeoPython 2025](https://2025.geopython.net/), Basel – Switzerland, 24-26 February 2025

<a href="https://ibb.co/yW090yp"><img src="https://i.ibb.co/4PWqWT2/windhoek-fiber.png" alt="windhoek-fiber" border="0"></a>

_Figure: Fiber path simulation in Windhoek, Namibia_

## Table of Contents

1. [Overview](#overview)
2. [Training-agenda](#training-agenda)
3. [Pre-requisites](#pre-requisites)
4. [Setup Instructions](#setup-instructions)
   - [Run Locally](#to-run-notebooks-locally)
   - [Run on Google Colab](#to-run-notebooks-on-google-colab)
5. [Usage Notes](#usage-notes)
6. [Contributing](#contributing)
7. [Acknowledgements](#acknowledgements)
8. [License](#license)
9. [Contact](#contact)

## Overview

This repository contains links to slides hosted on a [Google Drive folder](https://drive.google.com/drive/folders/1-4AfC8c9T6JMUHEtFtCyKlLG3kGGERIL?usp=sharing) and Jupyter notebooks for a workshop on infrastructure mapping and analysis. The workshop covers an introduction to GIS systems, data standardization, visualization, coverage analysis, fiber path modeling, and cost estimation.

## Training agenda

- **Slides:**
    - [`ITU broadband connectivity planning tools`](https://docs.google.com/presentation/d/11Zyl1DhpP4KbRYcbHlPyPV0w-fLUyDur/edit?usp=drive_link&ouid=110166480978407115454&rtpof=true&sd=true): Overview of ITU connectivity planning tools for schools

<img src="https://i.ibb.co/Bjq6d7Y/slide-snapshot.png" alt="slide-snapshot" border="0">

- **Jupyter Notebooks:**
    - [`0_get_open_data.ipynb`](0_get_open_data.ipynb): Get open data on ICT infrastructure and standardize it
    - [`1_proximity_coverage_demand.ipynb`](1_proximity_coverage_demand.ipynb): Analysis of coverage proximity and demand mapping
    - [`2_visibility_analysis.ipynb`](2_visibility_analysis.ipynb): Visibility and line-of-sight analysis for network planning
    - [`3_fiber_modeling.ipynb`](3_fiber_modeling.ipynb): Fiber network modeling and optimization
    - [`4_cost_modelling.ipynb`](4_cost_modelling.ipynb): Cost estimation and financial modeling

## Pre-requisites

To run the Jupyter notebooks on **Google Colab**, you'll need:
- A Google account (e.g. a Gmail account).

To run these notebooks **locally**, you'll need:

- Python 3.9
- Jupyter Notebook/Lab

## Setup instructions

### To run notebooks locally

1. Clone the repository:

```bash
git clone https://github.com/FNS-Division/geopython-2025.git
cd geopython-2025
```

2. Create and activate the Conda environment:

```bash
conda env create -f environment.yml
conda activate inframaptraining
```

3. Launch Jupyter:

```bash
jupyter lab
```

### To run notebooks on Google Colab

All notebooks are created using Google Colab for easy accessibility. In order to run them on [Google Colab](https://colab.research.google.com/), you will need to sign in with a Google account. If you are unfamiliar with Google Colab, please watch this [introductory video](https://www.youtube.com/watch?v=inN8seMm7UI).

1. Navigate to each notebook in the repository
2. At the top of each notebook, click on the **Open in Colab** button.

<a href="https://colab.research.google.com/" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Usage notes

Follow the notebooks in numerical order for the best learning experience.

## Contributing

Please submit a pull request to contribute to this repository.

## License

Please refer to our [license](LICENSE).

## Contact

For questions or support, please create an issue in this repository or get in touch at [fns@itu.int](fns@itu.int).