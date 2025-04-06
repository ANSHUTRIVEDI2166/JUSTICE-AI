# ⚖️ Justice-AI

**Justice-AI** is a smart system designed to help prioritize court cases based on severity, urgency, media attention, evidence, and other critical factors — with the goal of improving fairness and efficiency in the legal system.

> "Not all cases are equal — let's solve the ones that matter most first."

---

## 🧠 What It Does

Justice-AI analyzes and ranks court cases by computing a **priority score**, taking into account:

- Case Type (e.g., Rape, Murder, Theft)
- Number of Victims
- Severity & Urgency Levels
- Media Attention
- Evidence Strength
- Case Status (Pending / Under Trial / Closed)
- Date Filed (Oldest cases get more weight)

---

## 📁 Dataset Fields

| Column | Description |
|--------|-------------|
| `case_id` | Unique Case Number |
| `case_type` | Type of Case (e.g., Rape, Murder) |
| `victims_count` | Number of Victims |
| `severity_level` | Low / Medium / High |
| `urgency_level` | Low / Medium / High |
| `public_impact_level` | Low / Medium / High |
| `date_filed` | Case Registration Date |
| `media_attention` | True / False |
| `evidence_available` | True / False |
| `status` | Pending / Under Trial / Closed |
| `region` | Location of Case |
| `priority_score` | (To be calculated) |

---

## 📍 Goal

To assist courts, legal tech startups, and justice-related organizations in **objectively identifying** which cases deserve **immediate attention** based on transparent and logical rules.
