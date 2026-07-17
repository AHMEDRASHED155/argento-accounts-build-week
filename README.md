# argento-accounts-build-week
Offline-first Arabic accounting app for workshops, built with Codex during OpenAI Build Week.
# Argento Accounts

**Argento Accounts** is an offline-first Arabic accounting application created for a real laser-cutting and engraving workshop in Sana'a, Yemen.

The project started as a practical tool for managing daily workshop accounting: transactions, customers, balances, payments, reports, exports, and backups. It includes a desktop app and an Android companion app, with Arabic RTL support and local-first data handling.

## Built for OpenAI Build Week

This submission shows how Codex and OpenAI models helped improve an existing real-world project through focused planning, architecture review, data-safety work, testing, Android backup/restore flows, and the design of a new optional AI-assisted feature called **Argento Insight**.

## What it does

- Records workshop transactions.
- Tracks customers, payments, and balances.
- Generates Arabic reports.
- Supports local-first accounting workflows.
- Provides Android backup and restore.
- Uses deterministic local accounting logic.
- Keeps AI assistance read-only and advisory.
- Supports Arabic RTL interfaces.

## Platforms

### Desktop

The desktop version is built with:

- Python
- PySide6
- Qt Widgets
- SQLite
- pandas
- openpyxl
- ReportLab
- pytest

### Android

The Android version is built with:

- Kotlin
- Android SDK
- Room
- JUnit
- JSON
- SHA-256

## Argento Insight

**Argento Insight** is an optional AI-assisted financial review concept for the project.

It is designed to:

- summarize monthly performance;
- highlight unusual transactions;
- identify balances that may need follow-up;
- provide Arabic financial review notes;
- remain read-only and advisory.

Argento Insight does not modify transactions, balances, payments, or accounting records.

## Privacy and data safety

This public repository does not include:

- real customer data;
- production databases;
- passwords;
- signing keys;
- keystore files;
- private local configuration;
- workshop financial records.

All screenshots and demo materials use sample data only.

## Gallery

The Devpost gallery includes:

1. Desktop and Android overview with project branding.
2. Dashboard with demo data.
3. Operations, customers, and balances.
4. Backup and restore workflow.
5. Argento Insight prototype / new feature screen.

## Project status

This is a real project under active development. The Build Week submission focuses on the product story, architecture, Android readiness work, backup/restore safety, and the Argento Insight direction.

The public materials are sanitized for demonstration and do not expose private workshop data.

## Technologies

Python, PySide6, Qt Widgets, SQLite, Kotlin, Android, Room, OpenAI Codex, pandas, openpyxl, ReportLab, pytest, JUnit, JSON, SHA-256, Arabic RTL.

## Author

Built solo by Ahmed Ali, founder of Argento.
