# Air_Quality_Interpolation
Data Cleaning, Transformation, and Interpolation for Air Quality Time-Series Analysis

- Data Cleaning and Preprocessing:
  - Imported data from CSV, removed completely empty rows and columns, and cleaned columns with significant missing data.
  - Replaced erroneous data entries and transformed object data types for numerical analysis.
  - Combined and formatted date-time columns for chronological ordering and further analysis.

- Data Transformation:
  - Created new columns and pivoted the dataset for time-series analysis, enabling non-overlapping daily time-series representation.
  - Applied data normalization techniques to prepare for modeling and analysis.

- Data Interpolation and Visualization:
  - Implemented cubic spline interpolation for missing hourly data, ensuring smoother and continuous data representation.
  - Visualized both the original and interpolated data for multiple days, aiding in understanding the data trends and patterns.
