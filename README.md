# Statistical Analysis of Shannon's Equitability in Serbian Texts Generated from Cyrillic and Latin Prompts

## Contents

- `code/` – Python script for the Wilcoxon signed-rank test, Holm correction, and effect size calculation.
- `data/` – Excel files containing Shannon's equitability values for each model.
- `results/` – Excel table with the statistical results.
  
## Related Repository

The prompts and generated texts used in this study are available in the [Serbian Script LLM Texts](https://github.com/dragicalj/serbian-script-llm-texts.git) repository.

## Requirements

```bash
pip install scipy openpyxl
```

## Usage

Run the analysis using:

```bash
python code/statistical_analysis.py
```

The results are saved in `results/table.xlsx`.
