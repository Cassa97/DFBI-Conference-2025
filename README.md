# DFBI-Conference-2025
Case Study for the DFBI Conference
SPARQL Queries for Semantic Analysis of Construction Projects

This repository collects the SPARQL queries developed for the research paper:

**"Semantic Integration of Cost, Time, Resource, and Geometry for Data-Driven Construction Management: An Interactive Dashboard for Decision Support"**

These queries support consistency checking and cross-domain analysis of construction project data modeled in RDF, using ontologies and Linked Data technologies. The approach enables integration between scheduling, costing, resource planning, and BIM-based geometries.

---

## 🔍 Query Index

| Query | Purpose | Link |
|-------|---------|------|
| Q1 | List of Resources Linked to Task | [View Q1](queries/Q1.sparql) |
| Q2 | List of Cost Items Linked to Tasks | [View Q2](queries/Q2.sparql) |
| Q3 | List of Cost Items Linked to Tasks | [View Q3](queries/Q3.sparql) |
| Q4 | List of Resources Linked to Cost Item | [View Q4](queries/Q4.sparql) |
| Q5 | List of Geometries Linked to Cost Item | [View Q5](queries/Q5.sparql) |

> All queries are designed to work with a unified RDF knowledge graph structured through domain-specific ontologies such as `cr:`, `ci:`, `dtc:`, and `ifc:`.

---

## 🧩 Technologies Used

- **RDF (Resource Description Framework)**
- **SPARQL** for querying semantic graphs
- **OWL Ontologies** for construction domains:
  - `cr:` Construction Resources
  - `ci:` Cost Items
  - `dtc:` Digital Twin Construction
  - `ifc:` IFC OWL for BIM geometries

---

## 📊 Dashboard Integration

The results of these queries are visualized in a Power BI interactive dashboard to support:
- Real-time project monitoring
- Cross-domain data comparison
- Detection of inconsistencies across cost, time, and geometry
