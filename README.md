# Awesome-Construction-Quality-Management

## Top Construction Quality Management Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Inspection & Test Plans, Punch Lists, Non-Conformance Reports & Field Quality Control*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Construction Quality Management**. These tools help general contractors, quality managers, and site inspectors digitize inspections, manage punch lists, track non-conformance reports (NCRs), and maintain audit-ready quality documentation.



**Examples** include Autodesk Build, Procore Quality, Fieldwire, BIM 360 Build, HammerTech, Inspectivity, SiteMax, FlowForma, SnagR, and Finalcad (the category leaders).



**Open-source emphasis**: Construction quality management has a **developing open-source ecosystem**. **OpenConstructionERP** provides a comprehensive free platform with built-in **Inspection & Test Plan (ITP)** modules featuring hold and witness points, signed inspection records, and quality trail filing . **agent-quality-oss** delivers an AI-powered MCP server that supplies ITP and NCR form structures with Korean construction standards ontology . **OpenAEC BIM Validator** provides browser-based IFC validation against IDS specifications . **ITC СтройКонтроль** offers a full-stack construction control journal with daily checklists and quality review workflows .



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Autodesk Build](https://construction.autodesk.com/)**  

  Construction management platform with quality management modules. Provides inspection forms, issue tracking, and punch list capture with **model-linked inspection records** that connect directly to Revit elements for commissioning documentation . Document control supports ISO 19650-style BIM standards .



- **[Procore Quality](https://www.procore.com/)**  

  Quality and safety module within Procore's construction platform. Provides **field inspection forms and punch-list capture** with faster field deployment than Autodesk Build, though model traceability requires manual cross-referencing . Integrated cost management covering commitments and change orders .



- **[Fieldwire](https://www.fieldwire.com/)**  

  Field management platform optimized for construction teams. Provides **task tracking, photo documentation, and plan markups**. Limited to essential field workflows — does not include budget control, contract management, or formal technical process tracking .



- **[BIM 360 Build](https://www.autodesk.com/)**  

  Autodesk's legacy construction management platform (superseded by Autodesk Build). Provides quality and safety checklists, issue management, and document control.



- **[HammerTech](https://www.hammertech.com/)**  

  Safety and quality intelligence platform for construction. Provides inspections, ITPs, NCRs, and quality workflows with deep Procore integration.



- **[Inspectivity](https://www.inspectivity.com/)**  

  Inspection and ITP management platform. Provides digital checklists, hold point tracking, and quality documentation.



- **[SiteMax](https://sitemaxsystems.com/)**  

  Construction field management platform. Provides daily logs, safety inspections, and quality checklists.



- **[FlowForma](https://www.flowforma.com/)**  

  No-code workflow automation platform with construction quality process templates.



- **[SnagR](https://snagr.com/)**  

  Snagging and punch list management platform for construction. Provides defect tracking, photo documentation, and closeout workflows.



- **[Finalcad](https://www.finalcad.com/)**  

  Construction quality and safety platform. Provides inspections, punch lists, and analytics for field teams.



## Open-Source GitHub Projects



### Inspection & Test Plan Management



- **[OpenConstructionERP](https://github.com/datadrivenconstruction/OpenConstructionERP)**  

  **The most comprehensive open-source construction quality platform.** **AGPL-3.0 licensed**, free and open-source ERP with **192 modules** including quality, safety, RFI, tasks, and CDE . **Inspection & Test Plan (ITP) module** provides step-by-step quality workflow: **Build ITP** (define checks, acceptance criteria, specification clauses, hold and witness points before work starts), **Inspect at each point** (raise inspection at each ITP hold point, sign as passed or fail and hold next operation), **File signed records** (gather signed inspections, test certificates, and concessions into a continuous quality trail) . Zero-config install via `pip install openconstructionerp` with embedded database .



- **[agent-quality-oss](https://www.npmjs.com/package/agent-quality-oss)**  

  **Open-source MCP server for Korean construction quality management.** Developed by Hwangryong Construction Co., Ltd. and Ratelworks Inc. . Provides **ITP, NCR, inspection request, and test report form structures** with quantitative criteria, decision trees, and legal citation locations . **Ontology**: 19 work types, 382 graph nodes, 934 relationships connecting work type → material → test → criteria → risk → non-conformance → corrective action → evidence → standard . LLM supplies form structure and criteria; final judgment and signature remain human responsibility .



- **[ITC СтройКонтроль](https://github.com/storkych/ccj-frontend)**  

  **Full-stack construction quality control system (Russian-language).** Provides **daily checklists** for foremen (safety checklists, supply acceptance, work planning, QR code scanning), **review workflows** for construction control service (checklist verification and approval, supply control, violation management, visit planning), and **AI functions** (smart chat assistant, object analysis, computer vision for document recognition) . Tech stack includes API endpoints for building control, AI, computer vision, notifications, QR/visits, tickets, and files .



### BIM Model Quality & Validation



- **[OpenAEC BIM Validator](https://github.com/OpenAEC-Foundation/OpenAEC-BIM-validator)**  

  **Browser-based IFC validation tool for construction quality.** Upload an IFC model, validate against **IDS specifications** (NL-BIM, RVB), view results in 3D, and export BCF issues . Supports **IFC2X3 and IFC4**. Includes checks for correct IFC entities, NL-SfB classification (doors, windows, columns, beams, stairs), **constructive and fire-technical properties** (material assignment, IsExternal, FireRating, SelfClosing, FireExit, LoadBearing), and model quality (avoid IfcBuildingElementProxy) . Based on RVB BIM Norm v1.1 .



- **[concrete-structures-code-checking](https://github.com/jefalvesf/concrete-structures-code-checking)**  

  **Open-source automation for automated compliance checking in reinforced concrete structures.** Master's thesis from CEFET-MG, Brazil . Verifies **NBR 6118:2023 normative requirements** in BIM models of reinforced concrete structures. Built with **Python and IfcOpenShell** library .



- **[bim-ifc-audit-bot](https://github.com/walqed/bim-ifc-audit-bot)**  

  **Telegram bot for automated IFC model auditing.** Provides **normative control, geometric collision detection, and Excel reporting** with optional AI question-answering about the model . Supports **IFC2X3, IFC4, and IFC4X3**. Checks model structure, attributes, and dimensional values; normalizes project units to SI; performs exact triangulated body intersection checks via IfcOpenShell; and generates Excel reports with formula injection protection . AI mode is off by default — audit runs fully locally .



### Additional Strong Open-Source Options



- **Full Quality ERP**: **OpenConstructionERP** (192 modules, ITP workflow, hold/witness points) .

- **AI Quality Assistant**: **agent-quality-oss** (MCP server, Korean standards ontology, ITP/NCR forms) .

- **Quality Control System**: **ITC СтройКонтроль** (daily checklists, review workflows, AI functions) .

- **BIM Validation**: **OpenAEC BIM Validator** (IDS specifications, 3D view, BCF export) , **concrete-structures-code-checking** (NBR 6118 compliance) , **bim-ifc-audit-bot** (collision detection, Excel reports) .



**Frameworks for building custom systems**: Combine **OpenConstructionERP** for the core quality management workflow with ITP hold/witness points, **agent-quality-oss** for AI-powered form structure and criteria supply, **OpenAEC BIM Validator** for model-based quality checks, and **ITC СтройКонтроль** for daily field checklists. Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Construction quality management platforms handle sensitive project and compliance data; ensure compliance with building codes and contractual quality requirements.

- **Open-source reality**: The open-source ecosystem for construction quality management is **developing but not yet equivalent to commercial platforms**. **OpenConstructionERP** provides a production-ready ITP workflow with hold/witness points and signed quality trails . **agent-quality-oss** delivers AI-powered ITP/NCR form structures grounded in Korean construction standards . **OpenAEC BIM Validator** and related tools provide model-based quality validation . However, **commercial platforms** (Procore, Autodesk Build, HammerTech) provide **deeper field adoption, model-linked inspections at scale, and enterprise integrations** that open-source alternatives require significant configuration and training to match. The open-source path is most viable for **BIM-centric quality workflows, ITP management**, or **organizations with strong technical capacity**.



---



**Made for quality managers, site inspectors, construction technologists, and field engineers.**

Let's make construction quality management more open, transparent, and verifiable.
