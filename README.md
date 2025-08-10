"# ELEVATE_LABS_INTERN_TASK4" 
# 📝 Java Notes App (File I/O)

A simple **console-based Notes App** built in Java that uses **FileWriter** and **BufferedReader** to store and retrieve notes from a text file.

---

## 📌 Features
- **Add Notes** – Save your thoughts in `notes.txt`.
- **View Notes** – Read all saved notes from the file.
- **Persistent Storage** – Notes are stored locally and remain available until deleted.

---

## ⚙️ How It Works
1. **FileWriter**
    - Used to write notes to `notes.txt`.
    - `FileWriter("notes.txt", true)` is used to **append** notes without overwriting existing ones.

2. **BufferedReader** with **FileReader**
    - Reads the saved notes line by line.

3. **Menu-driven Program**
    - **Option 1:** Add Note
    - **Option 2:** View Notes
    - **Option 3:** Exit

---

## 📂 File Structure

