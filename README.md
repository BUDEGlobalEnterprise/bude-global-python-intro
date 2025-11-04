# Bude Global OSS - Introduction to Python

A beginner-friendly web presentation about the Python programming language for students and newcomers.

**Presented by:** [Aravind Govindhasamy](https://aravind-govindhasamy.github.io)
**Community:** Bude Global (BUDE)

## 🎯 Overview

This presentation covers:
- What is Python and why it matters
- How to get started with Python
- The basic syntax and data types
- Control flow and functions
- An introduction to Object-Oriented Programming (OOP)
- and much more!

**Key Feature:** Each topic is broken down into individual slides, allowing you to:
- Explain each point thoroughly with dedicated time
- Skip slides if you're running short on time
- Deep-dive into specific areas based on audience interest

## 📁 Project Structure

The presentation uses a **JSON-based content system** for easy editing:

```
oss-101/
├── index.html              # HTML template with styles and JavaScript
├── slides.json             # Presentation content (EDIT THIS!)
├── README.md               # This file
├── assets/
│   ├── fonts/
│   │   └── Molot.otf      # BUDE brand font
│   └── images/
│       └── budeglobal_logo.png
```

**Key Benefits:**
- ✅ **Separation of Concerns**: Content (JSON) vs Layout (HTML)
- ✅ **Easy Editing**: Edit content without touching HTML/CSS
- ✅ **No Conflicts**: Multiple agents can edit separately
- ✅ **Version Control Friendly**: Clean diffs for content changes

## 🚀 Quick Start

### Option 1: Open Locally with File Protocol
1. Simply open `index.html` in your web browser
2. **Note:** Some browsers block loading JSON files via `file://` protocol
3. If slides don't load, use Option 2 below

### Option 2: Using a Local Server
If you prefer using a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

## ✏️ Editing Content

**To edit presentation content:**
1. Open `slides.json` in your editor
2. Find the topic or slide you want to edit
3. Modify the content following the JSON structure
4. Save and refresh your browser

## 📋 Presentation Structure

The presentation is divided into the following sections:

- Introduction
- What is Python?
- Why Python is Popular
- Getting Started
- Python Syntax
- Data Types
- Control Flow
- Functions
- Modules & Packages
- Error Handling
- File Handling
- Object-Oriented Programming
- Popular Libraries
- Best Practices
- Real-World Python
- Mini Projects
- Learning Resources
- Quick Quiz
- Summary
- Q&A and Thank You

## 🛠️ Technical Details

- **Framework**: Reveal.js 4.6.0
- **No Build Process**: Pure HTML/CSS/JS
- **Content System**: JSON-based dynamic slide loading
- **Font**: Molot.otf (BUDE brand font) loaded from `assets/fonts/`
- **Logo**: budeglobal_logo.png from `assets/images/`

## 📝 License

This presentation is open source. Feel free to:
- Use it for your own presentations
- Modify it for your audience
- Share it with others
- Contribute improvements

## 🤝 Contributing

Found a typo or want to improve the content?
1. Edit `slides.json` for content changes
2. Edit `index.html` for layout/styling changes
3. Test your changes in a browser
4. Share your improvements!

## 📧 Support

If you have questions or suggestions, feel free to open an issue or reach out to the community.

---

**Happy Presenting! 🚀**
