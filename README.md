# WiDS Datathon 2025: ADHD & Sex Prediction from fMRI Data
WiDS Datathon Kaggle Competition tasked with building a model to predict both an individual’s gender and their ADHD diagnosis.

## **Project Overview**

This project is focused on predicting **ADHD diagnosis** and **sex (female or not)** using fMRI data and socio-demographic information, as part of the **WiDS Datathon 2025**. The dataset includes brain scan data (fMRI) along with socio-demographic features to build machine learning models.

## **Data Overview**

The dataset consists of:
<ul> 
    <li> fMRI Data: Brain scan data in matrix form. </li>
    <li> Socio-Demographic Data: Includes features like age, gender, and parental assessments. </li>
    <li> Target Variables: ADHD_Outcome (1 = ADHD, 0 = No ADHD) and Sex_F (1 = Female, 0 = Not Female). </li>
</ul>

## **Setup**

### **Clone the Repository**

To get started, clone the repository to your local machine:
<ul>
    <li><code> git clone https://github.com/your-username/adhd-sex-prediction.git </code></li>
    <li><code> cd adhd-sex-prediction </code></li>
</ul>

### **Install Dependencies**

Install the required Python dependencies by running the following:
<ul>
    <li><code> pip install -r requirements.txt </code></li>
</ul>

## **Data Preprocessing**

### **Loading Data**

First, load the training and test datasets:
```python
import pandas as pd

# Load training and test data
train_df = pd.read_csv('train.csv')
test_df = pd.read_csv('test.csv')

# Check for missing values in the training dataset
print(train_df.isnull().sum())




## Formatting Code
```
print("Wrapping text in three backticks is a great way to add a code block!")
print("You can add multiple lines of code")
```

```python
print("Specifiying the language = syntax highlighting!")
```

And of course you can always `print("Add inline code with single backticks")`

## Images and Hyperlinks

This is one way to add a [hyperlink](https://github.com/)

And this is how you add an image 

![Add some alt text here](https://www.breakthroughtech.org/app/themes/btt/assets/img/Break_Through_Tech_Logo.svg)

Feel free to add emojis :apple: and make your GitHub README descriptive and well-formatted!

## Read More

- [Markdown Reference Cheat Sheet](https://www.markdownguide.org/basic-syntax/)
- [Quickstart for writing on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
- [GitHub Markdown Preview VS Code Extension](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview)
