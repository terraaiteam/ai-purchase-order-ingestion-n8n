# ai-purchase-order-ingestion-n8n
# AI Purchase Order Ingestion (n8n)

## Overview
End-to-end automation that processes purchase order PDFs and converts them into structured, SAP-ready data using AI and semantic search.

## Business Problem
Manual processing of purchase orders is slow, error-prone, and does not scale.
Orders arrive as unstructured PDFs and require human interpretation.

## Solution
This automation:
- Listens for new purchase order PDFs
- Extracts text from files
- Uses LLMs to parse structured order data
- Matches products using vector similarity search
- Outputs clean, structured data ready for SAP ingestion

## Tech Stack
- n8n
- OpenAI (LLMs + embeddings)
- Vector database (Supabase)
- SAP Business One (integration-ready)

## Key Features
- Hebrew purchase order parsing
- Internal SKU extraction
- Semantic product matching
- JSON-safe outputs
- Modular and scalable design

## Repository Contents
- `workflow.json` – n8n workflow export (credentials removed)
- `README.md` – project documentation

## Notes
This repository is intended as a portfolio project.
Credentials and sensitive data are not included.
