# 🌿 Biodiversity Analysis in National Parks

This project analyzes biodiversity data from several U.S. national parks using Python and visualizations. The goal is to understand species distribution, conservation status, and observation patterns across different parks.

---

## 📁 Files

- `species_info.csv` – Contains data about species, their categories, and conservation status.
- `observations.csv` – Includes observation counts for each species at different parks.
- `Biodiversity_Analysis.ipynb` – Jupyter notebook containing all the analysis and plots.

---

## 🔍 Questions Explored

1. **What is the distribution of conservation status for animals?**  
 Visualize how many species fall into each status (e.g., Endangered, Threatened, etc.) using bar charts.

2. **Are certain types of species more likely to be endangered?**  
  Compare species categories (Mammal, Bird, Plant, etc.) across different conservation statuses using grouped bar charts.

3. **Are the differences between species and their conservation status significant?**  
   Perform a **Chi-Squared Test of Independence** to test for a statistically significant relationship between `category` and `conservation_status`.

4. **Which species were spotted the most at each park?**  
   Find and plot the most observed species per park using a horizontal bar chart labeled with species names.

---

## 📊 Visualizations

- **Log-scale bar charts** to handle large variations in species counts.
- **Grouped and stacked bar charts** to compare categories.
- **Horizontal bar chart** with species name labels for readability.

---

## 🧪 Statistical Method

Use the `scipy.stats.chi2_contingency()` method to perform the **Chi-Squared Test**.  
Result: A p-value of `~2.45e-117` confirms a highly significant relationship between species type and conservation status.

---

## 🚀 How to Run

1. Clone the repository
2. Open the notebook `Biodiversity_Analysis.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook
3. Upload the two CSV files to your environment
4. Run each cell sequentially

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn for plotting
- Scipy for statistical testing
- Google Colab for running the notebook

---

## 📌 License

This project is open-source and free to use under the MIT License.

---

## 🤝 Contributions

Feel free to open issues or pull requests if you'd like to suggest improvements!
