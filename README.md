# 📈 Nonlinear Regression with scikit-learn

## 🧠 Problem Statement and Goal of Project

This project explores **nonlinear regression modeling** techniques using synthetic data to understand how well scikit-learn models can capture non-linear relationships between variables. The primary goal is to test and evaluate different regression models and preprocessing techniques in a learning-driven, experimentation-focused environment.

## 💡 Solution Approach

* Created a synthetic non-linear dataset using polynomial relationships and random noise.
* Visualized the true function and noisy observations for intuitive understanding.
* Attempted to fit a **`LinearRegression`** model as a baseline.
* Applied **`PolynomialFeatures`** to enable linear regression to fit non-linear relationships.
* Evaluated underfitting/overfitting behavior visually using plots.

## 🧰 Technologies & Libraries Used

* Python
* Jupyter Notebook
* NumPy
* Matplotlib
* scikit-learn (`LinearRegression`, `PolynomialFeatures`)

## 🚀 Installation & Execution Guide

To run this notebook:

1. Clone this repository or copy the notebook.

2. Install required dependencies (via pip):

   ```bash
   pip install numpy matplotlib scikit-learn
   ```

3. Open the notebook in Jupyter:

   ```bash
   jupyter notebook 04_Nonlinear-Regression.ipynb
   ```

## 📊 Key Results / Performance

| Model                 | Degree | Visual Fit | Notes                            |
| --------------------- | ------ | ---------- | -------------------------------- |
| Linear Regression     | 1      | ❌ Poor     | Underfits non-linear pattern     |
| Polynomial Regression | 3      | ✅ Better   | Begins to capture curvature      |
| Polynomial Regression | 10     | ⚠️ Overfit | Captures noise, not just pattern |

*Visual analysis was used rather than metric-based evaluation due to the focus on understanding model behavior, not optimizing for accuracy.*

## 🖼️ Screenshots / Sample Outputs

| Plot                                                                                    | Description                                    |
| --------------------------------------------------------------------------------------- | ---------------------------------------------- |
| ![Nonlinear data](https://user-images.githubusercontent.com/placeholder-nonlinear.png)  | Synthetic data with true and observed function |
| ![Polynomial fit](https://user-images.githubusercontent.com/placeholder-polynomial.png) | Polynomial regression with various degrees     |

(*Note: Placeholder paths — images should be uploaded if this is a public repo.*)

## 🧠 What This Project Demonstrates

* Solid understanding of **bias-variance tradeoff** through polynomial degree exploration.
* Knowledge of using `PolynomialFeatures` to extend linear models.
* Clarity in data visualization and interpretation of model behavior.
* Willingness to **showcase models that don’t perform well** to highlight learning — an honest and analytical approach important in real-world modeling.
* Exploration-first mindset — this notebook is part of a broader process of skill-building and experimentation, not just clean results.

## 🗂️ Description About Dataset

### Dataset Generation Process:
we use some random data to show models abiliti and china_gdp.csv dataset
* **Input Variable (`x`)**: Random values uniformly distributed between 0 and 1.
* **Target Variable (`y`)**: Computed using a non-linear function:

  $$
  y = \cos(1.5 \pi x) + \text{noise}
  $$

  where **noise** is Gaussian (normally distributed) noise added to simulate real-world data imperfections.

### Dataset Characteristics:

* Small sample size, suitable for visual experimentation.
* Clear non-linear pattern to test model capabilities.
* Controlled randomness (seeded) for reproducibility.

This dataset is ideal for:

* Understanding the limits of linear models on non-linear problems.
* Experimenting with polynomial transformations and overfitting risks.
* Demonstrating model interpretability via plots.

## 👤 Author

## mehran Asgari
## **Email:** [imehranasgari@gmail.com](mailto:imehranasgari@gmail.com).
## **GitHub:** [https://github.com/imehranasgari](https://github.com/imehranasgari).

---

## 📄 License

This project is licensed under the Apache 2.0 License – see the `LICENSE` file for details.