# Reddit Media Gallery

A clean, minimal image gallery for browsing any subreddit with sorting options, keyword filtering, and keyboard navigation. Built with **Python / Flask**.

---

## Features

- **Subreddit browsing** — Enter any subreddit name to load its images instantly
- **Sorting options** — Sort posts by Hot, New, or Trending
- **Custom image count** — Choose how many images to load at once
- **Keyword filtering** — Optionally filter results by keyword (e.g. a character name or "cosplay")
- **Full-page gallery view** — Images are displayed in a clean, dark-background gallery
- **Keyboard & click navigation** — Select any image and navigate with arrow keys or by clicking through them

---

## Requirements

- Python 3.x
- Flask

---

## Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Reddit-Media-Gallery.git
   cd Reddit-Media-Gallery
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   python app.py
   ```

4. **Open in your browser**
   ```
   http://localhost:5000
   ```

---

## Usage

1. Enter a subreddit name (e.g. `cats`, `cosplay`, `EarthPorn`)
2. Select a sorting method: **Hot**, **New**, or **Trending**
3. Enter the number of images to load
4. *(Optional)* Enter a keyword to filter results
5. Browse the gallery — click any image to open it, then use **arrow keys** or **click** to navigate

---

## Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript
