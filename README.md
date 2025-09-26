# 📂 Smart File Organizer & Encryptor

A Windows-based desktop tool built with **Python + Tkinter** that automatically organizes files, removes duplicates, and provides simple **encryption/decryption** for files and folders.  
It also runs in the **system tray** for background monitoring.

---

## 🚀 Features

- ✅ **Auto File Organization**  
  - Moves images, videos, music, documents, archives, and programs into their proper folders.
  - Organizes subfolders into a dedicated "Folders" directory.

- 🔄 **Automatic Monitoring**  
  - Watches a chosen folder (default: `Downloads`) for new files.
  - Runs in the background with a **system tray icon**.
  - Customizable monitoring delay.

- 🗑️ **Duplicate Cleaner**  
  - Detects duplicate files by hashing and automatically deletes them.

- 🔐 **File & Folder Encryption**  
  - Encrypt/decrypt individual files with a password.  
  - Batch encrypt/decrypt entire folders.  
  - Uses **AES (via Fernet encryption)**.

- 🖥️ **Windows Startup Integration**  
  - Option to auto-start with Windows using registry.

- 📝 **Tkinter GUI**  
  - User-friendly interface with logs and buttons for all actions.

---

## ⚙️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ElvisNjaramba/File-Manager-Encryptor.git
   cd File-Manager-Encryptor

2. **Set up a Virtual Environment (recommended)**
   python -m venv venv
   venv\Scripts\activate   # On Windows

3. **Install Dependencies**
   pip install -r requirements.txt

4. **Run The App**
   python main.py

