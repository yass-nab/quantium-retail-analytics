# Quantium - Chips Category Retail Analytics

Retail analytics project from the **Quantium Data Analytics job simulation (Forage)**: analysing chips transactions and customers, evaluating trial stores, and presenting recommendations to the category manager.

![Total sales by lifestage and customer type](images/Total%20Sales%20by%20Lifestage%20and%20Customer%20Type.png)

## What I did
- **Task 1 - Data & customers:** cleaned transaction and customer data, derived pack size and brand, and analysed sales by customer segment (lifestage x premium level).
- **Task 2 - Trial stores:** selected control stores (correlation and Euclidean distance on store metrics) and measured whether the trial layout lifted sales and customers.
- **Task 3 - Insights:** structured the findings with the Pyramid Principle into a stakeholder presentation with recommendations on product range and target segments.

## Tools
Python - Pandas - NumPy - Matplotlib - Seaborn - Jupyter - PowerPoint

## Project structure
```
task1_transactions_and_customers.ipynb   # data cleaning, customer segments, purchase behaviour
task2_trial_store_analysis.ipynb         # control-store selection and trial uplift
data/                                    # QVI transaction, customer and merged datasets
images/                                  # charts exported by the notebooks
report/Chips category & trial store review.pdf   # final presentation
```

## Run it
```bash
pip install -r requirements.txt
jupyter notebook
```

Data provided by Quantium through the [Forage](https://www.theforage.com) job simulation.

---
**Author:** Yassine Nabil - AI & Data Engineering - [LinkedIn](https://linkedin.com/in/yassine-nabil-33786931b)
