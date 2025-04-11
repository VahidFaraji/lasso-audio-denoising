# 🎧 LASSO Audio Denoising

This project applies **LASSO regression** to remove noise from audio signals by exploiting **sparse frequency representations**. The technique solves a linear inverse problem using L1 regularization.

---

## 🔊 Problem

We are given a noisy piano signal `y = Ax + e`, where `A` is a transformation matrix (e.g., inverse DCT), and `x` is a sparse frequency-domain signal. The goal is to recover `x` and reconstruct the clean sound.

---

## 📦 Files

- `code/lasso.py` – LASSO denoising functions
- `notebooks/Task6_7.ipynb` – Full walkthrough: load, denoise, compare, play
- `data/A1_data.mat` – Contains `Xaudio` and noisy signal
- `results/denoised_audio.wav` – Output (optional)

---

