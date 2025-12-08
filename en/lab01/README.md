# 📘 Exercise 1: Using Google Drive as a Document Management System (DMS)

This exercise introduces the fundamentals of designing and implementing a Document Management System (DMS) using **Google Drive**.  
Students analyze a sample company, identify document types, propose a folder structure, assign access rights, and implement the system.

---

# 🏢 Company Description

**Example company:** *Fashion Brand X*  
Fashion Brand X is an online fashion retailer operating a web shop where it sells a variety of digital and physical fashion products.

---

# 👥 Company Employee Structure

The company employs **50 people**, organized into the following departments:

- **Accounting (5 employees)**  
  Responsible for invoicing, accounting, and financial reporting.

- **Marketing (10 employees)**  
  Responsible for advertising, digital marketing, and social media.

- **IT Department (5 employees)**  
  Responsible for systems, maintenance, and technical support.

- **Logistics (20 employees)**  
  Handles product packaging, shipping, and warehouse operations.

- **Operations (5 employees)**  
  Manages project coordination and daily operational workflows.

- **Executive (5 employees)**  
  Responsible for company leadership (C-level management).

---

# 📄 Document Identification

There are **6 departments** in the company:  
Accounting, Marketing, IT, Logistics, Operations, Executive.

### ✔️ How to collect document information?
Possible methods include:

- Meetings with department representatives  
- Emails with structured questionnaires  
- Phone interviews with employees  
- On-site document analysis  
- Proposing an initial structure based on prior experience

---

## **Accounting Department – Document Types**

- Invoices – PDF  
- Accounting statements  
- Financial reports  
- Bank fees and bank reports  

---

## **Marketing Department – Document Types**

- Monthly social media plans – Excel  
- Images for social posts  
- Product images  
- Meeting reports – PDF/Word  
- Presentations – PowerPoint  

---

## **IT Department – Document Types (TODO)**  
_Write your own document identification for this department._

---

## **Logistics Department – Document Types (TODO)**  
_Write your own document identification for this department._

---

## **Operations Department – Document Types (TODO)**  
_Write your own document identification for this department._

---

## **Executive Department – Document Types (TODO)**  
_Write your own document identification for this department._

---

# 🔍 Identification of DMS Needs & Usage

### **Accounting**

- Document types: PDF, Word, Excel, CSV  
- Needs structured organisation by type:  
  - Invoices  
  - Statements  
  - Reports  
- All employees need DMS access: **YES**  
- Special features: none  

---

### **Marketing**

- Document types: PDF, Word, Excel, PowerPoint, Images  
- Needs structured organisation by type:  
  - Text documents  
  - Images  
  - Reports  
  - Presentations  
- All employees need DMS access: **YES**  
- Special features: none  

---

### **IT Department (TODO)**  
_Write your own DMS needs for this department._

---

### **Logistics Department (TODO)**  
_Write your own DMS needs for this department._

---

### **Operations Department (TODO)**  
_Write your own DMS needs for this department._

---

### **Executive Department (TODO)**  
_Write your own DMS needs for this department._

---

# 🗂 Proposed Folder Structure

### **Notes:**
- Each department has its **own root folder**
- Access is **restricted per department**
- A shared folder is available for all employees

```
Fashion_Company_DMS
│
├── Accounting
│   ├── Invoices
│   ├── Statements
│   └── Reports
│
├── Marketing
│   ├── Reports
│   ├── Social_Media
│   │   ├── Images
│   │   └── Plans
│   └── Presentations
│
├── IT
│   └── TODO: add folder structure for this department
│
├── Logistics
│   └── TODO: add folder structure for this department
│
├── Operations
│   └── TODO: add folder structure for this department
│
├── Executive
│   └── TODO: add folder structure for this department
│
└── Shared
    ├── Documents
    │   ├── Internal
    │   └── HR
    └── Corporal_Visual_Identity
        ├── Branding
        └── Logos
```

---

# 🛠 Choose a DMS Platform

Based on company needs and pricing, possible candidates include:

- Microsoft SharePoint  
- Google Drive  
- Dropbox  
- Open-source solutions  

### **Chosen DMS:**  
👉 **Google Drive** – suitable for small to mid-size companies, user friendly, low cost, well integrated.

---

# 🚀 Implementation

The folder structure is implemented in Google Drive following the design above.

Example screenshots or confirmation:

### **Accounting Folder**

(Example structure)

### **Shared Folder**

(Example structure)

---

# ✅ DMS Needs Checklist

Complete this table to verify whether the system meets all departmental requirements.

| Department | Needs | Are needs satisfied? | Notes |
|-----------|-------|----------------------|--------|
| Accounting | PDF, Word, Excel, CSV; structured by type (invoices/statements/reports) | YES | / |
| Marketing | PDF, Word, Excel, PowerPoint, Images; structured by document type | YES | / |
| IT | TODO |  | |
| Logistics | TODO |  | |
| Operations | TODO |  | |
| Executive | TODO |  | |

---

# 🎉 Conclusion

All required departmental needs are satisfied, and the DMS implementation in Google Drive was successful.  
This system enables the company to efficiently manage, store, and collaborate on documents across all departments.

---

## Notes

**Use of AI:** During the development of the content and preparation of the documentation, the ChatGPT tool (OpenAI) was used as assistance for generating ideas, optimizing text, and shaping the structure of the project.  
All final solutions were reviewed, verified, and adjusted by the author of the project as needed.

## References

OpenAI. (2025). *ChatGPT* (Aug 2025) [Large language model]. https://chat.openai.com/