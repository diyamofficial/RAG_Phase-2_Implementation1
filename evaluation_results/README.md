# Evaluation Results

This folder contains the evaluation outputs for the Retrieval-Augmented Generation (RAG) system using RAGAS metrics.

## Contents

- **baseline_ragas_results.csv** – RAGAS evaluation results for the baseline vector-only retrieval system.
- **hybrid_ragas_results.csv** – RAGAS evaluation results for the hybrid retrieval system (Vector Search + BM25).
- **ragas_comparison_barplot.png** – Bar chart comparing the average RAGAS metrics of the baseline and hybrid retrieval systems.
- **comparison_table.png** – Tabular comparison of the average RAGAS evaluation metrics.

## Evaluation Metrics

The systems were evaluated using the following RAGAS metrics:
- Faithfulness
- Answer Relevancy
- Context Precision
- Context Recall

## Summary

The comparison provides a quantitative evaluation of the baseline and hybrid retrieval approaches using the same set of evaluation questions and RAGAS metrics.
