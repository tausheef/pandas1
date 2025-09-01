# 📊 Pandas Practice Projects

This repository contains two hands-on data analysis projects built using **Pandas**, a powerful Python library for data manipulation and analysis.

---

## 🗂️ Project 1: Anime Dataset Analysis

In this project, I worked with an anime ranking dataset to practice core Pandas operations.

### Key Highlights:
- Loaded and cleaned data using `read_csv()` and string methods
- Applied **feature extraction** from text-based columns
- Used **filtering**, **conditional selection**, and **sorting**
- Practiced **applying custom functions** using `.apply()` and lambda

---

## 🌍 Project 2: World Countries Dataset

This project involved a rich dataset of 190+ countries with 60+ features including economic, geographic, and political indicators.

### Key Highlights:
- Cleaned and preprocessed **real-world messy data**
- Handled **missing values** and inconsistent formats
- Performed **grouping** by continent, democracy type, and more
- Extracted insights using **aggregations** and **lambda functions**

---

## 🧰 Tools & Libraries Used
- Python
- Pandas
- Jupyter Notebook
- NumPy

---

## 🔗 Author

**Tausheef Raza**  
GitHub: [@tausheef](https://github.com/tausheef)

---

Feel free to explore and use these notebooks to get started with Pandas!

"""

# Write to README.md
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content.strip(), encoding="utf-8")

readme_path.name
