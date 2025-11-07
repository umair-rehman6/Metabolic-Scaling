# A Continuous Metabolic Scaling Law Unifies Geometric and Network Limits

This repository contains code and data for analyzing metabolic rate scaling in mammals using a kernel-augmented regression model. The project demonstrates that local metabolic exponents vary continuously with body mass and temperature, offering a unified explanation for the classical \(2/3\) geometric and \(3/4\) network-based scaling laws.

## 📁 Repository Structure

```
├── 6428table1.html                 # White & Seymour mammalian dataset (from PNAS 2003)
├── Curved_Metabolic_Scaling.ipynb  # Main analysis notebook (Colab-compatible)
├── README.md                       # The current document. 
```

## 📊 Dataset

**White & Seymour (2003)** — "Mammalian basal metabolic rate is proportional to body mass\(^{2/3}\)". Published in *PNAS*, vol. 100, no. 7, pp. 4046–4049.
- Source file: `6428table1.html`
- Parsed directly by the notebook.

## 🧠 Key Features

- **Kernel-OLS Regression**: Explicit fixed-feature mapping without black-box kernels.
- **Local Scaling Exponent**: Calculated analytically and visualized to reveal curvature.
- **Robustness Checks**: Cross-validation, residual diagnostics, and per-order fits.
- **Model Comparisons**: AIC, likelihood ratios vs. Kleiber and MTE forms.
- **Thermo-geometric Theory**: Derives a continuous function bridging geometric and transport limits.

## 📝 Running the Notebook

1. Clone the repository:
2. Open `Curved_Metabolic_Scaling.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter.
3. Upload `6428table1.html` when prompted.
4. Run all cells. Output figures and diagnostic tables will be generated.

## 📎 Supplementary Materials

See `supplementary Information.pdf` for:
- Full equations 
- Residual plots and confidence envelopes
- Per-order R² values and exponent intervals
- Derivation of the continuum model

## 📄 License

This repository is provided for peer review only. No license granted at this time.

---
