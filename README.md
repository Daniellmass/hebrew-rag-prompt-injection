# Detection and Analysis of Prompt Injection Attacks in RAG Systems in Hebrew

Final project for the Natural Language Processing (NLP) course.

This project investigates the robustness of Retrieval-Augmented Generation (RAG) systems against prompt injection attacks in Hebrew legal documents.

The work focuses on evaluating different attack strategies, analyzing retrieval behavior, and identifying weaknesses in Hebrew RAG pipelines.

---

## Overview

The project implements a complete Hebrew RAG pipeline, including:

- Hebrew legal document preprocessing
- Dataset cleaning and normalization
- Sentence-aware chunking
- Dense embedding generation
- FAISS vector retrieval
- Prompt injection attack evaluation
- Retrieval and generation analysis

The experiments compare model behavior under clean and adversarial conditions to better understand how prompt injection affects retrieval-based language models.

---

## Features

- Hebrew legal corpus preprocessing
- Sentence-based chunking
- AlephBERT embeddings
- FAISS semantic search
- GPT-based answer generation
- Direct prompt injection attacks
- Indirect prompt injection attacks
- Metadata injection attacks
- Cross-chunk injection attacks
- Quantitative evaluation and analysis

---

## Repository Structure

```
.
├── Daniel_Mass_Detection_of_Prompt_Injection_Attacks.ipynb
├── requirements.txt
├── README.md
├── docs/
│   ├── index.html
│   └── technical-report.pdf
└── data/
    └── README.md
```

---

## Technical Report

The complete technical report is available in:

```
docs/technical-report.pdf
```

or through GitHub Pages (after deployment).

---

## Dataset

The original dataset is **not included** in this repository.

The project uses a cleaned subset of Hebrew legal documents derived from publicly available Israeli Supreme Court rulings.

Please refer to the notebook for the preprocessing pipeline.

---

## Requirements

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open the notebook:

```
Daniel_Mass_Detection_of_Prompt_Injection_Attacks.ipynb
```

or run it directly using Google Colab.

---

## Results

The experiments evaluate:

- Retrieval quality
- Robustness against prompt injection
- Model behavior under adversarial inputs
- Retrieval failure cases
- Comparative performance across different LLMs

Detailed experimental results are presented in the technical report.

---

## Author

**Daniel Mass**

B.Sc. Computer Science  
Reichman University

---

## License

This repository is intended for educational and research purposes.