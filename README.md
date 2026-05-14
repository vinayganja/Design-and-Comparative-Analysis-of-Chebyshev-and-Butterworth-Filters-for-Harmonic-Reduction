### Design and Comparative Analysis of Chebyshev and Butterworth Filters for Harmonic Reduction in Power Systems using MATLAB

### Overview
This project focuses on the **design, implementation, and comparative performance analysis** of **Chebyshev Type-I** and **Butterworth** IIR digital filters for reducing harmonic distortion in power systems. Using MATLAB, the system processes signals containing fundamental frequency (50 Hz) + 3rd and 5th harmonics, demonstrating effective harmonic suppression while preserving the main signal.

### Key Highlights
- **Filters Designed**: Chebyshev Type-I and Butterworth (IIR)
- **Purpose**: Harmonic reduction (3rd & 5th order) in power signals
- **Methodology**: Frequency-domain analysis, FFT-based evaluation, waveform comparison
- **Performance Metrics**: Time-domain waveforms, Frequency spectra, Total Harmonic Distortion (THD)
- **Results**: Both filters significantly reduce harmonics; Butterworth showed slightly better THD reduction in the test case

### Objectives
- Design Chebyshev and Butterworth filters in MATLAB
- Apply filters to harmonic-contaminated power signals
- Compare performance in terms of harmonic attenuation, waveform quality, and THD
- Analyze trade-offs (sharp transition vs. passband flatness)

### Results & Discussion
- **Time-domain**: Both filters convert distorted waveforms into near-sinusoidal outputs
- **Frequency-domain**: Significant suppression of 150 Hz and 250 Hz harmonics while preserving 50 Hz fundamental
- **THD Improvement**:
  - Before filtering: **2.3005**
  - After Chebyshev: **2.2532**
  - After Butterworth: **2.2345** (slightly better)
- **Chebyshev**: Sharper transition band (good for close harmonics)
- **Butterworth**: Maximally flat passband (smoother fundamental preservation)

### Technologies & Tools
- **Software**: MATLAB
- **Techniques**: IIR Filter Design (`butter`, `cheby1`), `freqz`, FFT/IFFT, THD calculation
- **Visualization**: Waveforms, Magnitude/Phase responses, Spectra

---

**Status**: Successfully designed, simulated, and compared (March 2026)
