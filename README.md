# Data-preparation-with-Power-Query
This repository includes a general strategy for preparing raw data for analysis using Power Query, along with an illustrative example.
## About Power Query
Power Query is a highly flexible and potent data transformation tool offered by Microsoft. It can be accessed through various Microsoft products, including Microsoft Excel and Power BI. Its exceptional versatility makes it an invaluable tool for data preparation.
## Why data preparation matters
Preparing data is an essential preliminary step before analysis, minimizing errors and inconsistencies while enhancing dataset comprehension and the potential for uncovering valuable insights. Additionally, Well-prepared data offers enhanced flexibility in performing operations such as filtering, sorting, and aggregating.
## Description of well-prepared datasets 
Consistency is crucial for well-prepared datasets, both in terms of structure and content. Structurally, datasets should adopt a tabular format where each row corresponds to a distinct observation, and each column represents a unique attribute associated with that observation. A descriptive header should identify each column, defining its attribute. Furthermore, including a first column of identifiers linked to each observation is considered good practice. In terms of content, well-prepared data exhibit consistency in data types, formatting, and values.
## General approach to prepare datasets from Excel files
When inspecting raw data from Excel files, two types of inconsistencies may be encountered: structure inconsistencies and content inconsistencies. The following approach involves addressing structure inconsistencies first, followed by resolving content inconsistencies.
### Structure inconsistencies
Raw data can be organized in various ways, making it difficult to propose a generalized approach to address all structural inconsistencies. However, a combination of the following operations is typically sufficient to transform raw data into a structurally sound dataset:
+ Table transpositions
+ Column unpivoting
+ Column merging or splitting
+ Adding/removing columns or rows
+ Renaming headers

To become proficient in determining the appropriate transformations to apply based on the structure of a raw Excel file, practical experience is necessary. To facilitate this process, we present two commonly encountered structural inconsistencies in raw Excel data and report their transformation into well-prepared datasets.

Example 1 demonstrates the treatment of a common structural inconsistency where columns are associated with multiple levels of headers.

### Content inconsistencies
Once the table structure has been adjusted, the next step is to address content inconsistencies. The following are the most common adjustments to consider:
+ Removing duplicate records
+ Removing unnecessary spaces in cell values
+ Correcting data format
+ Handling missing values
+ Removing special characters
+ Standardasing text case
+ Correcting typos





