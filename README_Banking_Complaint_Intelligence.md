# Banking Complaint Intelligence Platform
### Microsoft Fabric + PySpark + SQL + Power BI + RAG AI

## Overview

This project is an end-to-end Data Engineering and AI solution built using Microsoft Fabric. It processes CFPB banking complaint data using Medallion Architecture (Bronze, Silver, Gold), Power BI dashboards, and a RAG-based AI assistant.

## Business Problem

Banks receive thousands of customer complaints every month. This platform helps analyze complaint trends, monitor performance, and answer questions from complaint narratives using AI.

## Architecture

CFPB Data -> Fabric Pipeline -> Bronze -> Silver -> Gold -> Power BI / RAG Assistant

## Technology Stack

- Microsoft Fabric
- OneLake Lakehouse
- PySpark
- SQL Analytics Endpoint
- Power BI
- Delta Lake
- Azure OpenAI / Gemini
- GitHub

## Medallion Architecture

### Bronze
Raw complaint data.

### Silver
Cleaned, validated, deduplicated data.

### Gold
Business KPIs and RAG-ready datasets.

## Features

- Delta Lake Processing
- Incremental MERGE Loads
- Data Quality Checks
- Power BI Dashboards
- RAG Assistant with Citations
- SQL Analytics

## Repository Structure

```text
fabric-bank-complaints-rag/
├── README.md
├── notebooks/
├── sql/
├── docs/
└── demo/
```

## Author

Your Name
