# COOKAI: Transforming Ingredients into Recipes

**COOKAI** is a smart, AI-powered recipe retrieval system designed to simplify cooking. By entering a recipe name, users receive a detailed list of ingredients and preparation steps — eliminating the confusion of scattered online recipes.

---

## Problem Statement

Finding reliable recipes online is often overwhelming due to inconsistent formats, confusing instructions, or irrelevant search results. COOKAI aims to resolve this by delivering:

- A precise list of ingredients  
- Step-by-step cooking procedures  
- Consistency and reliability in recipe details  

---

## Project Objectives

- Build a searchable system that returns complete recipe details based on user input (recipe name)
- Structure and clean recipe data for accurate retrieval
- Provide clear cooking instructions to users with minimal effort
- Lay groundwork for future personalization and dietary filters

---

## Dataset

- **Source**: Manually collected from Kaggle and recipe websites  
- **Size**: 80 recipes  
- **Fields**:
  - `Name`: Name of the recipe
  - `Ingredients`: Required items
  - `Procedure`: Step-by-step method
  - `Serving`: Portion or context of usage

---

## Data Preprocessing

- Removal of duplicates
- Filling missing values using imputation
- Cleaning and standardizing text (ingredients, procedure)
- Structured formatting for easy data retrieval

---

## Model Development

While the core system is rule-based, the project explores models for future recommendation capabilities, including:

- Collaborative filtering
- Content-based filtering
- Natural Language Processing (NLP) for intent understanding

---

## Evaluation

The system was manually validated by checking outputs for recipe queries. Future enhancements may include:

- Ingredient-based search
- Nutrition-based filtering
- Visual recognition (e.g., from images)

---

## Project Structure

```bash
COOKAI/
│
├── INDIAN FOOD RECIPE.csv         # Dataset (80 recipes)
├── Mini Project Report.docx       # Full documentation
├── cookai_recipe_retriever.ipynb  # (If implemented in code form)
└── README.md                      # You are here
