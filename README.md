# Polygon.io Data Ingestion Pipeline

Efficient ingestion pipeline for historical Polygon.io market data, including CSV parsing, Parquet conversion, and optional data lake storage.

This repository contains a high-performance, modular pipeline for ingesting historical market data from [Polygon.io](https://polygon.io/). It is designed to process flat file dumps (e.g., `2023-06-05.csv.gz`), convert them into analysis-friendly formats like Parquet, and store them in a structured data lake.

## 📦 Features

- 🗃️ Batch ingestion of compressed CSV files
- 🧱 Conversion to columnar Parquet format
- 🧪 Schema enforcement and file validation
- ⚡ Optional multi-threaded processing
- 🪣 Compatible with local and cloud (S3) storage
- 🧩 Modular design for extensibility (e.g., DuckDB, Snowflake, BigQuery)
- 🧭 For use in quantitative research and trading systems

## 📂 Example Directory Structure

