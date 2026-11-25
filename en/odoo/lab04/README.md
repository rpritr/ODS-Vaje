# 📘 Company Logo, Versions, and Sharing Documents in Odoo

## 🏢 Scenario

As part of the IT department at **Digitera Ltd.**, the document folders are in place and the files are filed.

The contract with Client X will change several times before it is final. You need a record of each change, a way to stop further edits once it is approved, the company logo on Digitera’s record, and a link so someone outside your login can read the file.

---

## 🎯 Objectives

In this exercise, you will:

- Keep several versions of one document and download an older one
- Lock the approved file
- Replace the company logo
- Share documents with a URL and confirm the link works

---

## 🧰 Prerequisites

- The Odoo database from [lab02](../lab02/README.md) and [lab03](../lab03/README.md)
- A logo image you are allowed to use (PNG or JPG)

---

## 1️⃣ Step 1: Manage versions

1. Open **Documents** and open `Company Documents / Contracts / Contract_ClientX.pdf`
2. Click **Download** and save the file on your computer
3. Change the file (add a line such as `Version 2: payment terms updated`) and save it
4. Back in Odoo, open the same file
5. Click **Actions → Manage versions**
6. Upload the changed file as a new version
7. Repeat the edit and upload **two more times**, with a different sentence each time (`Version 3: …`, `Version 4: …`)

The file now has the original upload plus three newer versions.

8. Open **Actions → Manage versions** again
9. Versions are listed in upload order. Download an earlier version and open it
10. Confirm the downloaded file is the older text, not the latest edit

---

## 2️⃣ Step 2: Note the change and lock the file

1. With `Contract_ClientX.pdf` open, click **Actions → Info & Tags**
2. In the chatter, log a note: `Approved version. Payment terms updated.`
3. Close the details panel
4. Click **Actions → Lock**

The locked file can be opened and downloaded. It can no longer be modified.

---

## 3️⃣ Step 3: Change the company logo

1. Open **Settings**
2. Go to **Users & Companies → Companies**
3. Open **Digitera Ltd.**
4. Click the logo placeholder and upload your image
5. Click **Save**

To see the logo on company documents, go to **Settings → Companies → Configure Document Layout**. The uploaded logo appears in the layout preview.

---

## 4️⃣ Step 4: Share a document with a URL

1. Open **Documents**
2. Open `Company Documents / Contracts / Contract_ClientX.pdf`
3. Click **Share**
4. Set **Access through link** to **Viewer**
5. Click **Save**
6. Click **Copy link** and paste the URL into a notes file

Repeat for `Invoice_March2025.pdf` in `Invoices`, and keep that second URL as well.

---

## 5️⃣ Step 5: Share the folder with a URL

1. Select the `Company Documents` folder
2. Click the **Actions** (gear) icon above the tree
3. Choose **Share**
4. Set **Access through link** to **Viewer**
5. Click **Save**, then **Copy link**

One folder link opens the files inside `Company Documents`. Leave `Private` unshared.

---

## 6️⃣ Step 6: Open the shared URLs

1. Open a private browser window
2. Paste the contract URL and confirm the file opens
3. Paste the folder URL and confirm you can see `Contracts`, `Invoices`, `Offers`, `Internal Docs`, and `Marketing`

---

## ✅ Expected outcome

By the end of the exercise, you should have:

- `Contract_ClientX.pdf` with at least four versions, and an older version downloaded
- A chatter note on that file, and the file **locked**
- The **Digitera Ltd.** logo replaced in **Settings → Companies**
- A share URL for `Contract_ClientX.pdf`
- A share URL for `Invoice_March2025.pdf`
- A share URL for the `Company Documents` folder
- Both a file link and the folder link checked in a private window

---

## 📚 Resources

- [Documents — versions, lock, and sharing](https://www.odoo.com/documentation/19.0/applications/productivity/documents.html)
- [Companies and the company logo](https://www.odoo.com/documentation/19.0/applications/general/companies.html)
