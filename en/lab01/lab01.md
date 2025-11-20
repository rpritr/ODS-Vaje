# 📁 Setting Up a SharePoint Document Management System for a Company

## 🏢 Scenario

You are part of the IT department at **Digitera Ltd..**, a company providing software development, consulting, and support services.

The management has asked you to set up a **document management system** using **Microsoft SharePoint** to help departments organize their documents and streamline internal operations.

---

## 🎯 Objectives

In this exercise, you will:

- Understand the basics of a document management system (DMS)
- Create a SharePoint document library with business-relevant metadata
- Upload and classify company documents
- Organize documents by views and filters for easier access

---

## 🧰 Prerequisites

- Microsoft 365 account
- Access to a SharePoint site (provided by your instructor)

We will provide you a link to the SharePoint site, example:  
`https://studentfisunm.sharepoint.com`

---

## 1️⃣ Step 1: Explore the SharePoint Site

1. Open the provided SharePoint site
2. Navigate to the **Documents** section or to the pre-created **Company Documents** library
3. Explore existing folders or create a new one called `Internal Docs`

---

## 2️⃣ Step 2: Create the Folders in the Document library

If you are allowed to create libraries:

1. Click **New > Folder**
2. Name it `Company Documents`
3. Create a New Word Document with content: `Digitera document archive and internal documentation`
4. Click **Create**

If not, use the existing `Company Documents` library provided by your instructor.


Next we will create some specific folders with Access Restrictions:

1. Click **New > Folder**
2. Name it `Private`
3. Click **Create**
4. Set Permissions so that only you can access the folder
---

## 3️⃣ Step 3: Add custom metadata columns

Inside the library, create the following custom columns:

| Column Name     | Type         | Choices (if applicable)             |
|------------------|--------------|-------------------------------------|
| `Department`     | Choice       | Development, Sales, Support         |
| `Document Type`  | Choice       | Contract, Invoice, Offer, Policy, Manual |
| `Client Name`    | Single line of text |                            |
| `Status`         | Choice       | Draft, Submitted, Approved          |
| `Year`           | Choice       | 2024, 2025                          |

📌 **How to add a column:**
- Go to the library view
- Click on **+ Add column**
- Choose the appropriate column type and set the name and choices

---

## 4️⃣ Step 4: Upload company documents

1. Download the provided sample documents (or use your own mock files):
   - `Contract_ClientX.pdf`
   - `Invoice_March2025.pdf`
   - `Offer_WebPortal.pdf`
2. Upload them to the `Company Documents` library
3. Open the **Details panel** for each file and fill in all metadata fields

Example:

File: Invoice_March2025.pdf  
Department: Support  
Document Type: Invoice  
Client Name: ClientX  
Status: Submitted  
Year: 2025  


## 5️⃣ Step 5: Use custom views

Now use filtered views to simulate real-world use:

### View 1: **By Specific folders**
- Show contents of `Internal Documents` folder
- Show contents of `Marketing` folder
- Show only docments by `Specific` owner

---

## ✅ Expected Outcome

By the end of the exercise, you should have:

- A document library named `Company Documents`
- At least 3 uploaded files with properly filled metadata
- 2–3 custom views created to filter or group documents
- A clear understanding of how metadata improves navigation and management

---


## 📚 Resources

- [What is SharePoint?](https://learn.microsoft.com/en-us/sharepoint/introduction)
- [Create and manage custom views](https://support.microsoft.com/en-us/office/create-a-view-7e8a20dc-8619-431e-bf52-7c1a53c8e73c)
- [SharePoint metadata columns](https://support.microsoft.com/en-us/office/add-remove-or-update-columns-in-a-library-02f0a1f2-9ea1-4f8f-9016-0507d52d7d8c)