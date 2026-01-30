# 🔍 Resume & Job Description Matching using NLP

An NLP-based project that analyzes how well a candidate’s resume matches a given job description by calculating a similarity score and identifying missing skills.

## ✨ Features

- 📄 Upload or paste resume text
- 📃 Input job description
- 🧠 Text preprocessing using NLP techniques
- 📊 Similarity score using TF-IDF & Cosine Similarity
- 📈 Match percentage output
- 📝 Highlights missing or weak skills
- 💡 Helps improve resume quality for specific roles

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries & Tools:**
  - NLTK / spaCy
  - Scikit-learn
  - Pandas
  - NumPy
- **NLP Techniques:**
  - Tokenization
  - Stopword Removal
  - Lemmatization
  - TF-IDF Vectorization
  - Cosine Similarity

## ⚙️ How It Works

1. Load resume and job description text
2. Preprocess text (cleaning, tokenization, lemmatization)
3. Convert text into numerical vectors using TF-IDF
4. Calculate similarity using Cosine Similarity
5. Display match percentage and insights
