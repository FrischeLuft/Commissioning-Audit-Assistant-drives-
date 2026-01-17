drive-commissioning-audit-assistant

What it does
Commissioning and audit assistant for drives: compares parameter baseline vs after and generates a structured report. Intended for commissioning evidence, audits, and repeatable handovers. “n8n-ready” for automation pipelines.

Typical use cases

* Parameter baseline capture and “after commissioning” comparison

* Evidence report for acceptance / QA / service handover

* Automated packaging of commissioning documentation

Core features (demo scope)

* Input: two parameter exports (baseline / after) in CSV format (synthetic demo data)

* Output: diff report (what changed, categorized by importance)

* Optional: workflow step to generate and deliver a report (email/ticket/archive)

Architecture (high level)

* Param diff tool (CLI/service)

* Report generator (Markdown/HTML, extendable to PDF)

* n8n workflow integration points (trigger → diff → report → deliver)

Deliverables (for a client pilot)

* Parameter diff rules and report template

* Automated reporting workflow (n8n)

* Storage/archiving approach for evidence

* Documentation + commissioning checklist suggestions

Safety / limitations

* Demo uses synthetic data and generic CSV format.

* No sensitive customer/plant information included.

Contact
Freelance / pilot projects: Industrial Automation + AI + n8n workflows
(Email: igor.pokhotelov@outlook.de)
