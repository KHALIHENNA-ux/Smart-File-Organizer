# Smart File Organizer (Python)

A robust and efficient Python script designed to automatically declutter and organize directories by categorizing files based on their extensions. Built with a focus on clean code, performance, and reliability.

## 🚀 Key Features
- **Smart Categorization**: Automatically detects and moves images, videos, documents, code, and more into dedicated folders.
- **Efficient Operations**: Uses `shutil.move` for high-speed file relocation instead of copying/deleting.
- **Conflict Management**: Smartly handles duplicate filenames by appending a prefix to avoid overwriting existing data.
- **Clean Architecture**: Implemented using **Dictionaries** for easy scalability and **Pathlib** for modern file system interactions.
- **Robust Error Handling**: Wrapped in try-except blocks to ensure the script doesn't crash during unexpected OS interruptions.

## 📂 Supported Categories
The script currently supports:
- **Images**: .png, .jpg, .jpeg, .gif, etc.
- **Documents**: .pdf, .docx, .txt, .doc
- **Media**: Video (.mp4, .webm) and Music (.mp3, .wav, .flac)
- **Programming**: .py, .js, .html, .css, .php
- **Archives**: .zip, .rar, .tar, .gz
- **And more**: Executables, Torrents, and Design files (.psd, .ai).

## 🛠️ Requirements
- Python 3.6+
- No external libraries required (uses built-in `pathlib`, `os`, and `shutil`).

## ⚙️ How to Use
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/smart-file-organizer.git](https://github.com/your-username/smart-file-organizer.git)# Smart-File-Organizer
