# 🍅 Automated Agro-Sorting: AI for Tomato Quality Control

## 📖 The Project in a Nutshell

In the agricultural industry, manually sorting produce is time-consuming, expensive, and prone to human error. This project explores how **Computer Vision** — teaching computers to "see" and understand images — can automate this process.

Specifically, this project trained **Artificial Intelligence** to look at pictures of tomatoes and sort them based on their quality, accounting for real-world challenges such as:

- Poor lighting
- Hidden angles and occlusion
- Irregular tomato shapes
- Visual inconsistencies in real-world datasets

---

## 🎯 The Goal

The goal of this project was to determine which AI model is better equipped for real-world agricultural sorting by testing two powerful image-recognition models side by side.

---

## 🧠 The Contenders

A dataset of approximately **1,000 diverse tomato images** was used to train and evaluate two pre-built AI models.

### InceptionV3

Known for being highly efficient and for analyzing images from multiple perspectives at once.

### ResNet50

Known for its deep architecture, allowing it to understand highly complex visual patterns.

---

## 🏆 The Results: Which AI Won?

To determine the winner, we used the **F1 Score**, a metric that measures not only how many predictions the model got right, but also how well it balanced correctly identifying good tomatoes without accidentally passing bad ones.

| AI Model | Final Score (F1) | Verdict |
|---|---:|---|
| 🥇 InceptionV3 | 93% | **The Winner.** Highly reliable and accurate. It handled real-world variations such as shadows, unusual shapes, and inconsistent image conditions very well. |
| 🥈 ResNet50 | 83% | **The Runner-Up.** A strong model, but it struggled more with visual inconsistencies in the dataset compared to InceptionV3. |

---

## ✅ Conclusion

**InceptionV3 is the clear choice for this automated agro-sorting task.**

Its higher F1 Score shows that it was more reliable, more accurate, and better suited for handling real-world tomato quality-control challenges.

---

## 📁 What's in this Repository?

This repository contains two main notebook files, each representing the code used to train and evaluate one of the models.

| File | Description |
|---|---|
| `InceptionV3_Agrosort.ipynb` | Complete code, training process, and testing for the winning InceptionV3 model. |
| `ResNet50_Agrosort.ipynb` | Complete code, training process, and testing for the ResNet50 model. |

---

## 🚀 Project Summary

This project demonstrates how AI-powered computer vision can support automated agricultural sorting systems, reducing manual labor and improving consistency in tomato quality control.
