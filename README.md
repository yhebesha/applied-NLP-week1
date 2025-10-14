# Session 1 — Course Applied NLP

This repository contains the materials for **Session 1** of *Applied NLP*.  
- Slides: see [`slides/`](./slides/) folder  
- Notebooks: see [`notebooks/`](./notebooks/) folder 
---

### Session Outline

- Course overview and expectations

- “Words as data”: treating literature quantitatively

- From Al-Kindi’s frequency analysis to Shannon’s information theory

- Measuring text features: word frequency, entropy, punctuation, pronouns, color words, gender representation

- Examples from Nabokov’s Favorite Word Is Mauve

- Bechdel Test as a measurable criterion

### Hands-On

- Set up your GitHub account and accept the invite to the course organization

- Fork and clone today’s starter repository

- Initialize your personal project repository for the semester

### Group Activity

- Choose your author and working language (solo or small team)

- Draft an initial research question (e.g., sentiment over chapters, topic trends, stylistic fingerprinting)

### Homework

- Short reflection: why this author/text? what you plan to measure

- Complete repo setup and make your first commit (README + checklist)

### Key Takeaways

- Texts can be profiled with simple, reproducible metrics

- Historical ideas (frequency analysis) connect directly to modern NLP (information theory)

- A clear author choice and research question will guide all subsequent sessions

---
## 🚀 Environment Setup

Before starting, please **fork this repository** and create a fresh Python virtual environment.  
All required libraries are listed in `requirements.txt`.

> ⚠️ If you encounter errors during `pip install`, try removing the version pinning for the failing package(s) in `requirements.txt`.  
> On Apple M1/M2 systems you may also need to install additional system packages (the “M1 shizzle”).

---

### macOS / Linux (bash/zsh)

```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate

# Upgrade pip and install dependencies
pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (PowerShell)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
.venv\Scripts\Activate.ps1

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (Git Bash)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/Scripts/activate

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

You’re now ready to run the session notebooks!

Deactivate the environment when you’re done:
```bash
deactivate
```


