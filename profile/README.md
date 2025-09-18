# 👋 Welcome to DataProm s.r.o.

### *Data Engineering & Analytics Platform*  
Building structured, metadata-driven solutions for next-gen data pipelines.

This project is licensed under a proprietary license.

 [![License](https://img.shields.io/badge/license-Proprietary-red)](../../LICENSE.txt)

[![🚀 Build & Publish NuGet Packages](https://github.com/dataprom-online/platform/actions/workflows/publish-nuget.yml/badge.svg)](https://github.com/dataprom-online/platform/actions/workflows/publish-nuget.yml)

---

## 🚀 About Us

**DataProm** is a data engineering platform designed by [DataProm s.r.o.](https://www.dataprom.online), powering robust analytics through:

- ⚙️ Schema-first architecture
- 📦 Modular, configuration-driven ETL
- 🧠 Normalization-aware data pipelines
- 📊 Local + cloud-ready SQLite integrations
- 📁 Metadata-based export & transformation

> We believe data pipelines should be **declarative, traceable, and analytics-ready by design**.

---

---
## 📚 Related Packages
- DataProm.Core - provides the foundation for the DataProm ETL platform.
- DataProm.Sqlite.Core – Native SQLite provider
- DataProm.Sql.Core – Native Sql provider
- DataProm.Oracle.Core – Native Oracle provider
- DataProm.SapHana.Core – Native SapHana provider
- DataProm.GoogleCloud.Core – Native GoogleCloud.BigQuery provider

## 🧩 Key Features
* DynamicRecord System
    - object[] based storage with schema alignment
    - Fast typed accessors (GetInt32, GetString, etc.)
    - Works directly with IDataReader
* Normalization Engine
    - Global per-property string dictionaries
    - Integer key storage in records
    - Automatic SQLite persistence
* Schema-Driven SQL
    - Auto-generate CREATE TABLE, INSERT, INDEX, and foreign keys
    - SQLite and SQL Server support
* CSV Serialization & Validation
    - Import/export with validation rules
    - Separate normalized-property CSVs
* Diagnostics & Logging
    - Crash recovery
    - Startup/shutdown tracking
    - App + project context awareness
---

## 🧪 Try It Yourself

Check out our working demo:

### [🧩 DataProm DemoApp →](https://github.com/dataprom-online/etl-app)

A minimal, real-world example showing:
- 🧵 Full ETL lifecycle (Extract, Transform, Load)
- 📄 Metadata & normalization via config files
- 🐞 Logging, diagnostics & SQLite export

> Built entirely on `.NET`, raw SQL, and simple configuration files.

---

## 🔍 Explore Our Mission

We’re focused on:
- ✨ Simplicity over complexity
- 🧩 Open standards for metadata
- 📊 Direct integration with BI & reporting tools
- 🧱 Reusable data components for scalable growth

---

## 💬 Let’s Connect

🔗 [Website](https://www.dataprom.online)  
🐙 [GitHub](https://github.com/dataprom-online)  
📧 maros.kolibas@dataprom.online

---

© 2025 [DataProm s.r.o.](https://www.dataprom.online) — All rights reserved.
