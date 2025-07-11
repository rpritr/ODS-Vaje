# 2️⃣ Types of Documents and Metadata

**Exercise 2 – Understanding document types and metadata**  
📅 Duration: 1 hour

---

## 🎯 Objective

The goal of this exercise is to understand the concept of metadata, how it is stored in digital documents, and how to extract and analyze metadata from different document types.

---

## 📝 Learning outcomes

After completing this exercise, you will be able to:
- Explain what metadata is and why it is important.
- Distinguish between document content and metadata.
- Use a tool to extract metadata from different digital documents.
- Compare metadata from various file formats.

---

## 🔍 Task description

### 1. **What is metadata?**
Read and take notes on:
- Definition of metadata (“data about data”).
- Types of metadata: descriptive, administrative, structural.
- Examples of metadata in documents: author, creation date, modification history, version, tags.

---

### 2. **Prepare documents**
Find or create **three documents of different types**, for example:
- A `.docx` Word document.
- A `.pdf` PDF file.
- A `.jpg` or `.png` image file (optional: a `.odt` file if you prefer).

Save them to a folder you will use for analysis.

---

### 3. **Analyze metadata**
Use a metadata analysis tool to extract metadata from each document. Suggested tool:
- [ExifTool](https://exiftool.org/) (cross-platform, command-line)
  - Install and run:  
    ```bash
    exiftool yourfile.pdf
    ```
  - Or drag & drop a file into an online metadata viewer.

For each file, save the output of the metadata analysis.

You might also use [Exif.tools](https://exif.tools/) or [Exiftool-web](https://exiftool.lucasgelfond.online/)

---

### 4. **Compare metadata**
Write down:
- Which metadata fields are present in all files?
- Which fields are unique to certain formats?
- What kind of sensitive information could be leaked through metadata?

---

## 📄 Deliverables

At the end of this exercise, submit a single `.md` or `.pdf` document with:
✅ A short explanation of what metadata is (2–3 sentences)  
✅ A table summarizing key metadata fields extracted from each file  
✅ Answers to the comparison questions (see above)

---

## 📊 Metadata Table Template

You can use this table to summarize your findings:

| File Name         | File Type   | Key Metadata Fields                     |
|--------------------|-------------|-----------------------------------------|
| `example.docx`     | Word (.docx)| Author, creation date, last modified… |
| `example.pdf`      | PDF         | Title, producer, creation date…       |
| `example.jpg`      | JPEG        | Camera model, GPS coordinates…        |

---

## 🛠️ Suggested tools

- ExifTool (recommended)
- Text editor or Word processor for your report

---

## 💡 Tips

When analyzing PDF or Word documents, pay special attention to **hidden metadata** like author names or tracked changes — these can reveal sensitive information.
