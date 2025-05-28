# 📊 Hypothesis Testing in Python – Z-Test, T-Test & Chi-Square Test

This repository contains Jupyter notebook examples demonstrating **Hypothesis Testing** using real-world scenarios with the following statistical tests:

- ✅ Z-Test (One-sample)
- ✅ T-Test (One-sample)
- ✅ Chi-Square (χ²) Test (Goodness of Fit)

---

## 📘 Keyword Trick for Selecting Test Type

Use these keyword clues to identify the correct alternative hypothesis (Hₐ):

- **"Less than / Decrease"** → Hₐ: μ < ... → Left-tailed test
- **"Greater than / Increase"** → Hₐ: μ > ... → Right-tailed test
- **"Not equal / Different"** → Hₐ: μ ≠ ... → Two-tailed test

---

## 🔬 Z-Test Example: Salary Dispute

> A company claims the average employee salary is PKR 50,000/month. A labor group suspects it's overstated.

- Sample size: 40  
- Sample mean: 47,500  
- Population std. dev: 6,000  
- α = 0.05  
- **Result:** Labour group is correct (Left-tailed test)

```python
z_cal = (x̄ - μ) / (σ / √n)
if z_cal < z_table:
    reject H₀


📚 T-Test Example: Study Hours
University claims students study 15 hours/week. A sample shows an average of 13 hours.

Sample size: 10

Sample mean: 13

Sample std. dev: 2.5

α = 0.05

Result: Students are correct (Left-tailed test)


t_cal = (x̄ - μ) / (s / √n)
if t_cal < t_table:
    reject H₀
🧪 Chi-Square Test: User Distribution
Checking if user distribution across 4 categories is uniform.

Observed: [30, 20, 25, 25]

Expected: [25, 25, 25, 25]

α = 0.05

Result: Distribution is not uniform

χ²_cal = Σ((O - E)² / E)
if χ²_cal > χ²_table:
    reject H₀


📂 Technologies Used
Python 3

Jupyter Notebook

scipy.stats

numpy

🚀 Run the Notebook

git clone https://github.com/MuhammadUzair0786/Hypothesis_Testing---Z-Test-T-Test-CHAI-Test.git
cd Hypothesis_Testing---Z-Test-T-Test-CHAI-Test
jupyter notebook

🙌 Author
Muhammad Uzair
Bachelor's in Software Engineering

