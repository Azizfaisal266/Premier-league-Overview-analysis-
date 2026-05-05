## Premier league Overall performance analysis 
This project analyze the player performances and his contribution
## Tools used : 
Microsoft Excel 
Imported and prepared player dataset using Power Query
Renamed columns for better readability (e.g., converting "Age" to "PlayerAge")
Cleaned player age data by extracting only the age value from complex format (e.g., "29-240" → "29")
Used "Column From Examples" to automate data transformation
Changed data types to appropriate formats (e.g., PlayerAge to Whole Number)
Split player positions into separate rows using delimiter (e.g., "FW,AM" → "FW" and "AM")
Reordered and removed unnecessary columns to improve dataset structure
Added index column for better data organization and renamed it to playerID
Ensured the dataset is clean and ready for analysis 
Loaded cleaned tables into Power Pivot
Created relationships between tables (e.g., PlayerID between Fact table and Player_Position Dim table)
Built a data model to handle multiple tables efficiently
Created measuresand Dax functions for analysis
Used Pivot Tables to generate insights from the data model

