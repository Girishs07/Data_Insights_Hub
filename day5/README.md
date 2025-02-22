# IPL Commentary Data Analysis

## Overview
This project aims to analyze and process IPL cricket commentary data using Natural Language Processing (NLP) techniques. The dataset is cleaned, structured, and visualized to extract valuable insights. The key tasks involve generating a **word cloud**, extracting structured information from commentary, and implementing text vectorization techniques.

## Tasks Breakdown

### 1️⃣ Commentary Word Cloud
**Description:**
- Create a **Word Cloud** that displays the most frequently used words in IPL commentary.
- Remove common stopwords like "the", "a", etc., before generating the visualization.

**Expected Output:**
- A **Word Cloud Figure** where frequently occurring words are displayed larger.

**Level:** Beginner

**Reference:** Matplotlib, WordCloud Library

---

### 2️⃣ Commentary to Table
**Description:**
- Extract key features from the **commentary** column using **Regular Expressions (Regex)**:
  1. **Bowler Name**
  2. **Batter Name**
  3. **Ball Type** (Wide Ball, No Ball, etc.)
  4. **Shot Type** (Boundary, Single, Dot Ball, etc.)
  5. **Speed of Ball** (if mentioned)
  6. **Runs Scored**
- Convert extracted information into a structured table.

**Expected Output:**
- A **Structured Table** containing the extracted columns.

**Level:** Intermediate

**Reference:** Regular Expressions (Regex), Pandas

---

### 3️⃣ Text Pre-processing Methods using Scikit-Learn
**Description:**
- Implement at least **two feature extraction methods** to convert text into numerical vectors:
  1. **CountVectorizer()** - Converts text into a frequency-based matrix.
  2. **TfidfVectorizer()** - Converts text into a TF-IDF weighted representation.
- These techniques are fundamental for training **Large Language Models (LLMs)** like ChatGPT.

**Expected Output:**
- **Vectorized Representations of Text** using CountVectorizer & TfidfVectorizer.

**Level:** Advanced

**Reference:** Scikit-learn, NLP Techniques

---

## Installation & Setup
### 1️⃣ Install Required Libraries
```bash
pip install pandas matplotlib wordcloud scikit-learn seaborn openpyxl
```

### 2️⃣ Run Jupyter Notebook (if applicable)
```bash
jupyter notebook
```

## Usage
- Load the dataset into a **Jupyter Notebook**.
- Run each **task script** to generate the expected outputs.
- Visualize and analyze the insights.

## License
This project is under the **MIT License**.

