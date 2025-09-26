# regulatory-style-clinpharm-report
A concise, submission-style Clin Pharm/DMPK report that imports outputs from ada-panda-mini.

Repo purpose

Readers: regulatory reviewers, program leads, non-coding stakeholders.

Inputs (from ada-panda-mini):
reports/tlgs.parquet, reports/benchmarks.parquet, figures in reports/figures/.

Outputs: output/ClinPharm_Summary.pdf (+ a web HTML if you want).

Minimal file tree
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
