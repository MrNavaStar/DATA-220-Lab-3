## Purpose

This project summarizes occupancy information for campus spaces. The R script reads a CSV file and reports the number of records, total and occupied seats, overall occupancy rate, and the busiest observed space.

## Data

The project uses **synthetic teaching data** rather than real campus information. The tracked sample is:

`data/samples/campus_spaces.csv`

The sample contains 12 campus spaces with information about buildings, space types, seating capacity, occupancy, and noise level.

## Repository Structure

* `scripts/` — Contains the R script used to summarize the data.
* `data/sample/` — Contains the sample dataset used by the project.
* `docs/` — Reserved for project documentation.
* `outputs/` — Reserved for generated outputs. This script does not create an output file.

## Requirements

* R 4.5.1
* No additional R packages are required. The script only uses functionality included with base R.

## How to Run

Run the following command from the **repository root**:

```bash
Rscript scripts/summarize_spaces.R data/samples/campus_spaces.csv
```

## Expected Result

Using the included sample data, the script should report:

* **Rows:** 12
* **Total seats:** 278
* **Occupied seats:** 214
* **Available seats:** 64
* **Occupancy rate:** 77.0%
* **Busiest observed space:** S103

Space S103 is the busiest based on its percentage of occupied seats relative to its total capacity.

## Outputs

The script prints its summary directly to the terminal. It does **not** create a result file, so the `outputs/` directory remains unchanged when the script is run.

