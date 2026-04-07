# MRAGDM

This repository contains the code, data, baseline implementations, figures, and result files for MRAGDM experiments.

## Repository Structure

```text
mragdm_code/
├─ MRAGDM_train_51.ipynb
├─ MRAGDM_train_K.ipynb
├─ README.md
├─ readme.me
├─ requirement.txt
├─ .gitignore
├─ data/
│  ├─ hetero_data.pt
│  ├─ lncrna.txt
│  ├─ mirna.txt
│  └─ protein.txt
├─ baseline/
│  ├─ other_train.ipynb
│  ├─ figure.ipynb
│  └─ input_data/
├─ figure/
└─ result/
```

## Files and Folders

- `MRAGDM_train_51.ipynb`: Main notebook for MRAGDM training and experiments.
- `MRAGDM_train_K.ipynb`: Additional MRAGDM training notebook.
- `data/`: Input data required for MRAGDM.
- `baseline/other_train.ipynb`: Notebook for baseline models, including HAN, HGT, and RGCN.
- `baseline/input_data/`: Input data required for the baseline models.
- `baseline/figure.ipynb`: Notebook for result analysis and visualization.
- `figure/`: Exported figures used for analysis and presentation.
- `result/`: Output results and statistical summary files.
- `requirement.txt`: Python package dependencies for running the project.

## Requirements

It is recommended to use Python 3.10 or Python 3.11.

Install the required packages with:

```bash
pip install -r requirement.txt
```

## Usage

### Run MRAGDM

Open and run one of the following notebooks:

- `MRAGDM_train_51.ipynb`
- `MRAGDM_train_K.ipynb`

The main MRAGDM input data is stored in:

```text
data/hetero_data.pt
```

### Run Baseline Models

Open and run:

```text
baseline/other_train.ipynb
```

The baseline notebooks use the files in:

```text
baseline/input_data/
```

### Results and Figures

- Experimental outputs are stored in `result/`.
- Figures are stored in `figure/`.
- Additional plotting and analysis code is available in `baseline/figure.ipynb`.

## GitHub Upload

Run the following commands in the project root directory:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/your-repository.git
git push -u origin main
```
