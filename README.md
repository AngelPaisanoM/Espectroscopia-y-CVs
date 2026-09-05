# Espectroscopia-y-CVs

This repository is dedicated to the spectral analysis of cataclysmic variables (CVs), implementing standard techniques and procedures to interpret and understand the data.

The core of the analysis focuses on the residuals obtained by subtracting 4MOST flux from the SDSS spectra of the same objects. To achieve this, this repository provides a detailed pipeline that includes:

* **Main Pipeline:** Complete spectral analysis and processing functions located in the `4MOST.ipynb` Jupyter Notebook.
* **Exploratory Work:** The procedural steps taken to build the pipeline, exploring different approaches to optimize specific stages of the workflow.

### Techniques Explored:
* **Normalization:** Comparing polynomial fitting versus sigma-clipping.
* **Line Masking:** Utilizing `scipy.signal.find_peaks`, manual integrated statistics, and hybrid combinations of both approaches.

---

### Keywords
* **SDSS:** Sloan Digital Sky Survey.
* **4MOST:** 4-metre Multi-Object Spectroscopic Telescope (spectrograph instrument operating at Paranal Observatory).
