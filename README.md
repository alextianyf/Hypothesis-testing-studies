# Hypothesis-testing-studies

This repository presents a clear and structured breakdown of fundamental concepts in **hypothesis testing**, including the difference between one-tailed and two-tailed tests. It combines written explanations, illustrative visuals, sample data, and runnable notebooks.

The materials are designed for:

- Students studying introductory statistics

- Data science learners needing concept refreshers

- Interview preparation for statistical inference questions

## File Structure

```bash
.
├── data/
│   └── Simulated_Salary_Data.csv         # Sample dataset used for demonstration
├── images/                               # Conceptual visual illustrations (exported from notebooks)
│   ├── CLT-samples.png
│   ├── CLT.png
│   ├── critical-value.png
│   ├── hypothesis.png
│   ├── p-value.png
│   ├── single-double-tail.png
│   └── t-distribution.png
├── notebooks/                            # Jupyter notebooks used to generate supporting diagrams
│   ├── 01-hypothesis-images.ipynb
│   └── 02-single-double-tail-images.ipynb
├── 01-hypothesis-testing.md              # Written notes on hypothesis testing (main discussion)
├── 02-single-double-tail.md              # Written notes on tail types (main discussion)
├── LICENSE                               # Project license (MIT)
├── requirements.txt                      # Minimal dependencies needed to run the notebook
└── README.md                             # Project overview (you are here)
```

## Topics & Notes Breakdown

| File Pair | Key Topics Covered |
|-----------|---------------------|
| **`01-hypothesis-testing.md`**<br>**`01-hypothesis-images.ipynb`** | - Null and Alternative Hypotheses (H₀ vs. H₁)<br>- p-value and α significance level<br>- Critical value and test statistic<br>- Visual overview of the t-distribution<br>- Real-world example using simulated salary data |
| **`02-single-double-tail.md`**<br>**`02-single-double-tail-images.ipynb`** | - One-tailed vs. Two-tailed hypothesis tests<br>- How to choose the correct test type<br>- Graphical comparison of rejection regions<br>- Interpreting p-values in both settings |

## Development & Reproduction

To run, verify, or modify this project, the following environment is recommended:

- **Python version:** 3.12.4  
- **IDE:** Visual Studio Code  
  Alternatively, you may explore the notebook interactively using **JupyterLab** or **Google Colab**.

Install the required packages using:

```bash
pip install -r requirements.txt
```

The requirements.txt file was automatically generated using pipreqs:

```bash
pipreqs . --force
```

## Learning Outcomes

By reviewing these notes, learners will:

- Understand the logic and flow of hypothesis testing

- Accurately interpret p-values and critical values

- Distinguish when to apply one-tailed vs. two-tailed tests

- Gain confidence with visual reasoning in statistics

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.  
You are free to use and adapt the materials for **non-commercial** purposes, but **you must credit the author**.

See the full license text in the [LICENSE](./LICENSE) file.

⸻

## Author

Alex Tian
Master of Applied Science @ University of Victoria
Specializing in Data Science & Machine Learning