# 🎙️ Linguistic Style in Political Discourse  
**A Quantitative Analysis of Part-of-Speech and Formality Distributions in Joe Biden's 2020 Speeches**

This project analyzes the stylistic differences between Joe Biden's formal and informal speeches in 2020, using part-of-speech (POS) tagging and the Heylighen & Dewaele (1999) F-score to measure formality.

---

## 🧠 Objective  
To explore how linguistic style—specifically formality and syntactic choices—varies across different political speech contexts. The focus is on comparing:
- 📢 **Democratic Convention Speech** (formal)  
- 🦃 **Thanksgiving Day Speech** (informal)  

---

## 🛠️ Tools & Methods  
- **Python** for data processing and analysis  
- **spaCy** for POS tagging  
- **Heylighen & Dewaele’s F-score** as the primary formality metric  
- **Pandas** for data organization  
- **Matplotlib** for visualization  

---

## 🔍 Analysis Steps  
1. **Data Collection**: Transcripts of two Biden speeches were retrieved and preprocessed.  
2. **POS Tagging**: spaCy was used to tag each token with its part-of-speech category.  
3. **Formality Score**: The F-score was computed based on POS frequency using the formula:  
   \[
   F = \frac{(noun\% + adjective\% + preposition\% + article\%) - (pronoun\% + verb\% + adverb\% + interjection\%) + 100}{2}
   \]
4. **Comparison & Visualization**: Differences in POS distribution and formality were plotted and interpreted.

---

## 📈 Key Findings  
- The **Democratic Convention Speech** had a **higher F-score**, indicating more formal language.  
- **Pronouns and verbs** were more frequent in the informal speech, aligning with a conversational tone.  
- The formal speech favored **nouns, prepositions, and articles**, consistent with more structured discourse.  

These results demonstrate how political figures adjust their linguistic style to match the formality of the occasion, which is relevant for political communication, sociolinguistics, and NLP applications.

---

## 📄 Full Project Available on OSF  
🔗 [https://osf.io/e9kct/](https://osf.io/e9kct/)  
📌 DOI: [10.17605/OSF.IO/E9KCT](https://doi.org/10.17605/OSF.IO/E9KCT)

---

## 📚 References  
- Heylighen, F., & Dewaele, J.-M. (1999). *Formality of language: definition, measurement and behavioral determinants*.  
- spaCy Documentation: https://spacy.io  

---

## 👩‍💻 Author  
**Regina Kukuh Prasetyo Ati**  
Linguist & NLP Enthusiast  

---

> This project is part of my academic research portfolio combining linguistics, NLP, and applied data analysis.
