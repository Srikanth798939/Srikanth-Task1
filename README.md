#Task-1

A brief description of what i did in Sales-Export dataset

**Table of content**

 Taking a dataset from kaggle (Dataset Name- Sales -Export_2019-2020).
 after importing dataset into jupyter notebook
**steps**
   
**1. Standardized Country Names**
Cleaned the 'country' column by stripping whitespace and converting all values to lowercase.
Mapped inconsistent or abbreviated country names (e.g., 'UK', 'u.s.a.') to standardized values (e.g., 'United
Kingdom', 'United States').
Capitalized names for presentation (e.g., 'united kingdom' -> 'United Kingdom').
**2. Formatted Dates Consistently**
Converted the 'date' column to a standard datetime format.
Reformatted all dates to a consistent 'dd-mm-yyyy' format for clarity.
**3. Renamed Column Headers**
Standardized column names by
Removing leading/trailing whitespace.
Converting to lowercase.
Replacing spaces with underscores (e.g., 'Order Value EUR' -> 'order_value_eur').
**4. Checked and Fixed Data Types**
Ensured columns like  'date' were correctly typed:
Ensured dates were parsed as datetime objects.
