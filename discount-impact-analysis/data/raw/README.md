# Raw Data

This directory is intended to store the raw dataset used for this analysis.

Due to file size considerations and repository hygiene best practices, the full raw data files are **not included** in this GitHub repository.

---

## 📂 Data Source

The dataset contains historical order-level sales data used to analyze the business impact of discount strategies, including:
- Order quantities
- Discount levels
- Revenue information
- Time-based attributes

If the dataset is publicly available, it can be obtained from the original source and placed in this directory using the expected file structure.

---

## ⚠️ Important Notes

- Raw data files should remain **unchanged** to preserve data integrity.
- Any data cleaning, filtering, or feature engineering steps are performed downstream and stored separately (e.g., in `data/processed/`).
- Large files are intentionally excluded from version control to keep the repository lightweight and easy to clone.

---

## 📌 How to Use

1. Download or obtain the raw dataset.
2. Place the file(s) in this directory.
3. Ensure the file names match those expected in the notebooks.

Links:

data/raw/orders.csv     : [Orders](https://drive.google.com/file/d/1Vu0q91qZw6lqhIqbjoXYvYAQTmVHh6uZ/view?usp=sharing)
data/raw/orderlines.csv : [Orderlines](https://drive.google.com/file/d/1FYhN_2AzTBFuWcfHaRuKcuCE6CWXsWtG/view?usp=sharing)
data/raw/products.csv   : [Products](https://drive.google.com/file/d/1afxwDXfl-7cQ_qLwyDitfcCx3u7WMvkU/view?usp=sharing)

---

## 🔒 Data Privacy

If the dataset contains sensitive or proprietary information, it should **not** be uploaded to public repositories.