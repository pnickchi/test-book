# The Mini Test Book (in development)
**[View the Book Online](https://pnickchi.github.io/test-book/)**

## Overview  

**The Mini Test Book** provides a clear, modern introduction to key frequentist hypothesis tests—such as $t$-tests, one-way ANOVA, and chi-square tests. The material follows a consistent **eight-stage testing workflow** (Study Design → Data Collection and Wrangling → Exploratory Data Analysis → Hypothesis Definitions → Test Flavour and Components → Inferential Conclusions → Storytelling) and presents **parallel `R` and `Python` codes** for reproducible analysis. It combines mathematical foundations, statistical reasoning, and hands-on data science implementation to bridge theory and practice. This material is an **Open Educational Resource (OER)**.

##  Learning Goals

After reading this book, readers will be able to:

- Design and interpret hypothesis tests with rigour and reproducibility.
- Translate statistical problems into code-based workflows.
- Assess test assumptions (e.g., normality, variance homogeneity, independence).
- Communicate inferential findings clearly for data-driven decision-making.

## Testing Workflow  

The material follows a unified eight-stage testing workflow used throughout the book:  

1. **Study Design:** Formulate the research question and define the statistical inquiry.  
2. **Data Collection and Wrangling:** Acquire, clean, and prepare data for analysis.  
3. **Exploratory Data Analysis (EDA):** Visualize and summarize data patterns.  
4. **Testing Settings:** Define the model assumptions and testing framework.  
5. **Hypothesis Definitions:** State $H_0$ and $H_A$ formally.  
6. **Test Flavor and Components:** Select and implement the appropriate test (e.g., ANOVA, Chi-squared test).  
7. **Inferential Conclusions:** Interpret $p$-values and confidence intervals. Moreover, execute model diagnostics.
8. **Storytelling:** Communicate results with statistical and contextual clarity.  

## Key Features  

- **Two-language code examples** (`R` + `Python`) for every test.  
- **Simulated and real datasets** to ensure reproducibility.  
- **Workflow-based organization**, aligning with modern data science projects.  
- **Statistical depth + applied focus**, including equations, diagnostics, and communication of results.

## Getting Started  

### Prerequisites  

You’ will need the following tools installed:  
- **`R` ≥ 4.0** (with `tidyverse`, `rsample`, `broom`, etc.). 
- **`Python` ≥ 3.7** (with `pandas`, `numpy`, `scikit-learn`, `statsmodels`, etc.).
- **Quarto** for rendering the book locally.

### Run Locally  

```bash
git clone https://github.com/pnickchi/test-book.git
cd test-book
quarto preview
```

The book will preview at `http://localhost:54320` (as set in `_quarto.yml`).

To render the full book, use:

```bash
quarto render
```

## Repository Structure

```bash
├── book/                  # Chapter files (.qmd) with code and narrative
├── data/                  # Simulated and real datasets
├── docs/                  # Rendered output (for GitHub Pages)
├── img/                   # Figures and plots
├── _quarto.yml            # Global site configuration
├── test-book.Rproj        # RStudio project file
└── README.md              # This file
```

## Example Chapters

- **Chapter 1:** The Testing Workflow — introduces the eight-stage process.
- **Chapters 2–4:** Core tests (proportion and $t$-tests, and ANOVA).
- **Chapter 5:** Chi-Squared Tests — categorical data analysis.
- **Appendix B:** Simulated datasets.

Each chapter integrates equations, `R`/`Python` code blocks, and visualizations.

## Contributing

Contributions are welcome!

If you would like to fix typos, clarify text, or extend examples:

1.	Fork the repo and create a new branch.
2.	Make your edits in `.qmd` files under `/book/`.
3.	Preview locally with `quarto preview`.
4.	Submit a pull request.

Please ensure your contribution preserves reproducibility and cross-language parity (`R` + `Python`).

## Authors

Developed by [G. Alexi Rodriguez-Arelis](https://alexrod.netlify.app/), Ekaterina (Kate) Manskaia, and [Payman Nickchi](https://pnickchi.github.io/).

For questions or feedback, open an issue on [GitHub](https://github.com/pnickchi/test-book/issues).

## Citation

If you use this material in teaching or research, please cite it as:

Rodriguez-Arelis, G.A., Manskaia, E., & Nickchi, P. (2025). *The Mini Test Book*. University of British Columbia / OER Framework. [https://pnickchi.github.io/test-book/](https://pnickchi.github.io/test-book/)

Here is a BibTeX entry you can use:

```bash
@book{minitestbook,
  title     = {The Mini Test Book},
  author    = {Rodriguez-Arelis, Gilberto Alexi and Manskaia, Ekaterina and Nickchi, Payman},
  year      = {2025},
  url       = {https://pnickchi.github.io/test-book/},
  note      = {Open-access bilingual (R + Python) textbook},
  publisher = {University of British Columbia / OER Framework}
}
```

## Privacy Policy

For details on data usage, cookies, and user tracking on the website, please refer to the [Privacy Policy](https://pnickchi.github.io/test-book/book/privacy-policy.html).

## License

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0"  width="150"  src="img/by-nc-sa.png" /></a>
