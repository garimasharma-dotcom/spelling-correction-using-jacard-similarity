📝 Spelling Correction Using Jaccard Similarity

A Python-based Natural Language Processing (NLP) project that performs **spelling correction** using the **Jaccard Similarity** algorithm. The project compares character n-grams of misspelled words with a predefined dictionary and suggests the most similar correct word.

---

## 📌 Project Overview

This project demonstrates how **Jaccard Similarity** can be used to identify and correct spelling mistakes. Instead of relying on machine learning models, it uses a simple similarity-based approach that compares the overlap between character n-grams of words.

The notebook includes:
- Text preprocessing
- Character n-gram generation
- Jaccard Similarity calculation
- Spell correction function
- Testing with multiple misspelled words

---

## 🚀 Features

- Convert words into character n-grams
- Calculate Jaccard Similarity between words
- Suggest the closest matching word
- Simple and beginner-friendly implementation
- Easy to customize with your own dictionary

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Regular Expressions (`re`)
- Jaccard Similarity Algorithm

---

## 📂 Project Structure

```
Spelling-Correction-Using-Jaccard-Similarity/
│
├── speling correction using jacard similarity.ipynb
└── README.md
```

---

## ⚙️ How It Works

1. Preprocess the input word.
2. Generate character n-grams (default: bigrams).
3. Generate n-grams for every word in the dictionary.
4. Compute the Jaccard Similarity score.
5. Return the word with the highest similarity score.

---

## 📊 Example

**Input**

```
recieve
freind
machin
scince
```

**Output**

```
receive
friend
machine
science
```

---

## 📚 Concepts Covered

- Natural Language Processing (NLP)
- Text Preprocessing
- Character N-grams
- Set Operations
- Jaccard Similarity
- String Matching

---

## 🎯 Applications

- Spell Checking Systems
- Search Engine Query Correction
- Text Processing
- Auto Suggest Systems
- Educational NLP Projects

---

## 🔮 Future Improvements

- Use a larger dictionary
- Support multiple languages
- Add GUI using Tkinter or Streamlit
- Improve accuracy using Edit Distance (Levenshtein Distance)
- Build a real-time spell checker

---

## 👩‍💻 Author

**Garima**

If you found this project helpful, consider giving it a ⭐ on GitHub!
