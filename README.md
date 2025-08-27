# Text Mining: Analyzing Research Abstracts

## 📖 Project Overview
This project was developed as part of the **MATH6183 Data Mining coursework**.  
It applies **text mining and machine learning techniques** to analyze **4,385 article abstracts** published between 2000–2022 in three journals:
- *Journal of the Operational Research Society*  
- *Health Systems*  
- *Journal of Simulation*  

The analysis pipeline includes **text preprocessing, TF-IDF, topic modeling, regression, classification, clustering, and PCA visualization**.

---

## 📊 Data
- Source: Abstracts collected from academic journals (2000–2022)  
- Total documents: **4,385 abstracts**  
- Preprocessing steps:
  - Lowercasing  
  - Removing punctuation, special characters, and stopwords  
  - Stemming and lemmatization  

---

## ⚙️ Methods
1. **Bag-of-Words & TF-IDF**  
   - Extracted most frequent terms by journal  
   - Identified domain-specific keywords (e.g., *asthma*, *IoT*, *cryptocurrency*)  

2. **Topic Modeling (LDA)**  
   - Extracted 3 main topics:  
     - Topic 1: Healthcare & patient systems  
     - Topic 2: Optimization & decision-making  
     - Topic 3: Modeling & simulation  
   - Tracked topic trends over time  

3. **Regression Analysis**  
   - Built a multiple regression model to predict citation counts  
   - Found that *views* variable had strongest positive impact  

4. **Classification & Association Rules**  
   - Classification model achieved **~87.6% accuracy**  
   - Discovered strong associations (e.g., `{monte} => {carlo}` with 100% confidence)  

5. **Clustering (K-means)**  
   - Grouped abstracts into 3 clusters:  
     - Medical/Health  
     - Nursing/Social Care  
     - Simulation & Operations Research  

6. **Dimensionality Reduction (PCA)**  
   - Visualized clustering results in 2D space  

---

## 📈 Key Results
- **Health Systems** abstracts strongly associated with medical and patient care terms.  
- **Journal of Simulation** dominated by technology and modeling-related keywords.  
- **Operational Research Society** focused on optimization, finance, and emerging fields (e.g., cryptocurrency).  
- LDA showed increasing research attention to healthcare topics post-2015.  
- Classification achieved **accuracy ≈ 87.65%** (moderate Kappa = 0.467).  

---

## 📂 Repository Structure

