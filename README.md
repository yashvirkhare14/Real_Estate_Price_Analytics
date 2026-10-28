# Real_Estate_Price_Analytics
A Complete Data Analysis Project Using Python

📌 Project Overview
- This project studies house data to find the main factors that affect house prices.
- It shows the main steps of data analysis, such as cleaning data, handling missing values, exploring the data (EDA), making charts, and finding useful business insights with Python.
- The dataset has real-world data issues, such as missing values and unusual values called outliers. This makes the project useful for learning skills needed for data analyst jobs

🎯 Project Objectives
- Clean and prepare the original house data.
- Handle missing values using suitable statistical methods.
- Explore the data (EDA) to understand it better.
- Create charts using Matplotlib and Seaborn.
- Find the factors that affect house prices.
- Share useful insights that can support business decisions.

🛠️ Skills & Tools Used
- Python
- NumPy
- Pandas
- Data Cleaning and Preparation
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- Data Visualization
- Matplotlib
- Seaborn
- Business Data Analysis

📂 Dataset Information
Dataset Name: King County House Sales Dataset (with missing values)
Rows: 21,613
Columns: 22
Target Variable: price

Key Features:
- Property Size: sqft_living, sqft_lot — the size of the living area and the land.
- House Structure: bedrooms, bathrooms, floors — the number of bedrooms, bathrooms, and floors.
- Quality: grade, condition — the house's build quality and current condition.
- Location: zipcode, waterfront, view — location details, whether the house is near the water, and its view.
- Building and Renovation: yr_built, yr_renovated — the year the house was built and the year it was renovated.

🔍 Project Workflow
1️⃣ Data Loading and Understanding
- Loaded the dataset using Pandas.
- Checked the number of rows and columns, data types, and summary statistics.
- Looked for unnecessary data and missing values.

2️⃣ Data Cleaning and Preparation
- Removed the extra index column (Unnamed: 0).
- Changed the date column to a date format.
- Checked number-based and category-based columns.

3️⃣ Handling Missing Values
Missing values were found in:
1. bedrooms
2. bathrooms
Method Used:
- Missing values were filled using the median (the middle value). This method helps keep the data's overall pattern and reduces the effect of unusually high or low values.

4️⃣ Exploratory Data Analysis (EDA)
The analysis used these charts:
1. Histograms
2. Scatter plots
3. Box plots
4. Correlation heatmaps
Main topics studied:
1. How house prices are spread across the dataset.
2. How house price is related to living area.
3. How bedrooms, bathrooms, and grade relate to price.
4. How renovation, waterfront, and view relate to price.
5. How prices change by location.

5️⃣ Creating New Features
- New columns were created to make the analysis more useful:
- house_age — the age of the house.
- is_renovated — shows whether the house was renovated.
- price_per_sqft — price for each square foot, used to compare house prices more fairly.

6️⃣ Analysis by Price Group
Houses were compared in these groups:
- Budget homes
- Mid-range homes
- Luxury homes
- This helped show how prices differ between the groups of houses.

7️⃣ Data Visualization Dashboard
- A simple dashboard was created using:
  - Matplotlib
  - Seaborn
- The dashboard shows the main findings in a clear way, including for people who do not work with data every day.

📊 Key Insights
1. Living area (sqft_living) has the strongest link with house price.
2. House build quality (grade) has a major effect on price.
3. Bathrooms have a stronger link with price than bedrooms.
4. Renovated houses and houses near the water are often in the higher-price group.
5. Land size alone has a smaller effect on price.

📈 Business Recommendations
1. Focus on improving house build quality instead of only adding more bedrooms.
2. Renovation may help increase a house's value.
3. Houses near the water or with a good view should be presented as premium properties.
4. Buyers should pay attention to living area, not only the number of rooms.

⚠️ Limitations and Assumptions
Limitations:
- House prices were not adjusted for inflation.
- Location details are limited to ZIP code level.
- The project does not include a model for predicting house prices.
Assumptions:
- The data represents normal market conditions.
- There were no major changes in the economy during the period covered by the data.
