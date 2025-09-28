# Cognitive Effort & Emotion — Poster Figures

This repository reproduces the figures and analyses from my undergraduate research poster on **Cognitive Effort and Emotion Effects on Recognition Memory Performance** in August 2023.
The code generates the four key figures and statistical results presented in the poster.


## Background

Human memory performance is influenced by both the amount of **cognitive effort** invested during encoding and the **emotional valence** of the context.  
In this project, we investigated whether the **self-rated difficulty** of encoding (easy vs hard) and the **emotional condition** (negative vs neutral) would shape subsequent recognition memory accuracy for **words** and **word pairs**.


## Hypotheses

1. **Effort effects**  
   - Words: Hard > Easy recognition  
   - Pairs: Easy > Hard recognition  

2. **Emotion effects**  
   - Easy words: Negative > Neutral (expected, but not significant)  
   - Easy pairs: Negative > Neutral (significant benefit for negative)  


## Methods

- Dataset: `taskanalysis_copy.xlsx` (Sheet1)  
- Items: rated items as **easy** or **hard** during encoding.  
- Conditions: **Negative (neg)** vs **Neutral (neu)** emotional context.  
- Recognition memory was tested for **single words** and **word pairs**.  
- Dependent measures: `itemhit` (word hit rate) and `pairhit` (pair hit rate).  
- Analyses: Welch’s independent t-tests, with group means ± standard error (SE).  


## Results

- **1A. Words (Hard vs Easy):** Hard > Easy, *p* < .001  
- **1B. Pairs (Easy vs Hard):** Easy > Hard, *p* ≈ .02  
- **2A. Easy Words (Neg vs Neu):** n.s., *p* ≈ .16  
- **2B. Easy Pairs (Neg vs Neu):** Negative > Neutral, *p* ≈ .04  

These outcomes replicate the findings reported on the poster.

---

## Figures

Running the notebook or script generates four `.png` figures:

- `Fig1A_Word_HitRate.png`  
- `Fig1B_Pair_HitRate.png`  
- `Fig2A_EasyWord_Condition.png`  
- `Fig2B_EasyPair_Condition.png`  

---

## Files

- `figs` — figures generated.  
- `Cognitive_Effort_Data_Analysis.ipynb` — notebook (load data, run tests, plot figures)
- `taskanalysis_copy.xlsx` — Data file (kept local).
- `Cognitive Effort Poster _2023.pdf` - Poster presented with figures

---
## Citation 
He, E.*, Nelson A.* (2023, August 4). \textit{The Effects of Cognitive Effort and Post-Encoding Emotional Arousal on Recognition Memory Performance} [poster presentation]. Summer Undergraduate Research Experience Symposium, Atlanta, Georgia, United States.

