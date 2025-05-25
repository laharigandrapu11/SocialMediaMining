# Language and Support in Online Mental Health Communities

This repository contains the code, data, and documentation for a research project analyzing emotional support dynamics on Reddit’s mental health communities. The study explores how post intent, emotional tone, and user interaction networks influence engagement and support within online peer-driven forums.

## 🧠 Project Overview

Online platforms like Reddit play a vital role in mental health support by offering anonymity and accessibility. This project investigates:
- What types of posts dominate mental health subreddits?
- How emotion and tone correlate with community engagement?
- Who are the most active support providers?
- How is support distributed across users?

The study combines **Natural Language Processing**, **emotion modeling**, and **network analysis** to uncover insights into digital empathy and peer support mechanisms.

## 📊 Dataset

Collected using Reddit’s API via PRAW from 7 mental health-focused subreddits:
- `r/mentalhealth`, `r/depression`, `r/Anxiety`, `r/BPD`, `r/TrueOffMyChest`, `r/KindVoice`, and `r/DecidingToBeBetter`

Final dataset includes:
- 6,921 posts
- 9,885 top-level comments

Posts and comments were filtered for quality (e.g., removed bots, deleted users).

## 🔍 Methodology

The project employs a multi-method framework:
1. **Zero-shot intent classification** using `facebook/bart-large-mnli`  
2. **Emotion detection** using `j-hartmann/emotion-english-distilroberta-base`  
3. **Stylistic analysis** via VADER sentiment scoring and word count metrics  
4. **Network analysis** using NetworkX to identify central support providers  

## 📈 Key Findings

- **Venting** is the most common post type (49%).
- High-arousal emotions (joy, sadness, disgust) lead to more comments/upvotes.
- Posts with positive tone and stylistic clarity receive more thoughtful replies.
- A small subset of users account for the majority of support, indicating emotional labor concentration.


