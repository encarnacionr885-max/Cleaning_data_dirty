# Animal Dataset Cleaning Project

This project is basically me cleaning a messy animal dataset from Europe. The CSV was full of missing values, column names all over the place, and numbers saved as text. So I cleaned it up so I can actually use it for analysis.

## What I Did

- Fixed column names and typos so everything is consistent (like `Body Length cm` → `Body_Length_cm`).  
- Turned string `"NaN"` and empty cells into real missing values (`NaN`).  
- Filled missing stuff in categorical columns (`Gender`, `Animal_Type`, `Animal_name`, `Country`) using the most common value or just `"Unknown"`.  
- Converted numeric columns (`Weight_kg`, `Body_Length_cm`, `Latitude`, `Longitude`) to numbers and filled missing values with the mean.  
- Converted `Observation_Date` to proper datetime and filled missing dates with `2024-01-01`.  
- Double-checked everything to make sure no missing values are left and all columns are ready to go.

## Outcome

- The dataset is now fully cleaned and ready to use.  
- No more errors when analyzing or plotting.  
- Ready for exploring, making charts, or any kind of modeling I want.
