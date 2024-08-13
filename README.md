# Exploratory Data Analysis

# Step 1 : Data Sourcing (Public Data, Private Data)
# Step 2 : Data Cleaning 
- 2.1 Handling Misssing Values
- -- Dropping Columns Which has more that 90% data missing
- -- Droping Rows which has missing value
- -- Replacing Missing Value by mean/ median / Mode  ( Imputation )
- -- Forward and Backwar Filling
- 2.2 Feature Scaling of the data (Standardization / Normalization ) ( Library: sklearn.preprocessing )
- Divide All values by Maximum Value
- Standard Scalar (Standardization)
- Min-Max Scaler  (Normalization)
- 2.3 Outlier Treatment
- -- For Detection Use Boxplot, Histograms, Scatter Plot, Z-Score, Inter Quartile Range
- -- Treatment - Remove them or use the model which are not affected by outlier like KNN, SVM, DT, Naive Bayes
- -- 3-Sigma Technique (Standard Deviation )
- -- Boxplots
- -- Inter Quartile Range
- 2.4 Handle Invalid Value
- Correct Incorrect Data type
- Encode Unicode Properly (eg: date format is different)
# Step 3 : Categorical Analysis
# Step 4 : Numerical Analysis
# Step 5 : Derived Metrics
- 5.1 Feature Binning
- -- Unsupervised Binning (equal width, equal Frequency)
- -- Supervised Binning
- 5.2 Feature Encoding ( Categorical Data to Numerical data)
- -- Label Encoding  ( Mostly used on Target / Y variable )
- -- One-Hot Encoding ( Mostly used in Features / X Variable )
- -- Target Encoding
- -- Hash Encoders
- 5.3 From Domain Knowledge
- 5.4 Calculated from Data
