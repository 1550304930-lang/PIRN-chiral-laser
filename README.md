# PIRN-assisted Directional Chiral Laser

This repository provides the source code used in the manuscript:

"PIRN-assisted directional chiral laser induced by non-Hermitian interlayer coupling"

## Files

- `pinn_group_improved.py`: PIRN training and validation code.
- `pinn_postprocess_tools.py`: Post-processing code for validation metrics, interlayer coupling extraction, Hamiltonian band reconstruction, and laser-emission prediction.

## Requirements

The code requires Python 3.10 and the following packages:

```bash
pip install numpy pandas matplotlib torch openpyxl scipy
