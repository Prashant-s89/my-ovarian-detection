# my-ovarian-detection
Ovarian cancer detection – imaging + CA‑125 fusion
# Ovarian Cancer Detection Project

A collection of AI tools for early ovarian‑cancer detection from ultrasound + lab markers.

## What’s inside
- [`oc-prediction`](https://github.com/<your-org>/oc-prediction) – end‑to‑end prediction pipeline (imaging + CA‑125).
- [`OvaMTA`](https://github.com/<your-org>/OvaMTA) – multi‑task attention model (segmentation + detection + diagnosis).
- [`DMMN-ovary`](https://github.com/<your-org>/DMMN-ovary) – whole‑slide patch classifier (Deep Multi‑Magnification Network).

## Quick start
```bash
# clone the repo
git clone https://github.com/<your-org>/my-ovarian-detection.git
cd my-ovarian-detection

# install dependencies
pip install -r requirements.txt   # (add your deps here)

# run inference
python scripts/inference.py --image path/to/scan.png
