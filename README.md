# Concentration-Camp-Legacy-Effects

# This repository is a work in progress, and all materials and analyses have not yet been loaded. Please contact Bryan Lockwald at lockwald@unlv.nevada.edu with questions and requests for information.

# Replication Materials for "Locating the Far Right- A Geospatial Analysis of Support for the AFD in Germany"

## Authors
- **Bryan Lockwald**
  Ph.D. Candidate, UNLV 
- **Dr. Christian Jensen**
  Associate Professor, UNLV
- **Matthew Gomez**
  Ph.D. Candidate, UNLV

## Overview
This repository contains the replication materials for our response and extension to:

> Homola, Jonathan, Miguel M. Pereira, and Margit Tavits. 2020. “Legacies of the Third Reich: Concentration Camps and Out-Group Intolerance.” *American Political Science Review* 114(2): 573–90. [doi:10.1017/S0003055419000832](https://doi.org/10.1017/S0003055419000832).

We argue that Homola et al. are primarily capturing the effects of **ruralness** rather than the proximity to former Nazi concentration camps on support for the far-right Alternative für Deutschland (AfD) party in Germany. Our analysis demonstrates that:

- **Unemployment rates** and the **presence of immigrants** have an effect on far-right support that is **orders of magnitude larger** than the proximity to former concentration camps.
Using a similar model specification, we show that the effects reported by Homola et al. are only statistically significant in the bottom third of municipalities by population size. When splitting municipalities into low, medium, and high population tiers, the effect disappears in the more populated areas.
- Using the replication data from Homola et al., we analyze the geographic distribution of support for the AfD party using Moran’s I and Local Indicators of Spatial Autocorrelation (LISA). Our findings show that fewer than 50% of former Nazi concentration camps are located near clusters of AfD support, further challenging the argument that proximity to these historical sites significantly influences far-right voting behavior. 

## Repository Structure
- **`/data/`**: Contains raw and processed datasets.
- **`/code/`**: Stata and R scripts for data processing, model estimation, and visualization.
- **`/output/`**: Contains tables, figures, and regression results.
- **`README.md`**: This file.

## Reproducing the Analysis
### Requirements
- **Software**: This project primarily uses **Stata** and **R**.
- **Dependencies**: Required R packages are listed in the first code block of the Quarto document titled "
- **Data Access**: Some datasets may not be publicly available due to restrictions. Please refer to `data/README.md` for details.

### Steps to Run the Code
1. Clone this repository:  
   ```sh
   git clone https://github.com/your-repo-link.git
   cd your-repo-folder

	2.	Open Stata and execute:

do code/main_analysis.do


	3.	In R, open code/main_analysis.R and run:

source("code/main_analysis.R")



Citation

If you use this code or data in your own work, please cite our paper:

	[Lockwald, Jensen, and Gomez, Year, Paper Title]

Contact

For questions or collaborations, feel free to contact Bryan Lockwald at lockwald@unlv.nevada.edu.

⸻

Let me know if you want any modifications!
