
# 📚 QuickWord - Dark Mode Dictionary App

QuickWord is a stylish, **dark-themed Tkinter dictionary application** built with Python.  
It allows you to **instantly search for word definitions, parts of speech, and example sentences** using the **Free Dictionary API**.

---

## ✨ Features

- 🔍 **Instant Search** — Just type a word and hit "Search".
- 🎨 **Dark Mode UI** — Clean and modern interface that's easy on the eyes.
- 📖 **Multiple Definitions** — Supports different parts of speech (noun, verb, adjective, etc.).
- 💡 **Example Sentences** — Get context for better understanding.
- ⚠️ **Error Handling** — Handles empty input, no definitions found, and no internet gracefully.
- 📦 **Lightweight** — No heavy dependencies, just Python + Requests.


---

## 🛠️ Installation

### 1️⃣ Prerequisites

- **Python 3.x**
- Internet connection (for API requests)
- `requests` library

### 2️⃣ Install Dependencies

```bash
pip install requests
````

> **Note:** Tkinter comes pre-installed with Python on most systems.

### 3️⃣ Run the App

```bash
python quickword.py
```

---

## 💻 Usage

1. Open the application.
2. Enter the word you want to search for in the input box.
3. Click **Search** or press **Enter**.
4. View results including:

   * **Part of speech**
   * **Definition**
5. Search for another word any time.

---

## 🌐 API Reference

This app uses the [Free Dictionary API](https://dictionaryapi.dev/).

**Endpoint Example:**

```
https://api.dictionaryapi.dev/api/v2/entries/en/<word>
```

---

## 📂 Project Structure

```
quickword/
│
├── quickword.py     # Main Python Tkinter app
├── README.md        # Project documentation
└── screenshot.png   # Screenshot of the application (optional)
```

---

## 🎨 UI Colors

| Element             | Color Hex |
| ------------------- | --------- |
| Background          | `#1e1e1e` |
| Text (Foreground)   | `#ffffff` |
| Entry Field         | `#2d2d2d` |
| Button              | `#3a3a3a` |
| Active Button Hover | `#444444` |

---

## ⚠️ Notes

* Only supports **English words**.
* Requires an **active internet connection**.
* Handles:

  * Empty input
  * Word not found
  * API request failures

---

## 🚀 Future Improvements

* 📌 Add **synonyms & antonyms**.
* 📌 Add **pronunciation audio**.
* 📌 Add **offline mode** with local word database.

---

🙌 Author
Made with 💻 and ☕ by Atharva Arjun Patil

Department : Computer Engineering
