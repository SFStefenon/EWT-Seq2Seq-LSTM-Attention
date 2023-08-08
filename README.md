# EWT-Seq2Seq-LSTM with Attention

This repository presents an **optimized EWT-Seq2Seq-LSTM with attention mechanism** method.

Two time-varying sequences are considered to evaluate a sequence-to-sequence (**Seq2Seq**) signal.

To extract features from the original signal, the empirical wavelet transform (**EWT**) is used.

The hyperparameters of the model are optimized by **Optuna** and the **attention mechanism** is used.

---

The notebook for the analysis is divided according to the evaluations:

> **Seq2Seq-LSTM with Attention**: _Evaluation of the starting model using the Attention Mechanism_.

> **Optimized Seq2Seq-LSTM with Attention**: _Evaluation with the optimized hyperparameters (based on Optuna)_.

> **Standard Seq2Seq LSTM**: _Standard model for comparative purposes_.

Please go ahead and try it on [Google Colab](https://colab.research.google.com/github/SFStefenon/EWT-Seq2Seq-LSTM-Attention/blob/main/EWT-Seq2Seq-LSTM-Attention.ipynb)!

---

Additional information can be found at the **[Original Paper](https://doi.org/10.3390/s23063202)**.

Klaar, A. C. R., Stefenon, S. F., Seman, L. O., Mariani, V. C., Coelho, L. S. Optimized EWT-Seq2Seq-LSTM with attention mechanism to insulators fault prediction, Sensors, vol. 23, number 6, p 3202, 2023.

BibTeX:
`@Article{s23063202, AUTHOR = {Klaar, Anne Carolina Rodrigues and Stefenon, Stefano Frizzo and Seman, Laio Oriel and Mariani, Viviana Cocco and Coelho, Leandro dos Santos}, TITLE = {Optimized {EWT-Seq2Seq-LSTM} with attention mechanism to insulators fault prediction}, JOURNAL = {Sensors}, VOLUME = {23}, YEAR = {2023}, NUMBER = {6}, PAGES = {3202}, DOI = {10.3390/s23063202}}`

---

The leakage current experiment was carried out by Nemesio Fava Sopelsa Neto under the supervision of Dr. Luiz Henrique Meyer, in the High Voltage Laboratory of the Regional University of Blumenau (FURB), Brazil. Additional information are available at: https://github.com/SFStefenon/LeakageCurrent.

---
Thank you.

Dr. **Stefano Frizzo Stefenon** and Dr. **Laio Oriel Seman**.

Trento, Italy, March 10, 2023.

