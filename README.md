# 📘 **Calculator App — Python + Git Workflow**

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/calculator.png" alt="Calculator Logo"/>
</p>

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Python](https://img.shields.io/badge/python-3.10%2B-blue)
![License](https://img.shields.io/badge/license-MIT-purple)

A simple Python calculator demonstrating clean function design, automated testing, and an industry-standard Git branching workflow (feature branches, PR reviews, and version control best practices).  
Perfect repo for practicing Git, GitHub, and Python testing.

## 📑 **Table of Contents**
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Running Tests](#running-tests)
- [Git Workflow](#git-workflow)
- [Roadmap](#roadmap)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## 🔍 **Overview**
This project contains:
- A simple calculator with basic arithmetic functions.
- Automated unit tests to validate correctness.
- A clean Git workflow using feature branches + Pull Requests.
- A minimalist, beginner-friendly code structure.

It serves as a **learning project** for Git, Python, and software engineering workflows.

## ✨ **Features**
- Add, subtract, and multiply functions  
- Organized project folder structure  
- Automated test suite  
- Clean Git branching strategy  
- Easy to extend with new features  

## 📁 **Project Structure**
```
calculator/
    calculator.py
tests/
    tests.py
README.md
.gitignore
requirements.txt
```

## 🛠️ **Installation**
Clone the repository:
```bash
git clone https://github.com/Enthusiast-jefe/calculator.git
cd calculator
```

(Optional) install dependencies:
```bash
pip install -r requirements.txt
```

## ▶️ **Usage**
```python
from calculator import add, subtract, multiply

print(add(2, 3))
print(subtract(10, 4))
print(multiply(3, 5))
```

## 🧪 **Running Tests**
```bash
python tests/tests.py
```
or if using `pytest`:
```bash
pytest
```

## 🌿 **Git Workflow**
### 1. Create branch
```bash
git checkout -b feature/subtract
```

### 2. Commit changes
```bash
git add .
git commit -m "Add subtract function"
```

### 3. Push branch
```bash
git push -u origin feature/subtract
```

### 4. Open Pull Request on GitHub  
- **base:** main  
- **compare:** feature/subtract  

### 5. Merge after review

### 6. Delete branch  
```bash
git branch -d feature/subtract
```

# 🗺️ **Roadmap**
### **Phase 1 — Core Features**
- [x] Add basic operations (add, subtract, multiply)
- [ ] Add division function
- [ ] Add error handling (division by zero, invalid inputs)
- [ ] Add command-line interface (CLI)

### **Phase 2 — Testing & CI**
- [ ] Add pytest test suite
- [ ] Add GitHub Actions CI workflow
- [ ] Add coverage reports

### **Phase 3 — Project Expansion**
- [ ] Build a simple calculator API (FastAPI or Flask)
- [ ] Add Docker support
- [ ] Create GUI version (Tkinter or PyQt)

### **Phase 4 — Documentation**
- [ ] Add screenshots/GIFs of usage
- [ ] Add full developer guide
- [ ] Add contribution templates

## 🧰 **Technologies Used**
- Python 3.10+
- Unit tests (pytest or built-in unittest)
- Git & GitHub
- Optional: GitHub Actions CI

## 🤝 **Contributing**
1. Fork the repo  
2. Create a feature branch  
3. Commit your changes  
4. Push the branch  
5. Open a Pull Request  
6. Request review & merge  

## 📄 **License**
Licensed under the **MIT License**.
