
This repository contains the code, data, baseline implementations, figures, and result files for MRAGDM experiments.
<img width="839" height="899" alt="image" src="https://github.com/user-attachments/assets/8fd38167-0ffc-4e8c-8afe-fc36d21a475f" />
Overall framwork of MRAGDM.

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

