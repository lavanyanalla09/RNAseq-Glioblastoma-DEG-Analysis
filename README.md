# RNAseq-Glioblastoma-DEG-Analysis
RNA-seq differential expression and pathway analysis using DESeq2 and public GEO datasets.
RNAseq-Glioblastoma-DEG-Analysis
│
├── data
│   ├── counts.csv
│   └── metadata.csv
│
├── scripts
│   ├── 01_preprocessing.R
│   ├── 02_DESeq2_analysis.R
│   └── 03_pathway_analysis.R
│
├── figures
│
├── results
│
└── README.md
counts <- read.csv("data/counts.csv",
                   row.names = 1)

metadata <- read.csv("data/metadata.csv")

head(counts)
head(metadata)
