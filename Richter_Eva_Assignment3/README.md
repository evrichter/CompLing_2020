# 📊 Assignment 3 — CFGs & CKY Parsing  

This is the third assignment from the **Computational Linguistics lecture** at **Saarland University (WS 2021/22)**.  
The task was to implement the **Cocke–Kasami–Younger (CKY) algorithm** for bottom-up parsing with context-free grammars (CFGs).  

---

## 🔎 Task Overview  

- Implemented a **CKY parser** using the **ATIS CFG** (from the NLTK data package).  
- ATIS CFG originates from the **Airline Travel Information System** project (spoken language processing for airline queries).  
- Evaluated the parser on **98 English test sentences**.  

**Outputs:**  
- `trees_number.txt` → contains results in the format `sentence \t #parses` for each test sentence.  
- `images_parse_trees.pdf` → visualizations of parse trees for ATIS test sentences with 2–5 parses.  

**Runtime:**  
- Recognizer only: **43.7 seconds**  
- Recognizer + parser: **49.8 seconds**  

---

## 📂 Project Structure  

```text
├── CFG_and_CKY_parsing.ipynb
├── trees_number.txt
├── images_parse_trees.pdf
└── README.md
```

*Notes:*  
- `trees_number.txt` appears twice in the assignment output:  
  - One version with **all 98 test sentences** and their parse counts.  
  - One filtered version containing only sentences with 2–5 parses.  
- `CFG_and_CKY_parsing.ipynb` contains the full implementation of the CKY recognizer and parser.  

---

## ⚙️ Environment  

```text
Requirements:
  - python 3.8.5
  - nltk 3.5
  - collections (standard library)
  - itertools (standard library)
  - datetime (standard library)

System Details:
  - OS: Ubuntu 20.04.1 LTS
  - Type: 64-bit
```
