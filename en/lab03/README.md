# 📘 Exercise 3: Document Lifecycle & Versioning in SharePoint

## 🏢 Scenario

As part of the IT department at **Digitera Ltd.**, you are now responsible for managing the **document lifecycle** within the SharePoint-based document management system.

The company requires a reliable way to:
- track document changes,
- manage collaborative editing,
- restore previous versions,
- ensure proper control over document updates.

---

## 🎯 Objectives

In this exercise, you will:

- Use **versioning** in a document library
- Simulate a real-world **collaboration scenario** with multiple document edits
- Use **check-out / check-in** to control editing
- View and restore previous document versions

---

## 1️⃣ Step 1: Simulate a document editing workflow

### Upload a test file:
1. Upload a document (e.g. `Contract_ClientY.docx`)
2. Use check-out to edit the document
3. Make changes and check it back in
4. Write a short comment describing the change

Repeat the process **at least 2 more times** with meaningful edits (or collaborate with another student)


---

## 2️⃣ Step 2: View version history

1. Click the **three dots (⋯)** next to the document
2. Choose **Version History**
3. Review each version:
   - Comments
   - Timestamps
   - Editors
4. Optionally click **Restore** on an earlier version

---

## 3️⃣ Step 3: Create an Email Notification Rule

Digitera's managers want to be notified whenever a new document is added to the `Company Documents` library.

Use **Automate Rule** to build a flow that sends an email to a specified recipient whenever a new file is uploaded.

### 🔧 How to do it:

1. Go to the SharePoint **Company Documents** library
2. Click on the menu: **Automate > Power Automate > Create a flow**
3. Choose the template: **"Send a customized email when a new file is added"**

   *(If not available, use: “When a file is created (properties only)” from SharePoint connector)*

4. Customize the flow:
   - Trigger: `When a file is created`
   - Action: `Send an email to`
   - To: your own email or other collaborator
   - Custom message: `New file was uploaded to Company Documents, please review.`

6. Create another flow to set the value of column  `Owner` to `Unknown` when a new document is uploaded.

7. Save and **test the flow** by uploading a new document

---
## 📚 Resources

- [Enable versioning in SharePoint](https://support.microsoft.com/en-us/office/how-versioning-works-in-lists-and-libraries-0f6cd105-974f-44a4-aadb-43ac5bdfd247)
- [Check out, check in, or discard changes](https://support.microsoft.com/en-us/office/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de)
- [SharePoint version history overview](https://support.microsoft.com/en-us/office/view-version-history-in-sharepoint-5c55212c-1a6f-4692-84f4-9d6c10c6f512)