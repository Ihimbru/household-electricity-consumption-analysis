# Data

The dataset used for this analysis was provided for academic purposes as part of the **Project Learning from Data** course at Hasselt University.

The original dataset is **not included in this public repository**. This repository therefore focuses on the statistical analysis, modelling workflow, visualisations and interpretation of results.

## Expected File Structure

To reproduce the analysis locally, the R Markdown file expects the dataset at:

```text
data/data_students.txt
```

The analysis uses the following main variables:

* `annual_kwh` — annual household electricity consumption
* `sq_meters` — living area
* `epc_label` — Energy Performance Certificate rating
* `building_era` — building construction period
* `income_euro` — household income
* `occupancy_count` — number of household occupants
* `dist_to_brussels` — distance to Brussels
* `roof_color` — roof colour
* `pet_ownership` — household pet ownership

## Analytical Sample

After the required group-specific row removal, complete-case analysis and removal of five apparent data-entry errors in annual electricity consumption, the final analytical dataset contained **2,477 households**.
