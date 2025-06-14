# Order Flow Imbalance Feature Engineering

This repository contains a Jupyter Notebook implementation of Best-Level OFI, Multi-Level OFI, Integrated OFI (via PCA), and Cross-Asset OFI based on the paper:

`Cross-Impact of Order Flow Imbalance in Equity Markets`

## Contents

- `ofi_features.ipynb` – main notebook that performs all computations and generates summary statistics.
- `first_25000_rows.csv` – input order book data file.

## How to Run

1. **Clone this repository:**

   ```bash
   git clone https://github.com/yourusername/bh-ofi-impact.git
   cd bh-ofi-impact
   ```

2. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the notebook:**

   ```bash
   jupyter notebook ofi_features.ipynb
   ```

4. **Run all cells:**

   Inside the notebook interface, go to:

   ```
   Cell → Run All
   ```

   This will compute all OFI features and display the final summary statistics table.
