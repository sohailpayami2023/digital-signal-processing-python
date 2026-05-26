# Digital Signal Processing & Wireless Communications in Python

A practical, hands-on guide to DSP and wireless communications in Python — bridging the gap from MATLAB for engineers with a background in signal processing and wireless systems (LTE, 5G NR).

---

## Project Status
**Module 1 complete.** Core signal analysis tools — cosine generation, IQ representation, AWGN, FFT, and spectrogram — are implemented and documented. Module 2 (filtering) is next.

## Objectives

Build a deep, hands-on understanding of how digital information is transformed into physical waves, transmitted through a simulated wireless channel, and recovered — implemented from scratch in Python.

---

## Roadmap

### Module 1: Signal Fundamentals
- [x] `01_sine_and_noise.ipynb` — Cosine wave, complex baseband (IQ), AWGN noise, FFT / power spectrum, spectrogram (STFT)
- [x] `02_matplotlib_plotting_basics.ipynb` — Python/Matplotlib plotting guide for MATLAB users

### Module 2: Spectral Analysis & Filtering
- [ ] `03_fir_filter_design.ipynb` — FIR filter design (windowed-sinc, `firwin`), frequency response, group delay
- [ ] `04_iir_filter_design.ipynb` — Butterworth and Chebyshev IIR filters, pole-zero analysis
- [ ] `05_filter_application.ipynb` — Noise removal, channel separation, real-signal filtering examples

### Module 3: Digital Modulation
- [ ] `06_modulation_basics.ipynb` — Constellation mapping (BPSK, QPSK, 16-QAM, 64-QAM), EVM calculation
- [ ] `07_ber_vs_snr.ipynb` — BER vs SNR curves for common modulation schemes

### Module 4: Pulse Shaping
- [ ] `08_pulse_shaping.ipynb` — Root Raised Cosine (RRC) filter, eye diagram, Inter-Symbol Interference (ISI)

### Module 5: OFDM from Scratch
- [ ] `09_ofdm_basics.ipynb` — IFFT/FFT block processing, Cyclic Prefix (CP) insertion and removal
- [ ] `10_ofdm_resource_grid.ipynb` — Resource grid, pilot patterns, time-frequency structure

### Module 6: Channel Models
- [ ] `11_channel_models.ipynb` — Flat Rayleigh fading, TDL-A / TDL-C (3GPP NR channel models)
- [ ] `12_channel_statistics.ipynb` — Doppler, delay spread, BER analysis

### Module 7: Channel Estimation
- [ ] `13_ls_channel_estimation.ipynb` — Least Squares (LS) pilot-based estimation
- [ ] `14_mmse_channel_estimation.ipynb` — MMSE estimation, DMRS-inspired pilot patterns (NR)

### Module 8: MIMO & Beamforming
- [ ] `15_mimo_spatial_multiplexing.ipynb` — 2×2 spatial multiplexing, capacity
- [ ] `16_svd_precoding.ipynb` — SVD precoding, singular value analysis
- [ ] `17_beamforming_basics.ipynb` — Phased arrays, array response vectors, BER analysis

---

## Tech Stack

| Library | Purpose |
|---------|---------|
| `NumPy` | Numerical operations and matrix math (≈ MATLAB arrays) |
| `SciPy` | Signal processing toolbox — filters, spectrogram, chirp, channel models |
| `Matplotlib` | Waveform and spectrum visualisation |
| `Commpy` *(planned)* | Digital communications tools |

## How to Use

Notebooks are designed for **Google Colab** — open directly from the repo to experiment with parameters in real time. All dependencies are standard scientific Python (`numpy`, `scipy`, `matplotlib`).

---

*Developed with AI assistance (ChatGPT, Claude) as part of the learning process.*  
*A practical resource at the intersection of Python, wireless communications, and signal processing.*
