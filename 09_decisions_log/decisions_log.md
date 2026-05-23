# Decisions Log

## Public Repository Rule

This repository is public. Do not add confidential business data, supplier pricing, private documents, personal data, credentials, or non-public commercial strategy.

Use the correct brand spelling: `TM Barpi`.

## Decision Status Definitions

- Reject: the option is not suitable for this project.
- Research deeper: more public-safe information is needed before deciding.
- Prepare launch: the option is approved for launch preparation.
- Ready for execution: the option is approved for execution.
- Needs data: required inputs are missing.

## Decisions

| Date | Decision | Status | Owner | Rationale | Risk | Next action |
| --- | --- | --- | --- | --- | --- | --- |
| 2026-05-23 | Use GitHub repository as the public-safe project workspace and Codex as the GitHub operator. | Approved | ChatGPT / Codex | The current ChatGPT project chat can read the public repository but cannot write to it directly. Codex has working GitHub write access and can maintain files, commits, and structure. ChatGPT remains the lead strategic agent and final reviewer. | Public repository must not contain confidential business data, supplier pricing, private documents, personal data, credentials, or non-public commercial strategy. | Continue Stage 1 — Product Data Intake for SnEco and TM Barpi. |
| 2026-05-23 | Start with Product Data Intake before listing, PPC, or marketplace selection. | Approved | ChatGPT | SnEco and TM Barpi require separate category, compliance, logistics, and unit economics review before launch priority can be selected. | Starting with listing or PPC too early may create compliance risk, wrong category choice, unsupported claims, or negative unit economics. | Collect public-safe SKU-level data for SnEco 2 SKU and TM Barpi 5 SKU. |
| 2026-05-23 | Limit initial Amazon launch analysis to Europe marketplaces: Spain, Italy, France, and Germany. | Approved | Project owner / ChatGPT | Europe-only scope simplifies initial compliance, logistics, language, FBA, and marketplace comparison work. UK and US require separate regulatory and marketplace logic and should not be mixed into the first launch decision. | Potential opportunities in UK/US or other marketplaces are intentionally excluded from the current phase. | Update category and compliance risk framework only for amazon.es, amazon.it, amazon.fr, and amazon.de. |
| 2026-05-23 | Keep the GitHub repository public at the current project stage and use it as the primary workspace for all necessary Amazon Launch project information. | Approved | Project owner / ChatGPT / Codex | The project owner accepts the visibility risks at this stage in order to let ChatGPT directly read and review repository files, reduce manual copy-paste, and speed up strategic review. Codex remains responsible for writing and committing changes. | Public repository contents may be visible to competitors, suppliers, customers, Amazon, search engines, and AI indexers. Sensitive information may remain discoverable even if the repository is later made private. | Continue Stage 1 — Product Data Intake and enter all necessary product, compliance, marketplace, competitor, and unit economics information into the repository through Codex. |
