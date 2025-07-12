## Tumor Detection

##  Objective
The goal of this project is to build a machine learning model that can classify tumors as **malignant (M)** or **benign (B)** using features extracted from cell nuclei in digitized images. This project demonstrates the ability to handle medical datasets, perform EDA, and apply classification algorithms.

##  Dataset
- **Name**: Tumor_Detection.csv
- **Source**: Provided in the course module
- **Features**: Includes medical attributes such as `radius_mean`, `texture_mean`, `perimeter_mean`, etc.
- **Target**: `diagnosis` (M = Malignant, B = Benign)

##  Tools & Libraries Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (RandomForestClassifier, StandardScaler, train_test_split)

##  Methodology
1. **Data Cleaning**:
   - Removed irrelevant columns like `id` and unnamed fields
   - Checked and handled missing values

2. **Exploratory Data Analysis (EDA)**:
   - Visualized class distribution using count plots
   - Used correlation heatmaps to identify relationships between features

3. **Preprocessing**:
   - Applied `StandardScaler` for feature normalization
   - Split data into training and test sets (e.g., 80/20 split)

4. **Model Building**:
   - Used `RandomForestClassifier` from sklearn
   - Trained the model on the training set
   - Evaluated using accuracy score and confusion matrix

##  Results
- Achieved high accuracy (mention exact score)
- Model performed well in classifying tumors based on input features
- Visualizations showed strong correlations among certain features


