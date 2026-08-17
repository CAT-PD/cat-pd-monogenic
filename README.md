# Central Asian and Transcaucasian Parkinson's disease Genetics Study Consortium (CAT-PD Consortium)

## Rare variant analysis and burden tests

### Repository structure

```bash=
root/
├── LICENSE
├── README.md
├── 00_Rare_Variant_Association_and_Burden_Tests.ipynb
├── 01_Extract_per_Sample_GT_and_Annotation.ipynb
├── 02_get_ucsc_bed.py
└── 03_GBA1.ipynb
```

### Details
|Notebook| Description|
|---|---|
|**00_Rare_Variant_Association_and_Burden_Tests.ipynb**| Comprehensive pipeline for rare variant association (Plink assoc, fisher, glm) and burden testing (RVtests SKAT/SKAT-O). |
|**01_Extract_per_Sample_GT_and_Annotation.ipynb**| Get genotype data per sample and append annotation.|
|**02_GBA1.ipynb**| Run [Gauchian](https://github.com/Illumina/Gauchian) for GBA1 on WGS CRAM files.  |

Software used:

|Item| Version|
|-----|-------|
|Plink1.9 | 20250615|
|Plink2.0 |20250609|
|RVtests |2.1.0|
