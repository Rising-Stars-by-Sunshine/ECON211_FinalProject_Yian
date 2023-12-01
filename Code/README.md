## Description

This section is the detailed data query (and preprocessing) process. In the preprocessing part, a pseudo-code for the process in Latex Table format is provided.

## Data Query

The data was directly downloaded from kaggle www.kaggle.com. The following steps show the querying process.

### Step 1

Go to www.kaggle.com. Click **Sign in** or **Register**.

<img src="Step1.png" alt="Step1">

### Step 2

After successfully logging into kaggle, go to https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction.

<img src="Step2.png" alt="Step2">

### Step 3

Click **Download(9kb)**.

<img src="Step3.png" alt="Step3">

### Step 4

A file named **archive.zip** will be downloaded. UnZip it. There will be a file named **heart.csv**.

<img src="Step4-1.png" alt="Step4-1">

<img src="Step4-2.png" alt="Step4-2">

## Data Preprocessing

A categorical variable comprises values that can be categorized into distinct groups based on a specific characteristic. Unlike ordinal variables, categorical variables lack a natural order among their categories. These variables, also known as qualitative or attribute variables, cannot be directly processed by most machine learning algorithms. To address this, it is necessary to convert categorical variables into numerical values. The performance of many algorithms is influenced by the chosen encoding method for categorical variables.

To handle categorical variables and facilitate their integration into machine learning workflows, one commonly used tool is the LabelEncoder class from the scikit-learn library (sklearn). The LabelEncoder is designed to transform categorical labels into numerical representations, thus enabling machine learning algorithms to work with them effectively.
