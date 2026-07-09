# Marshall Characteristics Analysis of Reclaimed Asphalt Pavement (RAP) Modified with Waste Cooking Oil (WCO)

## Overview

This repository contains datasets, R scripts, figures, and supporting files used in my undergraduate research on the effect of Waste Cooking Oil (WCO) as a rejuvenator on Reclaimed Asphalt Pavement (RAP) mixtures based on Marshall characteristics.

The repository was created as part of the Reproducible Research assignment. It demonstrates how research data and analysis can be organized so that other researchers can understand, reproduce, and verify the analysis.

---

## Research Objective

The objectives of this study are:

- Evaluate the effect of RAP content on Marshall characteristics.
- Evaluate the effect of Waste Cooking Oil (WCO) dosage as a rejuvenator on RAP mixtures.
- Analyze the Marshall properties including Stability, Flow, Marshall Quotient (MQ), VIM, VMA, and VFB.
- Perform descriptive statistical analysis and visualize the relationship between RAP content and WCO dosage on asphalt mixture performance.

---

## Repository Structure

```
Marshall-WCO-Reproducible/
│
├── data/
│   └── marshall_data.csv
│
├── script/
│   └── analysis.R
│
├── output/
│   ├── stability_plot.png
│   ├── flow_plot.png
│   ├── VIM_plot.png
│   ├── VMA_plot.png
│   ├── VFB_plot.png
│   ├── MQ_plot.png
│   └── summary_statistics.csv
│
├── README.md
├── sessionInfo.txt
├── LICENSE
└── LICENSE_DATA.txt
```

---

## Data

The repository contains laboratory test data obtained from Marshall testing of asphalt mixtures incorporating RAP and WCO.

The dataset includes the following variables:

- RAP content (%)
- Waste Cooking Oil (WCO) dosage (%)
- Marshall Stability (kg)
- Flow (mm)
- Marshall Quotient (kg/mm)
- Voids in Mineral Aggregate (VMA, %)
- Voids in Mix (VIM, %)
- Voids Filled with Bitumen (VFB, %)

---

## Analysis

The analysis includes:

- Descriptive statistics
- Summary statistics by RAP and WCO content
- Data visualization
- Scatter plots
- Line plots
- Marshall characteristic comparison among mixtures

---

## Software

The analysis was conducted using **R**.

Required packages include:

```
readr
dplyr
ggplot2
```

Additional package information is provided in:

```
sessionInfo.txt
```

---

## How to Run

1. Clone this repository

```
git clone https://github.com/yourusername/Marshall-WCO-Reproducible.git
```

2. Open the project in RStudio.

3. Install required packages (if necessary)

```R
install.packages(c("readr","dplyr","ggplot2"))
```

4. Run the analysis script

```R
source("script/analysis.R")
```

or simply open **analysis.R** and click **Run All**.

---

## License

- Source code is licensed under the MIT License.
- Dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).

---

## Author

**Inggar Fidela Anggraini**

Department of Civil and Environmental Engineering

IPB University

2026
