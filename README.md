# Machine_Learning_Project_BodyDismorphia_ESCO4_Capstone

**Contribution:** EDA Dashboard Analysis, Machine Learning KNN Model  

UofA Capstone team project: utilized machine learning, data analytics, and anonymous surveys to understand future trends of BDD tied to social media.

📊 **Shiny app website (Desktop supported only):**  
[BDD and Social Media Dashboard](https://jconnors159.shinyapps.io/BDDandSocialMedia/)

---

## BDD Scores Across Genders

“BDD Scores across Genders” is a histogram that looks at the distribution of BDD scores by personal pronouns (*he, she, or they*).  

- **She/Her:** Peak score of **30.0**, with wide distribution.  
- **He/Him:** Peak score of **21.3**.  
- **They/Them:** Peak score of **22.6**.  

---

## Class Standing Across Social Media Platforms

“Class Standing across Social Media Platforms” identifies what each class standing utilizes, as well as what platform, and opens the question of what platforms should be prioritized for further analysis.  

- **Instagram** is the most used application among *Freshmen, Sophomores, and Juniors*.  
- **YouTube** had the highest usage among *Seniors*.  

---

## Topics Explored on Social Media

“Topics Explored on Social Media” showcases the distribution of BDD scores across different entertainment sources explored on social media, indexed by age group.  

- **Ages 18–20:** Higher shift of scores in the *Technology/Smartphone* section.  
- **Ages 25+:** Higher distribution in the topic of *Celebrities*.  

---

## Average BDD Score Based on Hours Spent on Social Media Daily

This graph shows the average BDD score of participants based on time spent on social media daily:  

- **< 3 hours/day:** Baseline.  
- **3–10 hours/day:** Only a 0.1 difference compared to < 3 hours/day.  
- **10–20 hours/day:** Average BDD score was **10 points higher**, with a **p-value of 0.0437**.  

➡️ The **R² value = 0.03**, meaning that time spent on social media explains only ~3% of variance in BDD scores.  
While helpful, the low level of confidence prevents us from concluding a strong effect.  

---

## KNN Analysis with Social Media Platforms

Using all social media platforms (*TikTok, YouTube, Instagram, Facebook, Snapchat, Pinterest*) as features, the KNN model shows that platform choice does not significantly impact BDD score.  

- **Correct Predictions:** 11 high scores were predicted correctly.  
- **Incorrect Predictions:**  
  - 8 low scores incorrectly predicted as high.  
  - 5 high scores incorrectly predicted as low.  
  - Only 3 low scores correctly predicted.  

➡️ The algorithm tends to **overdiagnose high BDD scores**.  

---

## KNN Analysis with BDD Questionnaire Questions

Using the BDD questionnaire questions as features, the KNN model performed much better.  

- **High Scores:**  
  - 15 actual high scores correctly predicted.  
  - Only 1 high score incorrectly predicted as low.  
- **Low Scores:**  
  - 8 correctly predicted.  
  - 3 incorrectly predicted as high.  

➡️ While some overdiagnosis still occurs, this model **more accurately captures BDD scores**.  

---
