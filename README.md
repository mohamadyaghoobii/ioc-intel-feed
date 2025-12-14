
# 🧪 Unified IOC Feeds — *ioc‑intel‑feed*
> **Continuously updated Threat Intelligence datasets** 🕷️

---

## 🧠 Purpose
This repository contains **generated IOC outputs** from the main platform:
👉 `Ioc‑intel`

It is designed to:
- Be **machine‑consumable**
- Be **versioned**
- Be **auto‑updated**
- Act as a **single source of truth** for SIEM / SOC tools

---

## 📦 Contents

```
feeds/
 ├── unified_ioc.json
 ├── unified_ioc.csv
 └── meta.json
```

### 📄 unified_ioc.json
Best for:
- SIEM ingestion
- APIs
- Splunk KV Store
- Detection pipelines

Each IOC includes:
- Value
- Type
- Score
- Severity
- Category
- Confidence
- Source
- Tags
- Timestamps

---

### 📊 unified_ioc.csv
Best for:
- Splunk lookups
- Excel / BI tools
- Lightweight ingestion

---

### 🧾 meta.json
Build metadata:
- Feed generation time
- IOC count
- Source health

---

## 🔄 Update Model
- Feeds generated every **30 minutes**
- Auto‑committed only if data changes
- No duplicate commits
- Atomic updates (safe for consumers)

---

## 🔐 Trust Model
- Sources are **well‑known OSINT providers**
- Data normalized & scored before release
- No raw dumps — only curated output

---

## 🎯 Use Cases
- SOC threat enrichment
- Correlation rules
- Detection engineering
- Threat hunting
- Lab & research

---

## ☠️ Philosophy
This repo is **output only**.
No logic.
No secrets.
No noise.

Just clean intelligence 🕶️

---

> 🕸️ *Consume it. Correlate it. Hunt with it.*
