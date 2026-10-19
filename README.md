# CSRPSO supporting dataset

Supporting data for **Cross-Swarm Recombination Particle Swarm Optimizer for Offshore Wind Farm Layout and Cable Routing Optimization**.

[Download the dataset](CSRPSO_minimal_dataset.zip?raw=true)

The archive contains case inputs and recorded optimization results for eight offshore wind-farm cases, six algorithms, and 30 repetitions per case and algorithm (1,440 runs). Each run used 30 initial layouts and 15,000 complete objective evaluations.

## Contents

- Eight MATLAB files with case inputs, per-run metrics, 15,000-point convergence histories, selected turbine layouts, and cable-routing results.
- Eight CSV files with per-run metrics, selected-layout indices, summary statistics, and statistical comparisons.
- `README.txt` describing fields, units, case and algorithm labels, and their relationships to the manuscript figures and tables.
- `verify_dataset.py`, a read-only numerical consistency check using Python 3, NumPy, and SciPy.

Extract the archive and read its `README.txt` for usage instructions. To run the included check from the extracted dataset directory:

```sh
python3 verify_dataset.py
```

## File integrity

SHA-256 of `CSRPSO_minimal_dataset.zip`:

```text
34733551380f1dfb3cddc2356a793dd42f4ee2b5b5c64ca53a98c3f1a2caba59
```
