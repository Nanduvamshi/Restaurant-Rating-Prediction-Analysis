# Restaurant - Exploratory Data Analysis
![307020272-955223f3-3c28-4027-aa0b-74ae3e93b6f1](https://github.com/user-attachments/assets/25688860-5f1b-49a5-af8b-d81ad4cd1dd3)
This Analysis includes 3 levels of tasks to perform.It contains analysis of restaurants and factors affecting their ratings. The main objective was to gather meaningful insights by conducting exploratory data analysis on the large restaurant dataset, as well as build a ML model to predict ratings. This github repo contains all files that includes necessary data exploraton, preprecessing and various visualization methods.
# Dataset
Dataset is uploaded in repo
# Platform used
Jupyter Notebook
# Libraries and Tools
pandas, numpy, matplotlib, seaborn, scikitlearn, folium, geopanda
# Data Preprocessing & Feature Engineering
- Cuisines had 9 null values. So dropped the rows
- Removed features that will inhibit model performance
- Split training data and test data in the ratio 8:2
- Some features/columns needed label encoding
# Model Training and Performance
- Used Random Forest, Decision Tree Logistic Regression algorithms to build the models
- My restaurant rating prediction model (Random Forest and Decision Tree) obtained an aggregate R2 score of 0.93
# EDA : Insights
(Analysis and task wise conclusions are given in repo folders in detail.)

- There are many restaurants having 0 rating probably due to less popularity.
- Visualized the geospatial distribution of restaurants on the map coordinates using folium and geopanda
- Most popular restaurants come in the range of ratings 3 to 3.5.
- Expensive restaurants (higher price range) tend to have higher ratings.
- New Delhi has the highest number of restaurants.
- By country, country code “1”, probably North America has most no of restaurants.
- 'North Indian' is the most popular cuisine overall, followed by "Chinese" and "fast food".
- Restaurants having table booking facility have fairly higher average rating.
- “Sunda” is the highest rated cuisine and also has the most votes.

# Some visualizations for reference
![307020452-996ef9a6-327b-4c53-a560-19016ec9fe0f](https://github.com/user-attachments/assets/9589141b-0924-4427-8b3b-c5abc0d83423)
![307020587-df299531-addb-4a07-b54b-2b896dc9136a](https://github.com/user-attachments/assets/4af8ce8b-d544-4ec0-8389-101756565819)
![307020830-e4f1574a-dfbb-4959-9694-56b8e63215b9](https://github.com/user-attachments/assets/cd10024a-c603-4477-96c5-9837824b9328)
![307020948-f157aa0a-7c6d-439c-82f9-48b4eb18640c](https://github.com/user-attachments/assets/cc065e6f-5412-4859-a988-c3a002e9e614)
![307021052-9d1a09be-63db-456b-b32b-b73bb7da9594](https://github.com/user-attachments/assets/436b48cd-1a5b-4c98-a182-ad590f749c46)
![307021178-4bdad205-2656-4a67-88b1-32cc6e83b6f2](https://github.com/user-attachments/assets/ec7bf0cd-f4fb-4836-8834-ee26a360bd00)
![307022399-8a3a32c2-7299-4475-8d3a-b2c06252bbf9](https://github.com/user-attachments/assets/0be25535-9372-429a-97c1-f1bcd157ab80)
![307022483-6eaee4f2-34fc-4ccb-b485-e97b83b21dd6](https://github.com/user-attachments/assets/0d2e3b23-bfe3-4539-ae32-af7af70434c0)
![307022671-904992df-bd11-4fd3-8ca8-b40058ce7975](https://github.com/user-attachments/assets/2756e2ab-31a6-4b64-91a7-5cd788bec5f7)















