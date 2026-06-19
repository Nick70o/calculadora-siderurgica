# 🔩 Steel Products Calculator (kg → pieces)

A single-file web calculator that converts **weight, length, and quantity of pieces** for **40+ types of steel products** (beams, tubes, square tubing, angles, and more). Built to eliminate manual math and speed up quoting for a steel/metalwork business.

🔗 **Demo:** publish it with GitHub Pages and add the link here.

---

## ✨ Features

- ⚖️ Converts **kg ↔ pieces** based on length and product type
- 🧱 Supports **40+ steel products** (beams, tubes, square tubing, angles, etc.)
- 💾 **Local persistence** (`localStorage`) — keeps your data between sessions
- 🔁 **Versioned data migration** — preserves saved data across updates
- 🔍 **Search with inline editing**, avoiding rework
- 🇧🇷 Brazilian decimal formatting to reduce reading errors at the sales counter
- 📱 **Responsive**, single-file (HTML + CSS + JS), no external dependencies

---

## 🛠️ Tech stack

- **HTML5**
- **CSS3** (responsive design, CSS variables)
- **JavaScript** (vanilla) with `localStorage`

---

## 🚀 How to use

Since it's a single file, just open `index.html` in your browser:

```bash
git clone https://github.com/Nick70o/calculadora-siderurgica.git
cd calculadora-siderurgica
# open index.html (double-click) or run a local server:
python -m http.server 8000
# go to http://localhost:8000
```

### Publish with GitHub Pages

In **Settings → Pages**, select the `main` branch and the `/ (root)` folder. The app becomes available at `https://nick70o.github.io/calculadora-siderurgica/`.

---

## 📁 Structure

```
calculadora-siderurgica/
├── index.html   # Full calculator (HTML + CSS + JS)
└── README.md
```

---

> 💼 Freelance project (Veltro) — built to streamline real quoting workflows in the steel industry.
