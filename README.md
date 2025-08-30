 # Mini Python Projects for Intermediates

This repository contains **3 mini Python projects** designed for intermediate learners. Each project demonstrates practical use cases of Python with libraries like `schedule`, `requests`, and `pytube`.

---

## Projects

### 1. Automated Backup Script (`backup.py`)
- **Description:** Creates daily backups of a specified folder and stores them with the current date in a destination directory. Uses `schedule` for task automation.
- **Features:**
  - Runs automatically at a specified time.
  - Stores backups in date-stamped folders.
  - Prevents overwriting by checking existing folders.
- **How to Run:**
  ```bash
  pip install schedule
  python backup.py
  ```
- **Customize:**
  - Change `source_dir` and `destination_dir` in the script to your desired paths.
  - Adjust the schedule time inside:
    ```python
    schedule.every().day.at("18:57")
    ```

---

### 2. Currency Converter (`currency.py`)
- **Description:** Converts a base currency into multiple target currencies using [FreeCurrencyAPI](https://freecurrencyapi.com/).
- **Features:**
  - Real-time exchange rates.
  - Supports multiple currencies (USD, CAD, EUR, AUD, CNY).
  - Handles invalid input gracefully.
- **How to Run:**
  ```bash
  pip install requests
  python currency.py
  ```
- **Usage Example:**
  ```
  Enter the base currency (q for quit): USD
  CAD: 1.36
  EUR: 0.92
  AUD: 1.50
  CNY: 7.21
  ```

---

### 3. YouTube Video Downloader (`youtube.py`)
- **Description:** Downloads YouTube videos in the highest resolution available. Provides a GUI folder picker to choose the save location.
- **Features:**
  - Uses `pytube` to fetch and download videos.
  - Simple folder selection with `tkinter`.
  - Downloads MP4 videos with the best available quality.
- **How to Run:**
  ```bash
  pip install pytube
  python youtube.py
  ```
- **Usage Example:**
  ```
  Please enter a YouTube url: https://www.youtube.com/watch?v=dQw4w9WgXcQ
  (Select a folder in the dialog)
  Started download...
  Video downloaded successfully!
  ```

---

## Requirements
- Python 3.7+
- Install dependencies:
  ```bash
  pip install schedule requests pytube
  ```

---

## Project Structure
```
📦 mini-python-projects
 ┣ 📜 backup.py
 ┣ 📜 currency.py
 ┣ 📜 youtube.py
 ┣ 📜 README.md
```

---
 ## Author

**Rohana Upadhyaya**    
Location: Bengaluru, Karnataka 
