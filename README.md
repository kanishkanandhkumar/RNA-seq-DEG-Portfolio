#  RNA-seq Differential Expression Analysis Portfolio

## Analysis Results
**COVID-19 vs Control PBMCs Analysis**

| Metric | Value |
|--------|-------|
| **Samples** | 30 (15 COVID, 15 Control) |
| **Genes analyzed** | 10,931 |
| **Significant DEGs** | 680 |
| **Up-regulated in COVID** | 337 genes |
| **Down-regulated in COVID** | 234 genes |

##  Quick Start

### Run Analysis
```bash
# 1. Clone repository
git clone https://github.com/YOUR_USERNAME/RNA-seq-DEG-Portfolio.git
cd RNA-seq-DEG-Portfolio

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run analysis
python src/analyze.py
