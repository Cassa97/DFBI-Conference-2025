# DFBI-Conference-2025
Case Study for the DFBI Conference
SPARQL Queries for Semantic Analysis of Construction Projects

This repository collects the SPARQL queries developed for the research paper:

**"Semantic Integration of Cost, Time, Resources, and Geometry for Data-Driven Decision-Making in Construction Projects"**

These queries support consistency checking and cross-domain analysis of construction project data modeled in RDF, using ontologies and Linked Data technologies. The approach enables integration between scheduling, costing, resource planning, and BIM-based geometries.

---

## 🔍 Query Index

| Query | Purpose | Link |
|-------|---------|------|
| Q1 | List of resources linked to tasks (with type) | [View Q2](queries/Q2.sparql) |
| Q2 | List of geometries linked to tasks (with GlobalId) | [View Q4](queries/Q4.sparql) |
| Q3 | Cost items associated with each task | [View Q6](queries/Q6.sparql) |
| Q4 | Resources linked to cost items (with type) | [View Q8](queries/Q8.sparql) |
| Q5 | Geometries linked to cost items (with GlobalId) | [View Q10](queries/Q10.sparql) |

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
