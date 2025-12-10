# BioQuery-Dashboard-Telebu-Python-Biotech
# BioQuery Assistant

A "Python FastAPI backend" that answers biotech drug-related queries by reading from a structured CSV dataset.  
This project is designed to integrate with a "Telebu chatbot" to provide users with quick, accurate drug information.

# Project Objective
To combine:
- Biotech domain knowledge**
- Python backend development**
- Chatbot integration**
into a lightweight, extendable drug-query assistant.

# Dataset
The application uses a CSV dataset with the following schema:
drug_name, category, mechanism, side_effect

# Architecture Overview
GMO data is stored in a structured CSV file.
FastAPI loads and normalizes the dataset at startup.
API endpoints allow querying by GMO name.
Data can be consumed by:
   A dashboard UI (charts, tables, filters)
   A Telebu chatbot for natural-language queries

# Dashboard Use Case
This backend is suitable for powering:
   GMO comparison tables
   Trait-based filters and analytics
   Regulatory or educational dashboards
   Chatbot-assisted GMO Q&A interfaces
A frontend or BI layer can consume the API for visualization.

# Tech Used:
Python
FastAPI
Uvicorn
CSV-based datastore
Telebu chatbot integration


