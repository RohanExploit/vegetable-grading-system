# Mushroom Classification

This project utilizes machine learning to classify mushrooms as edible or poisonous.

## Dataset Information
We leverage a pre-existing dataset containing descriptions of various mushroom species and their edibility labels (e.g., The Audubon Society Field Guide data or Kaggle's "Mushroom Classification" dataset). This data provides features like cap shape, color, and gill characteristics for model training.

## Technical Approach
1. Data Preprocessing: Clean and prepare the dataset, addressing missing values and ensuring consistency for optimal model training.
2. Feature Engineering (Optional): Explore techniques to create new features from existing ones, potentially improving model performance.
3. Model Training: Train a machine learning model, like Support Vector Machines (SVM) or Decision Trees, on the prepared data to learn the relationships between mushroom characteristics and edibility.
4. Model Evaluation: Evaluate the trained model's performance using metrics like accuracy, precision, recall, and F1 score to assess its effectiveness in classifying mushrooms.
5. Deployment (Optional): Develop a user interface allowing users to input mushroom features and receive predictions on edibility.
### Disclaimer: This system is intended as a supportive tool and should not be solely relied upon for mushroom identification.  Always consult a reliable field guide or expert for confirmation before consuming any mushroom.

## Running the Project
### This project is written in Python.  Specific instructions on setting up the environment and running the code

First of all clone this repository. by running this command
```
git clone https://github.com/Vishalkm206/Mushroom-classification

```
Make sure you are using python version 3.7,3.8,3.9 or 3.10. not 3.11 onwards because 1 library was removed from this 3.11 onwards.
or you can use anaconda3 to create virtual environments
Note :- if you are facing issues with this code try to open anaconda prompt and there you paste this code
```
conda create -n venv python==3.10
```
Activate this environment
```
conda activate venv
```
now copy the path of this repository where you have cloned it before
and type in your terminal and install all dependencies
```
cd path\to\Mushroom-classification\streamlitapp
pip install -r requirements.txt
```

run the application using the following command
```
streamlit run app.py
```

## Technologies Used
1. Python
2. scikit-learn
3. Pandas (Optional, for data manipulation)
4. Streamlit (Optional, for user interface development)
5. Specific libraries used within scikit-learn (e.g., SVM, Decision Tree)
6. Visualization libraries used for data exploration (e.g., Matplotlib, Seaborn)
7. Links to your project repository [Github - Mushroom Classification](https://github.com/Vishalkm206/Mushroom-classification)
