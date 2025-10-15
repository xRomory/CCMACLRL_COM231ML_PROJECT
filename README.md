# CCMACLRL_COM231ML_PROJECT

# Cross-Linguistic Fake News Detection Using Machine Learning

This research investigates how machine learning models trained on English-language datasets perform when tested on Filipino-language fake news data — and whether retraining them on Filipino datasets restores accuracy. The study aims to determine whether performance drops are caused by **language mismatch** rather than **model inefficiency**.

---

## Research Description

Fake news continues to pose a global challenge, influencing public opinion and distorting democratic discourse. While existing fake news detectors perform well on English data, their effectiveness often declines when applied to other languages such as Filipino due to linguistic and contextual differences.

This study evaluates the **cross-linguistic generalizability** of four traditional machine learning algorithms:

- **Naive Bayes**  
- **Logistic Regression**  
- **Support Vector Machine (SVM)**  
- **Random Forest**

The models were trained and tested in three phases:

1. **Phase 1 – English-to-English Evaluation**  
   Models were trained and evaluated using English fake and real news datasets to establish baseline performance.

2. **Phase 2 – Cross-Linguistic Evaluation**  
   English-trained models were tested on Filipino-language data to assess how linguistic mismatch affects model accuracy and F1-scores.

3. **Phase 3 – Filipino-to-Filipino Evaluation**  
   Models were retrained using the Filipino dataset and re-evaluated to determine whether native-language retraining restores performance.

---

## Key Findings

- English-trained models achieved near-perfect accuracy (F1 ≈ 0.99) when evaluated on English data.  
- When tested on Filipino data, accuracy dropped significantly (F1 ≈ 0.31–0.67), showing that models struggled with language and contextual transfer.  
- Retraining with Filipino datasets restored high accuracy and F1-scores (≈ 0.93–0.97), confirming that **language-specific data is essential** for reliable fake news detection.  
- Results demonstrate that performance degradation was due to **language mismatch**, not **model inefficiency**.

---

## Research Contribution

This study contributes to the growing field of **multilingual fake news detection** by:
- Empirically showing the limitations of English-trained models on Filipino text.
- Demonstrating that retraining with localized data restores performance.
- Providing benchmark results for future cross-linguistic research in low-resource languages like Filipino.

---

## Keywords
`Fake News Detection` · `Machine Learning` · `Cross-Linguistic Evaluation` · `Language Mismatch` · `Filipino Dataset` · `SVM` · `Naive Bayes` · `Logistic Regression` · `Random Forest`

---

**Research Paper:**  
*Cross-Linguistic Fake News Detection Using Machine Learning: A Comparative Study on English and Filipino News Datasets*  
Authored by:
- **Chris Lawrence De Vera**, National University – Manila (2025)
- **Lovely Joy Reyes**, National University – Manila (2025)
- **Jude Renwell Prodigalidad**, National University – Manila (2025)
