# Technical Lead – Data Annotation: Proctored Case Study & Operational Audit

## Introduction

This Jupyter notebook provides a rigorous, data-driven operational audit and diagnostic case study for a **Technical Lead – Data Annotation / QA Manager** position. It analyzes team performance dynamics, workforce retention, and quality degradation across multi-stage annotation workflows. The evaluation bridges quantitative labeler metrics with real-world quality incident root causes to formulate actionable remediation plans, queue prioritization strategies, and stakeholder risk communications.

---

## README & Repository Guide

### 1. Prerequisites & Dependencies

To run this notebook successfully, ensure the following Python libraries are installed in your environment:

```bash
pip install pandas numpy matplotlib seaborn openpyxl

```

### 2. Dataset Requirements

This notebook expects the companion spreadsheet **`Lead Case Study Metrics.xlsx`** to be located in the same directory. The workbook contains two primary sheets:

* **`Part 1 - Labeler Metrics`**: Individual performance profiles, onboarding scores, task complexity, completion times, error rates, and 6-month retention data for 32 anonymized labelers (`L001` to `L032`).
* **`Part 2 - Quality Incident`**: Weekly project progression snapshots, Week 3 QA failure distributions, segment-level breakdowns (tenured vs. new labelers and task domains), and QA reviewer agreement scores.

### 3. Notebook Structure

* **Section 1: Labeler Metrics & Operational Health Audit (Part 1)** — Exploratory data analysis examining correlations between task completion speed, onboarding scores, error rates, and 6-month retention.
* **Section 2: Quality Incident Root Cause Diagnosis & Segmentation (Part 2)** — Analysis of the Week 3 quality decline (pass rate drop from $94\%$ to $81\%$, rework surge to $19\%$) and cohort/domain segmentation.
* **Section 3: Strategic Recommendations & 5-Day Stabilization Plan** — Actionable remediation framework including quarantine/partial shipping, gated onboarding sandboxes, and guideline change management.
