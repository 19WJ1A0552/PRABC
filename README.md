Code Innovation Series - Gurunanak Institute Of Technology 2021

Breast cancer is the most common cancer in women. About 90% of breast cancer patients live for at least 5 years after the cancer is diagnosed. When the breast cancer is detected early, the chance of survival is much higher. Beginning at the age of 40, breast cancer screening every one or two years is one of the most recommended preventive solutions for women. However, there are a large population of women that does not have access to such services despite having a high chance of developing breast cancer. Risk scoring for breast cancer that can identify individuals with high risk of developing chronic condition might be a good way to encourage individuals to seek professional help on time. The tool is easy and cost-effective to use. 


What it does

Pink Ribbon is a tool for calculating the chance of developing breast cancer. Using this tool, a user can enter some information including age, weight, height, history of breast cancer in 1st degree relative, age of a user at the first birth or nulliparity, menopausal status, history of previous breast biopsy, and history of using hormone replacement therapy. Then, the app will return the chance of developing breast cancer. Upon returning the result, the tool also provides additional insights about breast cancer from the dataset.

<p align = "center">
</p>


The data is obtained from Breast Cancer Surveillance Consortium (BCSC) website. After data wrangling and feature engineering steps, a random forest model was trained as a classifier. The precision and recall were used for fine tuning and performance evaluation.  Python, Flask, D3.js, and HTML are deployed for creating the app.

### Running

pip install virtualenv

virtualenv flask-app-venv 

flask-app-venv/Scripts/activate.bat

source flask-app-venv/bin/activate

pip install Flask

pip install joblib

pip install sklearn

pip install numpy

python app.py

### References 

https://www.cancer.org/content/dam/CRC/PDF/Public/8577.00.pdf

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4991144/