# ✅ Definition of Done (DoD) – Amazon CMT & Kindle Project (Sample)  

This Definition of Done reflects how quality and completion were ensured during my work on **Catalog Mapping (CMT)** and **Kindle migration** projects.  
It is a generic, shareable version (no confidential data).  

---

## 🎯 Purpose  
To establish a consistent understanding of “done” across catalog automation and content migration teams.  
Ensures backlog items are delivered with high accuracy, tested, and ready for downstream systems without rework.  

---

## 🛠️ General DoD Criteria (Stories / Tasks)  
- [ ] Business rules/requirements validated with Product Owner.  
- [ ] Test data prepared and verified against sample catalog/ISBN records.  
- [ ] Code/config changes reviewed (peer review or automation rule validation).  
- [ ] Automated tests executed for mapping accuracy (e.g., ISBN → ASIN mapping).  
- [ ] Zero **critical/high-severity defects** outstanding.  
- [ ] Jira task updated with acceptance notes and evidence (screenshots, logs, reports).  
- [ ] PO/Stakeholder acceptance confirmed in sprint review.  

---

## 📦 Additional DoD – Catalog Mapping Automation (CMT)  
- [ ] Extracted competitor catalog data matches Amazon catalog fields (SKU, UPC, edition, platform, etc.).  
- [ ] Regex/JMESPath rules tested for accuracy and edge cases.  
- [ ] Mapping validated across **3P & Retail products** samples.  
- [ ] Catalog attributes (e.g., platform/edition) not missing for release scope.  

---

## 📚 Additional DoD – Kindle Migration (ISBN → ASIN)  
- [ ] ISBN successfully mapped to valid ASIN in target catalog.  
- [ ] Metadata (title, author, edition, language) verified and consistent.  
- [ ] Responsive UI pages tested on different devices (desktop, tablet, Kindle app).  
- [ ] Documentation updated (migration logs, validation reports).  

---

## 🌱 Continuous Improvement DoD  
- [ ] Retrospective action items implemented in upcoming sprint.  
- [ ] At least one new automation or validation rule added if gaps were found.  

---

✅ *This is a sample/public version. In actual projects, the Definition of Done was co-created with engineering, QA, and business teams to ensure shared ownership and transparency.*  
