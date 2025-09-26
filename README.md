# Regulatory-Style Clin Pharm Report

A concise, **submission-style Clinical Pharmacology / DMPK report** that imports outputs from [`ada-panda-mini`](https://github.com/camontefusco/ada-panda-mini).

## 🎯 Purpose
- **Audience:** regulatory reviewers, program leadership, non-coding stakeholders.  
- **Inputs (from mini repo):**
  - `reports/tlgs.parquet` (tables, listings, figures data)
  - `reports/benchmarks.parquet` (PASS/ALERT flags)
  - `reports/figures/` (pre-generated plots)
- **Outputs:**  
  - `output/ClinPharm_Summary.pdf` — concise submission-style report
  - `output/ClinPharm_Summary.md` — same in Markdown (traceable, auditable)

## 📂 Structure

```arduino
regulatory-style-clinpharm-report/
├─ notebooks/
│  ├─ 01_import_and_QC.ipynb
│  ├─ 02_TLGs_and_figures.ipynb
│  └─ 03_render_report.ipynb
├─ templates/
│  └─ ClinPharm_Summary_template.md
├─ config.yaml
├─ env.yml
├─ Makefile
└─ README.md
```
