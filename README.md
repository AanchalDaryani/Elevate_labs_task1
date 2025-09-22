📝 Project: Netflix Movies & TV Shows Dataset Cleaning

🔹 Key Steps Performed

1️⃣ Handling Missing Values:
Filled missing values in Director, Cast, and Country with placeholders (Not Available / Unknown).
Removed rows with missing values in critical columns: Rating, Duration, and Date_Added.

2️⃣ Duplicate Records:
Checked for duplicate rows and confirmed that there were no duplicates in the dataset.

3️⃣ Standardizing Text:
Cleaned textual data in columns like Country, Type, and Rating to remove extra spaces and standardized capitalization.

4️⃣ Column Renaming:
Renamed column headers to a clean, uniform format using Title Case with underscores (e.g., Show_Id, Release_Year, Date_Added).

5️⃣ Data Type Conversion:
Converted Show_Id and Release_Year to integers.
Converted Date_Added to datetime format for consistency.

6️⃣ Indexing:
Set Show_Id as the DataFrame index for better data referencing.

✅ Outcome:
The cleaned dataset is consistent, free of critical nulls, properly typed, and ready for analysis or visualization, ensuring reliable insights can be derived from Netflix movies and TV shows data.
