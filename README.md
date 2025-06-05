# 🧠 Association Rule Mining: Apriori & FP-Growth Implementation

This project applies **Association Rule Mining (ARM)** techniques to uncover meaningful relationships between items in transactional data. Implemented using both **Apriori** and **FP-Growth** algorithms, this analysis helps identify itemsets that frequently co-occur, offering insights for recommendation systems, inventory planning, and marketing strategies.

---

## 🛒 Dataset

A synthetic dataset of 15 transactions containing common items such as `Bread`, `Milk`, `Beer`, `Diaper`, `Cola`, etc., is used to simulate a market basket environment.

---

## 🎯 Objectives

- ✅ Encode transactions into one-hot format for processing
- ✅ Apply **Apriori** to extract frequent itemsets with minimum support
- ✅ Apply **FP-Growth** for efficient frequent pattern mining
- ✅ Generate and interpret association rules with support, confidence, and lift
- ✅ Visualize rule metrics using **scatter plots** and **network graphs**
- ✅ Compare Apriori vs. FP-Growth in terms of output and performance

---

## 🧰 Tools & Libraries

- `pandas`, `numpy` – data handling
- `mlxtend` – Apriori, FP-Growth, and rule generation
- `matplotlib`, `seaborn` – data visualization
- `networkx` – graph visualization

---

## 🔍 Sample Output

> **Rule**: `{'Bread', 'Milk'} → {'Eggs'}`  
> - **Support**: 0.33  
> - **Confidence**: 0.67  
> - **Lift**: 1.45

---

## 📊 Visualizations

- **Scatter Plot**:  
  Support vs Confidence colored by Lift (with jitter for better readability)
- **Network Graph**:  
  Antecedents → Rule → Consequents as a directed graph showing relationships

---

## 💡 Applications

- 📈 **Market Basket Analysis**: Find items commonly bought together  
- 🤖 **Recommendation Engines**: Suggest complementary products  
- 📦 **Inventory Planning**: Manage stock based on co-purchase trends  
- 🎯 **Targeted Promotions**: Bundle items for improved sales

---

## 📝 Notes

- Minimum support = 0.3  
- Minimum confidence = 0.6  
- Output includes metrics like lift to evaluate rule significance  
- Scatter plot includes jitter to improve point distinction

---

## ⚠️ Disclaimer

This project is created for **educational and research purposes only**.

---

## 👨‍💻 Author

Developed by [Luqman](https://github.com/luqyz)  
Contributions and suggestions are welcome!

---

## 📄 License

This project is licensed under the MIT License.
