# Natural Language Inference in Bahasa Indonesia
Final project of Natural Language Processing course, June-July 2020.

Team Member:
- Muhamad Abdurahman
- Muhamad Achir Suci Ramadhan
- Sage Muhammad Abdullan

In this project, we were asked to do a full cycle work of an NLP topic, namely natural language inference (a.k.a. textual entailment) on texts in Bahasa Indonesia. The training sets consists of ~6000 rows of premise, hypothesis, and label (entailment, contradiction, or neutral) that is generated via outsourcing from the students of this course.

After the outsourcing part, we were asked to create a model that classify each pair premise-hypothesis to a corresponding label. We were using two approaches to do this: (1) Machine Learning Model using extensive feature extraction, (2) Neural Network + Embedding Layer (TF Embedding and Word2Vec). However, I only share our neural network approaches in this repository.

Our neural network is explained by the diagram below:

![](nn-illustration.png)

However, the result is very poor compared to the first approach using extensive feature extraction. Seems like we were using to many layers that make the result overfitted.