# EWT-Seq2Seq-LSTM with Attention

This repository presents an **optimized EWT-Seq2Seq-LSTM with attention mechanism** model.

Two time-varying sequences are generated to evaluate a sequence-to-sequence learning (**Seq2Seq**) signal.

To extract features from the original signal, the empirical wavelet transform (**EWT**) is used.

The hyperparameters of the model are optimized by **Optuna** and the **attention mechanism** is used.

---

The notebook for the analysis is divided according to the evaluations:

> **Seq2Seq-LSTM with Attention**: _Evaluation of the starting model using the Attention Mechanism_.

> **Optimized Seq2Seq-LSTM with Attention**: _Evaluation with the optimized hyperparameters (based on Optuna)_.

> **Standard Seq2Seq LSTM**: _Standard model for comparative purposes_.

Please go ahead and try it on [Google Colab](https://colab.research.google.com/github/SFStefenon/EWT-Seq2Seq-LSTM-Attention/blob/main/EWT-Seq2Seq-LSTM-Attention.ipynb)!

![image](https://user-images.githubusercontent.com/88292916/224036141-e596f553-1328-4208-9825-e28ee35e96c1.png)

---

The leakage current experiment was carried out by Nemesio Fava Sopelsa Neto under the supervision of Dr. Luiz Henrique Meyer, in the High Voltage Laboratory of the Regional University of Blumenau (FURB), Brazil. Additional information can be found at: https://github.com/SFStefenon/LeakageCurrent

---

Wrote by Dr. **Laio Oriel Seman** and Dr. **Stefano Frizzo Stefenon**.

Trento, Italy, March 10, 2023.



