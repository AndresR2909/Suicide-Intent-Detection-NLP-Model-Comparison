**Suicide Intent Detection: NLP Model Comparison**
This project compares several approaches for detecting suicidal intentions in online text. It evaluates the effectiveness and efficiency of different models in the context of suicide intent detection, utilizing techniques like zero-shot, few-shot, and fine-tuning.

Approaches
The following four approaches are implemented and compared in this project:

* XGBoost with BERT Embeddings
Tokenizes and creates text embeddings using BERT to feed into an XGBoost model for classification.

* Large Language Model (LLM): ChatGPT-4
Utilizes ChatGPT-4 with zero-shot and few-shot learning to detect suicide intent based on online text.

* LLaMA Models (LLaMA 3.1 8B and LLaMA 3.2 3B)
Compares versions of LLaMA models, using zero-shot, few-shot, and fine-tuning techniques to enhance performance.

* DistilBERT
A smaller, more efficient version of BERT. Fine-tuning is applied to tailor the model for the specific task of suicide intent detection.
