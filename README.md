# 🏨 Hotel Booking Analytics & Retrieval-Augmented Question Answering (RAG)

This project processes hotel booking data, extracts insights, and enables **Retrieval-Augmented Question Answering (RAG)**. The system provides key analytics and answers user queries using an **LLM-powered API**.

## 📌 Features

- 📊 **Analytics & Insights**: Revenue trends, cancellation rates, lead time distribution, geographical booking distribution.
- 🔍 **RAG-Based Q&A**: Uses **FAISS** and **Sentence Transformers** to retrieve relevant hotel booking information.
- ⚡ **Flask API**: Provides RESTful endpoints for analytics & question answering.
- 🚀 **Deployment Ready**: Can run **locally or on cloud (AWS, GCP, Azure, or Heroku)**.

---

## 📂 Dataset
- The dataset used is **`hotel_bookings.csv`** (from Kaggle or other sources).
- Fields include **hotel name, country, reservation status, room type, lead time, revenue, and more**.

---
## Working
The **Hotel Booking Analytics & Retrieval-Augmented Question Answering (RAG) System** processes hotel booking data to extract key insights and enable natural language querying using an LLM-powered API. The project involves **data preprocessing**, including handling missing values and formatting inconsistencies, followed by **analytics generation** such as revenue trends, cancellation rates, booking lead time distribution, and geographical booking patterns. For question answering, the system uses **FAISS** and **Sentence Transformers** to generate embeddings from booking data, allowing similarity-based retrieval of relevant records. An **LLM-powered Q&A pipeline** then provides natural language responses. The project also includes a **Flask API** with endpoints for retrieving analytics and answering user queries. This API can be deployed locally or on cloud platforms like **AWS, GCP, Azure, or Heroku**, making it a scalable and efficient solution for hotel data analysis and intelligent querying. 🚀

