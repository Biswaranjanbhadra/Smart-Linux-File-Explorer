# Smart-Linux-File-Explorer
# 🧠 Smart Linux File Explorer (C++)

## 📘 Overview
The *Smart Linux File Explorer* is a C++ console-based file management tool that mimics basic Linux commands.  
It allows users to *navigate directories, create/delete files, copy files, search content, and log activities* automatically.

---

## ⚙️ Features
•⁠  ⁠📁 *List files and directories*
•⁠  ⁠📂 *Change directory (cd)*
•⁠  ⁠📝 *Create and delete files*
•⁠  ⁠📄 *Copy files*
•⁠  ⁠🔍 *Search files by name*
•⁠  ⁠🧱 *Create and remove directories*
•⁠  ⁠🕓 *Logs every action* in ⁠ activity_log.txt ⁠ with timestamps

---

## 🧩 Commands

| Command | Description |
|----------|--------------|
| ⁠ ls ⁠ | List files and directories |
| ⁠ cd <folder> ⁠ | Change current directory |
| ⁠ create <filename> ⁠ | Create a new file |
| ⁠ delete <filename> ⁠ | Delete a file |
| ⁠ copy <src> <dest> ⁠ | Copy a file |
| ⁠ search <keyword> ⁠ | Search files containing the keyword |
| ⁠ mkdir <folder> ⁠ | Create a new directory |
| ⁠ rmdir <folder> ⁠ | Delete a directory (recursively) |
| ⁠ exit ⁠ | Exit the program |

---

## 🧠 Example Usage
⁠ bash
>>> ls
>>> mkdir Projects
>>> cd Projects
>>> create notes.txt
>>> copy notes.txt backup.txt
>>> delete backup.txt
>>> search notes
>>> exit
 ⁠

---

## 🛠️ How to Compile and Run (Windows / VS Code)

### 1️⃣ Install MinGW-w64 (GCC)
Download from: [https://winlibs.com/](https://winlibs.com/)  
Extract to ⁠ C:\mingw-w64 ⁠ and add ⁠ C:\mingw-w64\bin ⁠ to *PATH*.

Verify installation:
⁠ bash
g++ --version
 ⁠

### 2️⃣ Compile the Program
⁠ bash
g++ -std=c++17 explorer.cpp -o explorer
 ⁠

### 3️⃣ Run the Program
⁠ bash
./explorer
 ⁠

---

## 📄 Logging
All user actions (like creating, deleting, or navigating files) are logged in:

activity_log.txt

Example:

[Sat Nov 09 14:35:21 2025] Created file: notes.txt
[Sat Nov 09 14:36:02 2025] Deleted file: old_data.txt


---

## 👨‍💻 Author
*Biswa Ranjan Bhadra*  
📧 biswaranjanbhadra2002@gmil.com 
🎓 B.Tech in Electrical And Electronics Engineering
🏫 ITER, S’O’A University, Bhubaneswar  

---

## 🏁 License
This project is open-source and free to use for educational purposes.
