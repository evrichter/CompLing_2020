# 📊 Assignment 1 — Zipf's Law & Random Text Generation  

This is the first assignment from the **Computational Linguistics lecture** at **Saarland University (WS 2021/22)**.  
It consists of two parts: an implementation and verification of **Zipf’s Law**, and a **random text generator** based on n-gram models.  

---

## 🔎 Zipf's Law  

Zipf's Law states that when words are ranked by their frequency, the frequency of a word is inversely proportional to its rank.  

- For each corpus, a list of unique words was computed and sorted by descending frequency.  
- **Matplotlib** was used to plot the frequency curves:  
  - one plot with linear axes  
  - another plot with log–log axes  

**Datasets:**  
- *King James Bible*  
- *The Jungle Book*  
- *SETIMES* Turkish–Bulgarian parallel newspaper text  

---

## ✍️ Random Text Generation  

Reimplementation of the classic *“Dissociated Press”* system:  

- Generates random text from an **n-gram language model** trained on a corpus.  
- Produced text samples of 100 words in length.  
- Parameter *n* varied between **2–4**.  

**Dataset:**  
- *War and Peace*  

---

## 📂 Project Structure  

```text
├── Zipfs_Law.ipynb
├── Random_Text_Generation.ipynb
├── data/
└── README.md

--- 
 
### Requirements: 
          python 3.8.5
          matplotlib 3.3.3
          nltk 3.5
               
### System Details: 
        	 OS Ubuntu 20.04.1 LTS
 	         OS type 64 bit
