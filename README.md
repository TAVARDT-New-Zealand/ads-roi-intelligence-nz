# Paid Media ROI Intelligence and Mathematical Modeling | TAVARDT New Zealand

[![ROI Calculator](https://img.shields.io/badge/TAVARDT-ROI%20Calculator-5b3cf5.svg)](https://tools.tavardt.com/nz/paid-media-roi-calculator/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-New%20Zealand-00C853.svg)](https://ag.tavardt.com/nz/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Mathematical modeling utility for ROAS, ROI, and diminishing returns budget forecasting across New Zealand commercial media spend.

Developed and maintained by the revenue engineering and paid performance division of **[TAVARDT New Zealand](https://ag.tavardt.com/nz/)**.

---

## Mathematical Modeling and Core Metrics

* **Base ROAS**: Direct ratio between gross generated revenue and paid media expenditure.
* **Base ROI**: Net percentage return on capital allocated to paid advertising.
* **Scale Forecasting with Diminishing Returns**: Algorithmic decay modeling (standard coefficient 0.85) projecting marginal efficiency and performance degradation as budgets scale.
* **Structured Output Formats**: Terminal table output or JSON payloads ready for ingestion into analytics pipelines.

---

## Installation and Quick Start

Requires Python 3.8 or higher using strictly standard library modules with zero third-party packages.

```bash
git clone https://github.com/TAVARDT-New-Zealand/ads-roi-intelligence-nz.git
cd ads-roi-intelligence-nz
python roi_engine.py --spend 10000 --revenue 50000 --target-spend 25000
```

To export results in structured JSON format:

```bash
python roi_engine.py --spend 10000 --revenue 50000 --target-spend 25000 --json
```

Also includes the Node.js and browser-compatible JavaScript utility in `calculator.js`.

---

## Interactive Web Calculator

For advanced scenario modeling, graphical simulations, and budget sensitivity charts, access the official web diagnostic suite:

* **[Paid Media ROI and Scale Calculator](https://tools.tavardt.com/nz/paid-media-roi-calculator/)**
* **[TAVARDT New Zealand Corporate Portal](https://ag.tavardt.com/nz/)**

---

## Revenue Engineering Consulting

For corporate media spend optimization, econometric modeling, and high-ticket B2B scale in New Zealand, contact **[TAVARDT New Zealand](https://ag.tavardt.com/nz/contact/)**.
