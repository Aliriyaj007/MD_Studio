# MD Studio

**The zero-overhead, browser-native converter for Rich Text and GitHub Flavored Markdown.**

---

## 💡 Why This Exists

Technical writers and developers often waste time switching between visual editors (Google Docs, Notion) and code editors (VS Code) just to format documentation properly.

Most existing online converters are either:

* Filled with ads
* Require account creation
* Send your content to backend servers
* Or produce broken Markdown

Before **MD Studio**, users had to manually convert tables, lists, and formatted text—or rely on AI tools that often hallucinate Markdown syntax.

> **“This tool exists because documentation should be about writing, not fighting syntax or privacy-invasive web apps.”**

---

## 🛠️ What It Does

* **Bidirectional Sync** – Real-time conversion between WYSIWYG and Markdown
* **GFM Support** – Native GitHub Flavored Markdown (tables, task lists, strikethroughs)
* **Privacy First** – 100% client-side; no data leaves your browser
* **Visual Polish** – 7 built-in themes (Dracula, Cyberpunk, Solarized, etc.)
* **Zero Dependencies** – No Node.js, no build steps, no installation

### ❌ What It Does NOT Do

* No cloud storage
* No collaboration
* No backend processing

MD Studio is a **stateless, high-speed conversion utility**.

---

## 🔄 Before vs After

| Scenario       | Manual Workflow (Before)   | MD Studio (After)        |                       |
| -------------- | -------------------------- | ------------------------ | --------------------- |
| Table Creation | Manually writing `         | `and`---`                | Auto-generated tables |
| Link Handling  | Syntax errors with nesting | Visual hyperlink support |                       |
| Drafting       | Switching apps repeatedly  | Live preview             |                       |
| Time Spent     | 5–10 minutes per section   | Under 60 seconds         |                       |

---

## 📋 Sample Output

When you create a table and a code block, MD Studio generates clean GFM:

### System Requirements

| Component | Minimum | Recommended |
| --------- | ------- | ----------- |
| RAM       | 4GB     | 8GB         |

```bash
# Clone the repository
git clone https://github.com/Aliriyaj007/MD_Studio.git
```

---

## 🚀 Installation & Usage

### ✅ Option 1: Direct Download (Recommended)

1. Download `index.html`
2. Open it in any modern browser

### ✅ Option 2: GitHub Pages

Access the live version:

```
https://aliriyaj007.github.io/MD_Studio/
```

### ✅ Option 3: Clone Repository

```bash
git clone https://github.com/Aliriyaj007/MD_Studio.git
cd MD_Studio
open index.html
```

---

## ⚡ One-Command Local Server

If Python is installed:

```bash
python3 -m http.server 8000
```

Then open:

```
http://localhost:8000
```

---

## 🎯 Use Cases

* 📘 Quick README creation
* 🔁 Content migration from Word/Notion
* 🧪 Markdown validation & preview
* ✈️ Offline documentation editing

---

## 🗺️ Roadmap

* [x] GFM table support
* [x] Multi-theme UI
* [x] Client-side export (.md / .txt)
* [ ] Drag-and-drop file import
* [ ] YAML frontmatter support
* [ ] Mermaid.js diagrams

---

## ⚠️ Limitations

* Image uploads are URL-only
* CSS styling is not preserved in Markdown
* No auto-save or version history

---

## 🤝 Contributing

Contributions are welcome and appreciated.

1. Fork the project
2. Create a feature branch
3. Commit your changes
4. Push to GitHub
5. Open a Pull Request

---

## 📜 License

Licensed under the **MIT License**. See `LICENSE` for details.

---

## 👤 Author

**Riyajul Ali**
GitHub: [@Aliriyaj007](https://github.com/Aliriyaj007)
Email: [aliriyaj007@protonmail.com](mailto:aliriyaj007@protonmail.com)
LinkedIn: [https://linkedin.com/in/Aliriyaj007](https://linkedin.com/in/Aliriyaj007)

> *“Built to remove friction, not add features.”*
> 
