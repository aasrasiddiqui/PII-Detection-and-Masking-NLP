# PII Detection using NLP

## Overview

This project focuses on detecting **Personally Identifiable Information (PII)** from text using Natural Language Processing techniques.
The model identifies sensitive entities such as names and email.
---

## Objectives

* Detect and classify PII entities in text
* Build a robust NER-based model
* Achieve high accuracy and generalization on unseen data

---

## Approach

* Data preprocessing and cleaning
* Tokenization and labeling for NER
* Model training using transformer-based architecture
* Evaluation using standard metrics

---

## Results

* **F1 Score:** 0.997
* High precision and recall across most entity classes

---

## Error Analysis

* Some misclassification in edge cases:

  * Ambiguous names vs common words
  * Rare entity formats
* Model performance may drop on highly noisy or unseen formats

---

## Improvements

* Increase dataset diversity
* Add rule-based validation for edge cases
* Fine-tune with domain-specific data
* Use ensemble models

---

## Project Structure

```
├── Data/
├── Trained_PII_Model/
├── src/
├── Results/
```


## ▶️ Usage

```bash
python main.py
```

---


## 📌 Key Insights

* Transformer models are highly effective for PII detection
* Data quality has a major impact on performance
* Combining ML with rule-based systems improves robustness

---

## 🏁 Conclusion

This project demonstrates an effective approach to detecting sensitive information using NLP, achieving near-perfect performance while highlighting areas for real-world improvement.

---
