# Xalal Python Theme

🎨 **Xalal Python Theme** is a clean, modern, and elegant VS Code theme specially crafted for Python developers who love readability, performance, and native language flair.

---

## ✨ Features

- 🔵 Based on **GitHub Dark Colorblind** syntax colors
- 🅱️ **Bengali heading font** (`Noto Serif Bengali`) for native comfort
- 🔍 Larger and clearer font size (16px recommended)
- 🌫️ Transparent editor background
- 🎛️ Custom scrollbar and sidebar styles
- 🐍 Python-optimized coloring for `def`, `class`, `self`, etc.
- 📦 Lightweight, responsive, and distraction-free

---

## 🛠️ Recommended Settings

To enjoy full experience, add this to your `settings.json`:

```json
{
  "editor.fontFamily": "'Noto Serif Bengali', 'Fira Code', Consolas, 'Courier New', monospace",
  "editor.fontSize": 16,
  "editor.fontLigatures": true,
  "workbench.colorCustomizations": {
    "editor.background": "#00000040",
    "scrollbarSlider.background": "#9994",
    "scrollbarSlider.hoverBackground": "#aaa6",
    "scrollbarSlider.activeBackground": "#bbb9",
    "sideBar.background": "#1e1e1e80",
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "entity.name.function", // Function/method names
          "entity.name.method", // Method names
          "variable.parameter.function.language.special.self.python", // Python 'self' keyword
          "storage.type.function.python", // def 
          "storage.type.class.python", // class
          "support.type.python",
          "keyword.control.flow.python"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  },
}
}

