# Transformer-Based Event Extraction from Financial News Articles
---
## Abstract
In the modern era of information abundance, financial news plays a pivotal role in shaping investment decisions and market trends. 
Financial news articles contain valuable insights into market events, company performance, and economic indicators. 
Extracting relevant events from these articles is essential for investors, analysts, and traders. 
Traditional event extraction methods struggle with the complexity and nuance of natural language, which motivates the use of transformer-based models.

This project uses transformer models, particularly BERT and its successors, to identify and classify events in financial news. These events include earnings reports, mergers and acquisitions, and economic indicators such as unemployment rates and GDP growth. 
A pre-trained model is fine-tuned on annotated financial news data. It captures both **explicit** and **implicit** event mentions, and the attention mechanism offers some interpretability. 
The approach is adaptable to different financial domains and scales well.
---

**Research questions:**

1. How accurately can fine-tuned transformer models extract events from financial news?
2. Can they detect implicit event mentions that rule-based systems miss?
3. What does the attention mechanism reveal about which text drives predictions?

---

## Key Features

- Fine-tuning of pre-trained transformers (BERT, [RoBERTa / FinBERT / others]) for financial event extraction
- Detection of both explicit and implicit event mentions
- Adaptation to financial domain jargon
- Attention-based interpretability analysis
- Comparison against a rule-based or traditional baseline: [specify]

---

## Methodology

1. **Pre-training:** Start from a model pre-trained on a large text corpus.
2. **Data preparation:** Collect, clean, and annotate financial news with event labels.
3. **Fine-tuning:** Adapt the model to financial language using labeled event data.
4. **Event extraction:** Identify and classify event mentions: 
5. **Evaluation:** Measure precision, recall, and F1 against the baseline(s).
6. **Interpretability:** Visualize attention to see which text contributes most to predictions.





