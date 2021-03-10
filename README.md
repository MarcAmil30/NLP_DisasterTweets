# Kaggle - Natural Language Processing with Disaster Tweets
[Kaggle Challenge](https://www.kaggle.com/c/nlp-getting-started/data?select=train.csv)

---
## Notes taken from the dataset 
- id (1 to 10.9k)
- 222 unique values (keyword) out of 7503 unique values (text)
- keyword = word that shows disaster 

---
## Questions and Ideas
- Q:  How does locations affect keywords and how they interact?
  - Maybe subset each location and see which word is more common for each
    location. Stratify for each location 
- Find ways to detect metaphors of keywords --> Metaphors can lead to false
  positives 
- Look at words around they keywords 
- Maybe depending on the emojis it can see if the message is bad or not. e.g. happy emoji does not mean danger (DO THIS LATER):
- Exclamation mark (❗️ ) could indicate danger tweet 
---

