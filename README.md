# Machine Learning Techniques Lab – University Politehnica of Bucharest (ACS)

This repository contains the laboratory assignments, notebooks, and datasets for the **Machine Learning Techniques (*Tehnici de învățare automată*)** course at the Faculty of Automatic Control and Computers (ACS), National University of Science and Technology Politehnica Bucharest.

## Repository layout

```text
ACS_TIA/
├── labNN/                  # One folder per lab: requirements, notebooks, scripts, and the datasets they use
├── materials/              # Course materials downloaded from Moodle
│   ├── courses/            # Lecture slides
│   └── lab/                # General lab slides (syllabus, grading)
└── README.md
```

Every folder has its own `README.md` describing its contents.

## Materials

| Folder | Contents |
|--------|----------|
| [materials/courses](materials/courses/) | Lectures 1–4: introduction, preprocessing, feature engineering, ML techniques |
| [materials/lab](materials/lab/) | Lab syllabus and grading rules |

## Labs

| Lab | Topic | Folder |
|-----|-------|--------|
| 02 | Linear Regression | [lab02](lab02/) |

## Tooling

- **Language:** Python 3
- **Libraries:** NumPy, pandas, scikit-learn, Matplotlib
- **Notebooks:** JupyterLab or VS Code (Jupyter extension)

Setting up a virtual environment:

```sh
python -m venv .venv
source .venv/bin/activate
pip install numpy pandas scikit-learn matplotlib jupyterlab
```

Then start JupyterLab from the repository root:

```sh
jupyter lab
```
