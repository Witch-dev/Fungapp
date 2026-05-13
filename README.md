# Fungapp

## Overview

An educational mushroom identification tool designed to help users understand how fungi are classified in the real world.

Instead of attempting to give a single definitive answer, the application guides users through a structured set of questions about observable traits and environment, gradually narrowing down the possible species.

The goal is not perfect identification, but a clear understanding of uncertainty and biological classification logic.

---

## Core Concept

Mushroom identification in nature is complex and often cannot be done with certainty without laboratory analysis or expert evaluation.

The system is designed around this principle:

> “You don’t find the exact mushroom — you narrow down what it could possibly be.”

As the user provides information, the system reduces the set of possible species step by step and shows how the uncertainty decreases.

---

## How It Works

The system behaves like a guided decision process:

- The user starts by describing or uploading a mushroom observation
- The application asks structured questions such as:
  - Cap shape and color
  - Gills, pores, or other structures
  - Spore characteristics (if known)
  - Habitat (soil, wood, specific trees, etc.)
  - Bruising or color changes

Each answer filters the possible species set.

The system continuously updates:

- Most likely families or genera  
- Remaining possible species count  
- Missing information needed for better accuracy  

Instead of returning a single species, the app shows:

- Most likely families / genera  
- Estimated number of possible species remaining  
- Key traits influencing the result  
- Missing data that would improve accuracy  
- Educational explanations of each trait  

---

## Educational Focus

The app is designed to teach:

- Basic mycology terminology (cap, gills, stipe, spores, etc.)
- Ecological relationships (tree associations, substrate types)
- How classification narrowing works in biology
- Why species-level identification is often uncertain without lab analysis

---

## Planned Features

- Interactive question-based narrowing system  
- Mushroom trait database (structured taxonomy)  
- Probability-based filtering engine  
- Habitat and ecological context system  
- Visual comparisons of similar species  
- Explanation of narrowing decisions  

---

## Tech Stack (Planned)

- **Frontend:** .NET Blazor or React (TBD)  
- **Backend:** ASP.NET Core (.NET 8)  
- **Database:** SQL Server / PostgreSQL  
- **Cloud:** Azure (App Service, Database, Storage)  

---

## Philosophy

This project focuses on learning over certainty, helping users understand that classification in biology is often probabilistic rather than absolute.

## ERD
<img width="851" height="250" alt="image" src="https://github.com/user-attachments/assets/7a94b48e-c4b3-4738-bcff-f22bf5390280" />



