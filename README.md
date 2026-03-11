# Animal Dataset Cleaning Project

This project is all about cleaning a messy dataset of animal observations across Europe. The CSV had missing values, inconsistent column names, numbers stored as text, and even a completely empty column (`Animal_Code`), which I decided to remove after inspecting the data. The dataset is now fully ready for analysis.

## What I Did

- Standardized column names and fixed typos (e.g., `Body Length cm` → `Body_Length_cm`).
- Replaced string `"NaN"` and blank cells with actual missing values (`NaN`).
- Filled missing categorical values (`Gender`, `Animal_Type`, `Animal_name`, `Country`) with the **mode** or `"Unknown"`.
- Converted numeric columns (`Weight_kg`, `Body_Length_cm`, `Latitude`, `Longitude`) to numeric and filled missing values with the **mean**.
- Converted `Observation_Date` to datetime and filled missing dates with a fixed placeholder (`2024-01-01`).
- Noticed `Animal_Code` was completely empty and removed it from the dataset.
- Verified that no missing values remain and the dataset is ready for analysis.

## Outcome

- Dataset is fully cleaned and ready for analysis.
- No more errors when analyzing or visualizing data.
- Ready for plotting, modeling, or further data exploration.
