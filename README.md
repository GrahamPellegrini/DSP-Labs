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

This repository includes 4 hands-on labs, each with a worksheet and an implemented solution notebook. Topics range from sampling theory and IIR filtering to FIR design and FFT-based frequency analysis.

### Practical 1 – Sampling Theorem
- Signal generation and pulse train sampling
- Power spectrum comparison (original vs sampled)
- Aliasing effects and Nyquist violations
- Chebyshev low-pass filtering

### Practical 2 – IIR Filter Implementation
- First-order IIR filter with recursive feedback
- Impulse and step response simulation
- `.wav` signal filtering and power spectrum analysis
- Gain/phase computation
- Experimental vs theoretical Bode plots

### Practical 3 – FIR Filter Design
- FIR system implementation and frequency response
- Filter length and performance tradeoffs
- Visualization of filtering effects
- (See worksheet for theoretical context)

### Practical 4 – DFT and FFT Analysis
- Manual DFT matrix computation
- Symmetry and conjugation in transforms
- Parseval’s theorem and energy conservation
- FFT implementation and performance gains

> These practicals were designed as **skill-building exercises** rather than full projects. Emphasis is on signal understanding and implementation from first principles.

---

## Requirements

This repository does **not** include a `requirements.txt` file.

To run the notebooks, make sure you have the following Python libraries installed:
```bash
pip install numpy scipy matplotlib jupyter
```
Or use:
```bash
conda install numpy scipy matplotlib jupyter
```

---

## Repository Structure

```bash
DSP-Labs/
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

## Author

**Graham Pellegrini**  
University of Malta  
GitHub: [@GrahamPellegrini](https://github.com/GrahamPellegrini)
