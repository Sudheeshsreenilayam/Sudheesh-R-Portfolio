# 🌲 Tree-Based Sales Prediction in R

This project explores how tree-based machine learning models can be used to predict retail product sales using the `Carseats` dataset. The techniques implemented include:

- Regression Trees
- Cross-validation and pruning
- Bagging (using all predictors)
- Random Forests with tuned `mtry`
- Variable importance analysis

---

## 📊 Dataset

The data comes from the `Carseats` dataset in the `ISLR` R package. It includes sales data and product features like:

- Shelf location
- Price
- Advertising
- Age of buyers
- Competing prices

---

## 🔍 Modeling Workflow

| Step | Description |
|------|-------------|
| 1️⃣ | Trained a regression tree on the training set |
| 2️⃣ | Applied cross-validation to prune the tree |
| 3️⃣ | Used bagging to improve predictive performance |
| 4️⃣ | Tuned `mtry` in random forests to compare test MSE |
| 5️⃣ | Visualized variable importance |

---

## 📈 Results

- **Regression tree**: Served as the baseline with a test MSE around 4.97
- **Pruned tree**: Slightly improved MSE (~4.74)
- **Bagging**: Reduced MSE significantly to ~2.33
- **Random forests**: Performed best at `mtry = 5`, with MSE ≈ 2.20
- **Most important features**: `ShelveLoc`, `Price`, and `Age`

---

## 🔗 View Report Online

📄 [Click here to view the project](https://sudheeshsreenilayam.github.io/Sudheesh-R-Portfolio/Tree-Based-Sales-Prediction-R/tree_model_sales.html)  

---

## 🧰 Tools Used

- R
- Packages: `tree`, `randomForest`, `ISLR`, `caTools`
- R Markdown + GitHub Pages

---

## 🧑‍💻 Author

**Sudheesh Sreenilayam**  
📎 [LinkedIn](https://www.linkedin.com/in/ssudheesh)

---
