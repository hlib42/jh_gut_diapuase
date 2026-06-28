# Analysis of Drosophila Guts in Diapuse
This repository contains the data and code for a 2×2 Factorial Design analysis that looks into the effects of Temperature (11°C vs 25°C) and hormone treatments (Juvenile Hormone vs EtOH (vehicle)) on *Drosophila melanogaster* midgut morphology, PH3+ cell counts, and Delta (Dl+) marker proportions.
## Repository Structure

- `diapause_gut_analysis.qmd`: The primary Quarto source code document containing all data tidying, statistical models (Kruskal-Wallis, Dunn's post-hoc, Beta regression, and Logistic regression), and ggplot2 visualization code.
- `diapause_gut_analysis.html`: Fully rendered HTML report including all embedded figures, statistical outputs, and code folding.
- `data/Current Slides - Guts.csv`: The raw input dataset used for this study.

## How to Reproduce

1. Clone or download this repository.
2. Ensure you have **R** and **RStudio** installed.
3. Install the required R packages by running the following command in your R console:
   ```r
   install.packages(c("tidyverse", "ggpubr", "rstatix", "patchwork", "betareg", "broom"))
