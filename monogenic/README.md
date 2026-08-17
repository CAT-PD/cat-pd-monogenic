# Central Asian and Transcaucasian Parkinson's disease Genetics Study Consortium (CAT-PD Consortium)

## Short tandem repeat analysis

### Repository structure

```bash=
root/
├── LICENSE
├── README.md
└── Repeat_Expansions_with_ExpansionHunter.ipynb
```

### Details
The code uses `ExpansionHunter` tool to estimate STR based on predefined `variant_catalog.json`. Used on CAT-PD srWGS CRAM files. ExpansionHunter generates json and vcf files, which are parsed in this notebook to create more precise json files of carriers based on predefined pathogenic ranges (stratified by AR, AD mode of inheritance).

Software used:

|Item| Version|
|-----|-------|
|ExpansionHunter | 3.1.2|
