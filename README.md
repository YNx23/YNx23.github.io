# 🌍 Climate, GIS & Disaster Risk Resource Hub

This repository hosts **https://ynx23.github.io**, a public knowledge hub built with **Just-the-Docs**.  
It curates high-quality resources across **climate science**, **GIS & remote sensing**, **disaster risk management**, and **sustainability**.

The site is designed as a lightweight, searchable reference for students, researchers, and practitioners working in environmental and resilience fields.

---

## 📁 Repository Structure

index.md               → Landing page
_config.yml            → Site configuration

_climate/              → Climate datasets, portals, reports
_gis/                  → GIS & remote sensing tools and tutorials
_drm/                  → Disaster risk management frameworks and alerts
_sustainability/       → Sustainability & environmental governance resources

assets/js/             → Custom scripts (e.g., table filtering)



Each collection contains a single Markdown page with a **filterable resource table**, keeping the site clean and easy to maintain.

---

## 🔎 Search & Filtering

The site supports two levels of filtering:

### **1. Site-wide search (Just-the-Docs built-in)**
Use the search bar (top right) to find resources by keyword  
(e.g., *dataset*, *GIS*, *IPCC*, *risk*, *satellite*, *tutorial*).

### **2. In-page table filtering**
Each category page includes a small JavaScript filter that allows instant row filtering within the table.

The script is loaded via:


and configured in `_config.yml` under:

```yaml
just_the_docs:
  aux_scripts:
    - assets/js/filter-table.js
