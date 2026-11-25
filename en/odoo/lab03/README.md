# 📘 Uploading and Organizing Company Documents in Odoo

## 🏢 Scenario

As a member of the IT department at **Digitera Ltd.**, you already created the company folders in Odoo Documents.

Colleagues now need the real files filed in the right place, so anyone can find a contract, an invoice, or an offer without searching through one mixed folder.

---

## 🎯 Objectives

In this exercise, you will:

- Add folders for each kind of document
- Upload company documents into those folders
- Move an existing file into the folder where it belongs

---

## 🧰 Prerequisites

- The Odoo database and folders from [lab02](../lab02/README.md)
- The **Documents** app open on the **Company** section

---

## 1️⃣ Step 1: Add folders for document types

1. Open **Documents** and select `Company Documents`
2. Click **New → Folder** and create:

   - `Contracts`
   - `Invoices`
   - `Offers`

`Internal Docs`, `Private`, and `Marketing` are already there from the previous exercise.

---

## 2️⃣ Step 2: Upload the company documents

Create these files on your computer, or use the samples from class:

- `Contract_ClientX.pdf`
- `Invoice_March2025.pdf`
- `Offer_WebPortal.pdf`
- `Marketing_Plan.pdf`

Upload each file into its folder. Select the folder first, then click **New → Upload** (or drag the file onto the folder):

| File | Folder |
|------|--------|
| `Contract_ClientX.pdf` | `Contracts` |
| `Invoice_March2025.pdf` | `Invoices` |
| `Offer_WebPortal.pdf` | `Offers` |
| `Marketing_Plan.pdf` | `Marketing` |

---

## 3️⃣ Step 3: Move the archive note

The file you uploaded in lab02 still sits in `Company Documents`. It belongs with the internal documentation.

1. Open `Company Documents`
2. Drag `Digitera document archive and internal documentation` onto `Internal Docs`

Or open the file, click **Actions → Move**, choose `Internal Docs`, and confirm.

---

## 4️⃣ Step 4: Check the structure

Open each folder and confirm the files are only in the folder from the table above.

`Company Documents` should look like this:

```text
Company Documents
├── Contracts
│   └── Contract_ClientX.pdf
├── Invoices
│   └── Invoice_March2025.pdf
├── Offers
│   └── Offer_WebPortal.pdf
├── Internal Docs
│   └── Digitera document archive and internal documentation
├── Marketing
│   └── Marketing_Plan.pdf
└── Private
```

`Private` stays empty in this exercise.

---

## ✅ Expected outcome

By the end of the exercise, you should have:

- Folders `Contracts`, `Invoices`, and `Offers` inside `Company Documents`
- Each sample file uploaded into the matching folder
- The archive note moved into `Internal Docs`

---

## 📚 Resources

- [Folders and files — Odoo Documents](https://www.odoo.com/documentation/19.0/applications/productivity/documents.html)
