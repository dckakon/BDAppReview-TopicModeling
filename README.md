# BDAppReview-TopicModeling

Welcome to the official repository for **BD-AppReviews**, a dataset of user-generated reviews collected from 50 popular Bangladeshi Android applications. 

## 📌 Overview

User reviews provide valuable insights into application performance, usability, and feature request. 



## 📂 Dataset Description
- The **BD-AppReviews dataset** (3.9M+ reviews)
The dataset is structured as a CSV file with the following columns:

| Field Name             | Description                                                        |
|------------------------|--------------------------------------------------------------------|
| `reviewId`             | Unique identifier for the review                                  |
| `userName`             | Anonymized name of the reviewer                                   |
| `userImage`            | URL to the reviewer’s profile image (if available)                |
| `content`              | The full review text                                               |
| `score`                | App rating provided (1 to 5)                                       |
| `thumbsUpCount`        | Number of thumbs-up (helpful votes) the review received           |
| `reviewCreatedVersion`| App version during which the review was posted                    |
| `at`                   | Timestamp of when the review was written                          |
| `replyContent`         | Developer's reply to the review (if any)                          |
| `repliedAt`            | Timestamp of the developer's reply                                |

📌 **Total Records:** 3.9 million+  
📌 **Apps Covered:** 50 top apps in Bangladesh (e.g., bKash, Pathao, Foodpanda, Daraz, MyGP, etc.)

## 🧪 Applications

- Topic Modeling ( BERTopic, Top2Vec)
- Sentiment Analysis
- Bug report summary generation
- Feature Request Extraction
- Software Maintenance Insights
- NLP for Low-Resource Languages 


