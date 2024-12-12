# Cholestify-ML

**Cholestify-ML** is a repository for building a machine learning-based food recommendation system to promote healthy eating and help manage hypercholesterolemia. This repository contains the necessary datasets, preprocessing scripts, and the model implementation to create an accurate and effective recommendation system tailored to user-specific nutritional needs.

---

## Repository Structure

The repository is organized into the following structure:

### 1. **Dataset**
This folder contains the datasets required for the model:
- **`data_diri.csv`**: User-specific nutritional and demographic data.
- **`food_data.csv`**: Information about various food items, including nutritional content like calories, fat, protein, and cholesterol.
- **`training_data.csv`**: Processed data used for training the model.
- **`user_food_pars.csv`**: User-food pair data indicating relevance for recommendations.

### 2. **Preprocessing Data**
This folder contains Jupyter notebooks for preprocessing the datasets:
- **`user_Food_Pair_Data.ipynb`**: Processes and prepares user-food pair data for training.
- **`food_data.ipynb`**: Cleans and formats the raw food dataset.
- **`training_data.ipynb`**: Combines processed data into a final dataset for training.
- **`user_data.ipynb`**: Preprocesses user-specific data for integration with the recommendation system.

### 3. **Cholestify_Model.ipynb**
This notebook contains the implementation of the food recommendation model using deep learning. It includes:
- The dual embedding model architecture for user and food features.
- Training pipeline with metrics like precision, recall, and AUC.
- Inference module to generate food recommendations for users based on their nutritional needs.

---

## Usage

### 1. Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/yourusername/Cholestify-ML.git
cd Cholestify-ML
