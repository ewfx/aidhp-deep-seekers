# 🚀 Project Name

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
The main objective of this code is to develop a fashion query response system that utilizes AI models to provide detailed and user-friendly responses to fashion-related queries. The system aims to enhance user experience by generating informative and contextually relevant answers, thereby assisting users in finding fashion items based on their preferences.

## 🎥 Demo
🔗 [Live Demo](#) (if applicable)  
📹 [Video Demo](#) (if applicable)  
🖼️ Screenshots: https://github.com/ewfx/aidhp-deep-seekers/tree/main/artifacts/demo

## 💡 Inspiration
To Enhance user experience by generating informative and contextually relevant search results 

## ⚙️ What It Does
a) Data Preprocessing:
The CSV dataset was formatted to enhance data quality and readability.
Blank entries were replaced, decimal points were standardized, and unnecessary columns were removed.
Text columns were cleaned to remove HTML tags and extra characters.

b) Model Integration:
Advanced AI models like GPT-3.5 were integrated into the system to generate responses to user queries.
Queries were passed through the model to generate detailed and contextually relevant responses.

c)Query Response Generation:
User queries were processed by both the search layer and the generation layer.
The search layer retrieved relevant fashion items from the dataset.
The generation layer utilized AI models to generate detailed responses to user queries, incorporating context and generating natural language responses.

## 🛠️ How We Built It

The Embedding Layer:
The CSV document needs to be effectively processed, cleaned, and prepared for embedding.

The Search Layer:
first need to design at least 3 queries against which you will test your system. Next, you need to embed the queries and search your vector database against each of these queries. Implementing a cache mechanism is also mandatory.

Finally, you need to implement the re-ranking block, and for this you can choose from a range of cross-encoding models on HuggingFace.

The Generation Layer:
In the generation layer, the final prompt that you design is the major component.

By effectively addressing each layer and conducting systematic experiments, the aim is to build a highly functional and efficient fashion search system tailored to meet user needs.

## 🚧 Challenges We Faced
Describe the major technical or non-technical challenges your team encountered.

## 🏃 How to Run
1. Run file [https://github.com/ewfx/aidhp-deep-seekers/blob/main/code/Fashion_Search_AI.ipynb](https://github.com/ewfx/aidhp-deep-seekers/blob/main/code/src/Fashion_Search_AI.ipynb)
   ```

## 🏗️ Tech Stack
- 🔹 Other: OpenAI API / Twilio / Stripe

## 👥 Team
- **Jyothirmayi Kolachalam** | [LinkedIn](https://www.linkedin.com/in/jyothirmayi-kolachalam-653b5117/)
- **Rahul Goyal** | [LinkedIn](https://www.linkedin.com/in/rahul-goyal-6a94b197/)
- **Aniket** | [Linkedin](https://www.linkedin.com/in/aniketaniket/)
