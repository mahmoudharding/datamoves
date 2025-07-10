# Python Notebooks: Core Data Moves Demo

This repository contains a collection of Python Jupyter notebooks that implement and visualize the six core data moves described in Erickson, Wilkerson, Finzer & Reichsman (2019) *“Data Moves”* ([escholarship.org](https://escholarship.org/uc/item/0mg8m7g6)). Each notebook demonstrates a specific move using real datasets and Python tools like Pandas and Matplotlib.

## Background

A **data move** is an action that changes a dataset’s structure or values to make analysis more effective or insightful. The core moves covered in this repo are based on:

> Erickson, T., Wilkerson, M., Finzer, W., & Reichsman, F. (2019). *Data moves*. Journal of Statistics and Data Science Education, 27(1), 2–11. [https://escholarship.org/uc/item/0mg8m7g6](https://escholarship.org/uc/item/0mg8m7g6)

The six moves demonstrated:

- **Filtering** – select rows based on conditions  
- **Grouping** – divide data into categories  
- **Summarizing** – compute aggregates (mean, count, etc.)  
- **Calculating** – derive new values/columns  
- **Merging / Joining** – combine datasets  
- **Making Hierarchy / Restructuring** – reshape data using pivot, melt, or multi-indexing

## 📂 Repository Structure

/
├── notebooks/

│   ├── 01\_filtering.ipynb

│   ├── 02\_grouping\_and\_summarizing.ipynb

│   ├── 03\_calculating.ipynb

│   ├── 04\_merging\_joining.ipynb

│   └── 05\_hierarchy\_restructuring.ipynb

├── data/

│   └── nhanes\_sample.csv

├── requirements.txt

└── README.md

## Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/data-moves-notebooks.git
   cd data-moves-notebooks

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

## Notebooks Overview

Each notebook focuses on a single data move with worked examples:

| Notebook                            | Description                                          |
| ----------------------------------- | ---------------------------------------------------- |
| `01_filtering.ipynb`                | Selecting subsets of data (e.g., rows by condition)  |
| `02_grouping_and_summarizing.ipynb` | Using `groupby()` to compute aggregates              |
| `03_calculating.ipynb`              | Adding new columns using derived formulas            |
| `04_merging_joining.ipynb`          | Merging two or more datasets                         |
| `05_hierarchy_restructuring.ipynb`  | Reshaping data using pivot tables and multi-indexing |

## Learning Goals

* Understand each core data move as a conceptual tool for working with data.
* Practice using `pandas` to implement data moves.
* See how combinations of moves enable deeper analysis and insight.

## Citation & Attribution

This work builds upon ideas from:

Erickson, T., Wilkerson, M., Finzer, W., & Reichsman, F. (2019). *Data Moves*. *Journal of Statistics and Data Science Education*, 27(1), 2–11. [https://escholarship.org/uc/item/0mg8m7g6](https://escholarship.org/uc/item/0mg8m7g6)

Wickham, H. (2014). Tidy data. Journal of Statistical Software, 59(10), 1–23. [https://doi.org/10.18637/jss.v059.i10](https://doi.org/10.18637/jss.v059.i10)

Erickson, T., Ismay, C., & Chunn, J. (2018). The fivethirtyeight R package: “Tame Data” principles for introductory statistics and data science courses. Technology Innovations in Statistics Education, 11(2). [https://escholarship.org/uc/item/0rx1231m](https://escholarship.org/uc/item/0rx1231m) 

Pruim, R., Gîrjău, M.-C., & Horton, N. J. (2023). Fostering Better Coding Practices for Data Scientists  . Harvard Data Science Review, 5(3). [https://doi.org/10.1162/99608f92.97c9f60f](https://doi.org/10.1162/99608f92.97c9f60f)

Stokes, D. J., & Harding, M. (n.d.). Intro R Python 4 DS. GitHub Pages. Retrieved July 9, 2025, from [https://djstokes02.github.io/IntroRPython4DS/](https://djstokes02.github.io/IntroRPython4DS/)


## License

All content in this repository is dedicated to the public domain under the [Creative Commons Zero (CC0) license](https://creativecommons.org/publicdomain/zero/1.0/). You are free to use, modify, and share without restriction.
