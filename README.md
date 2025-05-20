# Molecular-Florescence
Jupyter notebook analyzing fluorescence absorption and polariton dispersion. Includes Beer–Lambert law validation by varying concentration and path length in three materials, followed by polariton branch fitting from dispersion data.
# Beer–Lambert Law and Polariton Dispersion Analysis

**Single Jupyter Notebook** that performs:

1. **Part 1: Beer–Lambert Rule – Concentration Sweep**

   * Tests the Beer–Lambert law for three different fluorescent materials at various concentrations
   * Keeps the optical path length constant
   * Extracts intensity profiles, plots absorbance vs. concentration, and checks the linearity of the relationship

2. **Part 2: Beer–Lambert Rule – Path Length Sweep**

   * Verifies the Beer–Lambert law for the same three materials over several optical path lengths
   * Uses a fixed set of concentrations
   * Analyzes absorbance vs. path length, performs linear fits and residual analysis

3. **Part 3: Polariton Dispersion Analysis**

   * Fits upper and lower polariton dispersion curves to experimental $E(k)$ data
   * Implements a search over 4 fitting parameters: \\(E\_{\rm exc}, n, L\_0, \hbar\Omega
   * Estimates parameter uncertainties and plots both branches together with error bars

---

## Contents

* `notebook.ipynb` – Main Jupyter Notebook containing all three parts
* `README.md` – This file

## Requirements

* Python 3.8+
* [NumPy](https://numpy.org/)
* [Matplotlib](https://matplotlib.org/)
* [SciPy](https://scipy.org/)
* [OpenCV‑Python](https://pypi.org/project/opencv-python/)
* [Pandas](https://pandas.pydata.org/)
* JupyterLab/Notebook


## Usage

1. Launch JupyterLab/Notebook:

   ```bash
   jupyter lab
   ```
2. Open and run **`notebook.ipynb`**. All three analysis parts are self-contained in sequential sections.
3. Adjust file paths in the first cell to point to your `data/images/` and `data/dispersion_data.csv`.

---

## Structure

* **Part 1**: absorbance vs. concentration for Materials A, B, C.
* **Part 2**: Image‐based absorbance vs. path length.
* **Part 3**: Polariton dispersion fitting and combined upper/lower branch plotting.

---

## License

MIT License. See [LICENSE](LICENSE) for details.

## Contact

For questions or issues, please open an issue or contact the repository maintainer.
