# Binomial-Distribution-Analysis

This project demonstrates statistical analysis techniques for a binomial distribution dataset. The analysis focuses on computing probabilities, visualizing distributions, and calculating statistical measures such as the mean and variance.

---

## 📂 Files in This Repository:
- **End of Semester.Rmd**: R Markdown file containing the code and explanations for the statistical analysis of a binomial distribution dataset.

---

## 💻 Key Topics Covered:
### 1. **Binomial Distribution**
- Defined and modeled the distribution for a dataset with:
  - A fixed number of trials (`n = 31`).
  - A constant probability of success (`p = 0.447`).

### 2. **Probability Mass Function (PMF)**
- Generated and visualized the PMF for the binomial distribution using `dbinom`.

### 3. **Cumulative Distribution Function (CDF)**
- Calculated and visualized the CDF using `pbinom`.

### 4. **Probability Calculations**
- Computed probabilities for specific scenarios:
  - \( P(X = 17) \): Probability of exactly 17 successes.
  - \( P(X \leq 13) \): Probability of at most 13 successes.
  - \( P(X > 11) \): Probability of more than 11 successes.
  - \( P(X \geq 15) \): Probability of at least 15 successes.
  - \( P(16 \leq X \leq 19) \): Probability within a range.

### 5. **Statistical Measures**
- Calculated the following for the binomial distribution:
  - Mean (\( E(X) \)).
  - Variance (\( \text{Var}(X) \)).
  - Standard Deviation (\( \text{SD}(X) \)).

---

## 🛠️ Libraries Used:
- **ggplot2**: For visualization of PMF and CDF.
- **dplyr**: For data manipulation and summarization.

---

## 📊 Visualizations:
1. **Probability Mass Function (PMF)**:
   - Visualized the probability of each possible number of successes in the dataset.

2. **Cumulative Distribution Function (CDF)**:
   - Displayed the cumulative probability for success counts from 0 to 31.

---

## 🚀 How to Run:
1. Open `End of Semester.Rmd` in RStudio.
2. Install the required libraries if not already installed:
   ```R
   install.packages(c("ggplot2", "dplyr"))
