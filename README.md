# GRAIN
data.csv contains cleaned data
GRAIN.DOCX contains data after kniting
GRAIN.Rmd is the R markdown code
GRAIN---Land-grab-deals---Jan-2012-2 is the dataset

## Based on the output of head(), str(), and summary() functions, here are some observations and potential issues in the data:

The Hectares variable is of numerical data type, which is good. However, there seems to be a very wide range of values, with the minimum at 200 hectares and the maximum at 3,200,000 hectares. This suggests that there may be outliers in the data that need to be investigated and potentially removed.

The Year variable is also of numerical data type, which is good. However, the minimum value is 0, which is not a valid year. This suggests that there may be missing or incorrect data in this variable.

The Projected investment variable has a lot of missing values (indicated by "NA" in the output). Depending on the analysis, these missing values may need to be handled or imputed in some way.

The Landgrabbed, Landgrabber, Base, Sector, Production, Status of deal, and Summary variables are all of character data type, which is reasonable given their nature as textual descriptions. However, there may be formatting or spelling errors in these variables that need to be checked and potentially corrected.

The Sector variable seems to have multiple values separated by commas in some cases. This may cause issues in data analysis and may need to be addressed, such as by splitting the values into separate variables or categories.

Based on these observations, some potential data cleaning tasks that could be performed include:

      Investigating and potentially removing outliers in the Hectares variable.

      Checking and correcting any missing or incorrect data in the Year variable.

      Handling or imputing missing values in the Projected investment variable, depending on the analysis.

      Checking and correcting formatting or spelling errors in the Landgrabbed, Landgrabber, Base, Sector, Production, Status of deal, and Summary variables.

