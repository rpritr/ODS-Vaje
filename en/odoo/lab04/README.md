# 📘 Company Logo and Sharing Documents in Odoo

## 🏢 Scenario

As part of the IT department at **Digitera Ltd.**, the document folders are in place and the files are filed.

Two things are still missing. The company record still shows the default logo, and colleagues outside your login need a link to the documents.

---

## 🎯 Objectives

In this exercise, you will:

- Replace the company logo
- Share documents with a URL
- Open that URL and confirm the files are visible

---

## 🧰 Prerequisites

- The Odoo database from [lab02](../lab02/README.md) and [lab03](../lab03/README.md)
- A logo image you are allowed to use (PNG or JPG)

---

## 1️⃣ Step 1: Change the company logo

1. Open **Settings**
2. Go to **Users & Companies → Companies**
3. Open **Digitera Ltd.**
4. Click the logo placeholder and upload your image
5. Click **Save**

To see the logo on company documents, go to **Settings → Companies → Configure Document Layout**. The uploaded logo appears in the layout preview.

---

## 2️⃣ Step 2: Share a document with a URL

1. Open **Documents**
2. Open `Company Documents / Contracts / Contract_ClientX.pdf`
3. Click **Share**
4. Set **Access through link** to **Viewer**
5. Click **Save**
6. Click **Copy link** and paste the URL into a notes file

Repeat for `Invoice_March2025.pdf` in `Invoices`, and keep that second URL as well.

---

## 3️⃣ Step 3: Share the folder with a URL

1. Select the `Company Documents` folder
2. Click the **Actions** (gear) icon above the tree
3. Choose **Share**
4. Set **Access through link** to **Viewer**
5. Click **Save**, then **Copy link**

One folder link opens the files inside `Company Documents`. Leave `Private` unshared.

---

## 4️⃣ Step 4: Open the shared URLs

1. Open a private browser window
2. Paste the contract URL and confirm the file opens
3. Paste the folder URL and confirm you can see `Contracts`, `Invoices`, `Offers`, `Internal Docs`, and `Marketing`

---

## ✅ Expected outcome

By the end of the exercise, you should have:

- The **Digitera Ltd.** logo replaced in **Settings → Companies**
- A share URL for `Contract_ClientX.pdf`
- A share URL for `Invoice_March2025.pdf`
- A share URL for the `Company Documents` folder
- Both a file link and the folder link checked in a private window

---

## 📚 Resources

- [Sharing and access rights — Odoo Documents](https://www.odoo.com/documentation/19.0/applications/productivity/documents.html)
- [Companies and the company logo](https://www.odoo.com/documentation/19.0/applications/general/companies.html)
