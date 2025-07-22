<h1 align="center">DSP Learning Labs</h1>

<p align="center">
  <a href="https://www.um.edu.mt/courses/studyunit/cce3206">
    <img src="https://img.shields.io/badge/University%20of%20Malta-CCE3206-blue?style=for-the-badge&logo=python&logoColor=white" alt="CCE3206 Course">
  </a>
  <a href="https://www.um.edu.mt/profile/trevorspiteri">
    <img src="https://img.shields.io/badge/Supervised%20by-Dr.%20Trevor%20Spiteri-green?style=for-the-badge" alt="Supervisor">
  </a>
</p>

<p align="center">
  A lab-focused repository for <strong>CCE3206: Digital Signal Processing</strong> at the <a href="https://www.um.edu.mt">University of Malta</a>. Each practical session explores a key DSP concept using Python (NumPy, SciPy) in Jupyter notebooks.
</p>

---

## Practicals Overview

This repository includes 4 hands-on labs, each with an accompanying PDF worksheet and solved notebook.

### Practical 1 – Sampling Theorem
- Signal generation and pulse train sampling
- Power spectrum analysis in time and frequency domains
- Aliasing and effective sampling frequency
- Chebyshev filter design and application to sampled signals

### Practical 2 – IIR Filter Implementation
- First-order IIR filter using intermediate variables
- Impulse and step response analysis
- Filtering real `.wav` audio signals
- Frequency response and power spectra
- Gain and phase calculations across frequencies
- Theoretical vs experimental Bode plots

### Practical 3 – FIR Filter Design (from uploaded PDF)
- FIR system design and frequency response analysis *(Details in worksheet)*

### Practical 4 – DFT and FFT Analysis (from uploaded PDF)
- DFT matrix generation
- Transform properties: conjugation, symmetry, and energy conservation *(Details in worksheet)*

> **Note**: A `venv` or `requirements.txt` file is not included. To run the notebooks, install `numpy`, `scipy`, `matplotlib`, and `jupyter` using pip or conda.

---

## Structure

```bash
cce3206/
├── Practical_1/
│   ├── cce3206-practical-1.pdf
│   └── practical_1_solution.ipynb
├── Practical_2/
│   ├── cce3206-practical-2.pdf
│   └── practical_2_solution.ipynb
├── Practical_3/
│   ├── cce3206-practical-3.pdf
│   └── practical_3_solution.ipynb
├── Practical_4/
│   ├── cce3206-practical-4.pdf
│   └── practical_4_solution.ipynb
└── README.md
```

---
