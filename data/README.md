# Dataset Documentation

## Dataset Name

Individual Household Electric Power Consumption

## Dataset Source

UCI Machine Learning Repository

Dataset URL: https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

## Dataset Description

This dataset contains measurements of electric power consumption from a household in France, recorded at one-minute intervals between December 2006 and November 2010.

The dataset contains approximately 2.08 million observations.

## Dataset Variables

The dataset includes the following variables:

1. **Date:** Measurement date.
2. **Time:** Measurement time.
3. **Global_active_power:** Household global minute-averaged active power (kW).
4. **Global_reactive_power:** Household global minute-averaged reactive power (kW).
5. **Voltage:** Minute-averaged voltage (V).
6. **Global_intensity:** Household global minute-averaged current intensity (A).
7. **Sub_metering_1:** Energy consumption in the kitchen (Wh).
8. **Sub_metering_2:** Energy consumption in the laundry room (Wh).
9. **Sub_metering_3:** Energy consumption associated with the electric water heater and air conditioner (Wh).

## Data Format

- File: `household_power_consumption.txt`
- Format: Semicolon-separated text
- Sampling frequency: One minute
- Missing measurements: Represented by `?`

## Reproducibility

The raw dataset is excluded from this GitHub repository because of its size.

To reproduce the analysis:

1. Download the dataset from the UCI Machine Learning Repository.
2. Extract `household_power_consumption.txt` if it is compressed.
3. Place the file inside the project's `data/` directory.
4. Run the Jupyter Notebook from the `notebook/` directory.

## Attribution

Dataset: *Individual Household Electric Power Consumption*, UCI Machine Learning Repository.

The original dataset is distributed under the CC BY 4.0 license. Users should acknowledge the dataset creators and follow the applicable attribution requirements.

The analysis, feature engineering, visualizations, and forecasting code in this project will be developed independently.