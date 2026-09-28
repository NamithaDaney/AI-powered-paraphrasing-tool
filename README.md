# AI-powered-paraphrasing-tool
An advanced, console-based Natural Language Processing (NLP) module designed to rewrite text block segments while meticulously balancing **meaning preservation**, **syntactic clarity**, and **lexical originality**. 

This application combines a fine-tuned Deep Learning sequence-to-sequence model with an extensive mathematical evaluation pipeline (BLEU, ROUGE-L, and Semantic Vector Cosine Similarity) to guarantee high-quality rewrites that bypass rigid plagiarism systems.

##  System Architecture & Engine Layout

| Module Components | Core Engine Technology Used | Technical Purpose |
| :--- | :--- | :--- |
| **Sentence Tokenizer** | `nltk` (Punkt Engine) | Splits textual blocks into isolated sentences for exact, grain-level processing. |
| **Paraphrasing Model** | `humarin/chatgpt_paraphraser_on_T5_base` | Fine-tuned T5 model built to perform deep syntactic and voice shifts (e.g., Active-to-Passive voice transformations). |
| **Semantic Evaluator** | `sentence-transformers/all-MiniLM-L6-v2` | Transforms sentences into structural dense vectors to measure Cosine Similarity matching metrics. |
| **Overlap Diagnostics** | `evaluate` (BLEU & ROUGE-L tracking) | Measures n-gram sequence matching counts to quantify structural variations and plagiarism safety. |

