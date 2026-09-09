# Temporal resolution shapes inferred higher-order interactions and information representation in neural population activity: A data-driven approach using minimally complex models

**Fariba Jangjoo**
Kavli Institute for Systems Neuroscience, Faculty of Medicine and Health Sciences, Norwegian University of Science and Technology, Trondheim, Norway

**Status:** Under review, *PLOS ONE* (submitted 2025)
**Preprint:** [bioRxiv, doi.org/10.1101/2025.03.23.644813](https://doi.org/10.1101/2025.03.23.644813)

## What this is about

Studying how populations of neurons interact is hard when you're limited to pairwise correlations — a lot of the real structure lives in *higher-order* interactions (three, four, or more neurons acting together), which are harder to detect and easy to miss. This project asks a question that's often overlooked in that search: does the **time resolution** you analyze the data at change what interactions you find?

Using a data-driven framework called Minimally Complex Models, I analyzed grid-cell population activity (medial entorhinal cortex) across a wide range of temporal resolutions. The result: at intermediate resolutions (~100 ms), the inferred model captures the most meaningful higher-order structure *and* represents information most efficiently — both too fine and too coarse a resolution lose information. This establishes temporal resolution as a factor that has to be chosen deliberately, not as an arbitrary preprocessing step, when modeling collective neural dynamics.

## Data source

The neural recordings analyzed here (grid-cell populations, medial entorhinal cortex) come from the dataset published by:

> Gardner RJ, Hermansen E, Pachitariu M, Burak Y, Baas NA, Dunn BA, et al. *Toroidal topology of population activity in grid cells.* Nature. 2022;602(7895):123–128.
> Data: [Figshare](https://figshare.com/articles/dataset/Toroidal_topology_of_population_activity_in_grid_cells/16764508) · Code: [GitHub](https://github.com/erikher/GridCellTorus)

All analysis, modeling, and results in this project are my own.
