# 🏫 How to Add a University or Study Material to **My University Notes**

Welcome to the **GitNotes Repository** — a community-driven collection of notes and study material for various universities and courses.  
Follow this simple guide to contribute your university, course, branch, semester, and subject materials correctly.

---

## ⚙️ Folder Structure Overview
<details>
<summary>The directory structure for each university should look like this:</summary>

data/

└── UniversityName/

    └── CourseName/

        └── BranchName/

            └── SemesterName/

                └── SubjectName/

                    ├── Notes1.pdf

                    ├── Notes2.pdf
└── README.md

</details>


## 🧭 Naming Rules (Very Important)

> ❗ To ensure compatibility with the GitNotes web app, **follow these naming rules strictly.**

### ✅ Allowed:
- **No spaces** → use continuous words (e.g., `ShriRamswaroopMemorialUniversity`)
- **No dots (.) or special characters** (`_`, `-`, `@`, etc. not allowed)
- Use **alphanumeric characters only**
- Maintain **CamelCase** for readability (optional but preferred)

### ❌ Not Allowed:
Shri Ramswaroop Memorial University ❌
shri_ramswaroop_memorial_university ❌
Shri.Ramswaroop@Memorial-University ❌

---

## 🏗️ Example Directory Structure

If you’re adding **Shri Ramswaroop Memorial University**, structure it like this:

data/

└── ShriRamswaroopMemorialUniversity/

└── BTech/

└── CSE/

└── Semester1/

└── Physics/

├── Module1.pdf

├── Unit2.pdf

└── NotesSummary.txt

---

## 📤 Steps to Contribute

### 1. **Fork the Repository**
Click the **“Fork”** button on the top-right of [this repository](https://github.com/UraniumUtkarsh/my-university-notes).

### 2. **Clone Your Fork**
```bash
git clone https://github.com/<your-username>/my-university-notes.git
cd my-university-notes
```
3. Create a New Folder
Inside the data/University/ folder, create your new university directory following the **naming rules**.

Example:
```
bash
Copy code
mkdir -p data/University/ShriRamswaroopMemorialUniversity/BTech/CSE/Semester1/Physics
```
4. Add Notes or Files
Place your .pdf, .txt, .docx, or .pptx files inside the respective subject folder.

Tip: You can also include a README.md in each subject folder summarizing the material.

5. Commit and Push
bash
Copy code
git add .
git commit -m "Added notes for ShriRamswaroopMemorialUniversity - BTech CSE Semester1 Physics"
git push origin main
6. Create a Pull Request
Go to your fork on GitHub → Click “Contribute” → “Open Pull Request”
Add a short description and submit the PR.

💡 Additional Tips
- Keep filenames short and descriptive (e.g., DigitalLogicNotes.pdf)
- Avoid uploading copyrighted books
- Prefer your own summaries, handwritten scans, or project reports
- Check other universities’ folders for structure inspiration
