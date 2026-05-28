# Youtube-video-manager-
````md
# YouTube Video Manager 🎥

A simple command-line YouTube Video Manager built using Python.  
This project helps users manage YouTube video records with features like adding, updating, deleting, and listing videos using JSON file storage.

---

## 🚀 Features

- 📃 List all videos
- ➕ Add new videos
- ✏️ Update existing videos
- ❌ Delete videos
- 💾 Store data permanently using JSON
- 🐍 Beginner-friendly Python project

---

## 📂 Project Structure

```bash
youtube-manager/
│
├── main.py
├── youtube.txt
└── README.md
```

---

## 🛠 Technologies Used

- Python 3
- JSON Module

---

## ▶️ How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/youtube-manager.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd youtube-manager
```

### 3️⃣ Run the Program

```bash
python main.py
```

---

## 📸 Application Preview

```bash
Youtube Manager | choose an option

1. List a youtube videos
2. Add a youtube video
3. Update a youtube video details
4. Delete a youtube video
5. Exit the app
```

---

## 💾 JSON Data Example

Data is stored inside `youtube.txt` file in JSON format.

```json
[
  {
    "name": "Python Tutorial",
    "time": "15 mins"
  },
  {
    "name": "React Crash Course",
    "time": "30 mins"
  }
]
```

---

## 📚 Functions Overview

| Function Name | Description |
|---------------|-------------|
| `load_data()` | Loads saved videos from file |
| `save_data_helper()` | Saves video data to file |
| `list_all_videos()` | Displays all videos |
| `add_video()` | Adds a new video |
| `update_video()` | Updates video details |
| `delete_video()` | Deletes a selected video |
| `main()` | Controls application flow |

---

## 🔮 Future Improvements

- 🔍 Search functionality
- 🏷 Add categories/tags
- 📅 Upload timestamps
- 🖥 GUI version using Tkinter
- 🗄 Database integration

---

## 👨‍💻 Author

**Mahesh Pawal**

GitHub: https://github.com/your-username

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
````
