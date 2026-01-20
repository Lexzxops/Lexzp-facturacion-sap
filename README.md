# Lexzp-facturacion-sap
This project is a template for building a conversational enterprise chatbot that retrieves real financial data directly from SAP HANA and presents it in a clear, human-readable format.

The current implementation focuses on billing and sales analytics, allowing users to query information such as top customers, yearly comparisons, and historical performance using natural language.

⚙️ How it works

User submits a natural language query

An AI orchestration layer detects the business intent

Python scripts are executed remotely to query SAP HANA

Data is processed and returned as a structured, readable response

The system is designed to avoid manual reports and technical database queries, enabling business users to interact directly with company data.

🧩 Architecture & Scalability

Although the initial phase is focused on billing, the architecture is modular and ready to scale into additional domains such as:

Treasury

Projects

Inventory / Stock

Other enterprise data sources

Each domain can be added as an independent module while keeping a single conversational interface.

🚀 Project Status

✅ Billing module implemented

🛠️ Additional modules in progress

📦 Repository shared as a reusable template

This repository is intended as a starting point for enterprise chatbot projects that require real-time access to structured business data.
