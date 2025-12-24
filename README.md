# 🤖 Introduction to GitHub Models: Course Assignments

This repository contains the practical assignments and capstone tasks completed for the **"Introduction to GitHub Models"** short course.

The workshop, led by **Nisal Gunawardhana**, focuses on leveraging the GitHub Models marketplace to integrate Large Language Models (LLMs) into applications using Azure AI Inference.

> **Original Course:** [Introduction to GitHub Models](https://github.com/nisalgunawardhana/Introduction-to-Github-models)

## 📂 Project Overview
While the original course material provides examples in Node.js, I have implemented all solutions using **Python** and **Jupyter Notebooks** to align with industry standards for AI/ML engineering.

This project demonstrates:
* **Secure API Management:** Handling credentials using `.env` and environment variables.
* **Model Inference:** interacting with models like `GPT-4o` and `Mistral` via the OpenAI SDK.
* **Prompt Engineering:** Designing system messages for specific outputs.
* **Vector Embeddings:** Generating text embeddings for semantic similarity tasks.

## ✅ Completed Tasks

### 1. Sentiment Analysis
* **Goal:** Build a strict classifier that categorizes text as Positive, Negative, or Neutral.
* **Model Used:** `gpt-4o`
* **Key Learning:** Controlling output determinism using strict system prompts and low temperature settings.

### 2. Code Generation
* **Goal:** Create an AI-powered coding assistant to solve programming problems (e.g., string reversal).
* **Model Used:** `Mistral-small` / `Llama-3`
* **Key Learning:** Using open-weight models for specialized technical tasks.

### 3. Vector Embeddings
* **Goal:** Convert text strings into vector representations to understand semantic meaning.
* **Model Used:** `text-embedding-3-small`
* **Key Learning:** Understanding how LLMs perceive text numerically for search and comparison.

---
*Mentored by Nisal Gunawardhana.*
