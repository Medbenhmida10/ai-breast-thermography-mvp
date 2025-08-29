# Contributing Guidelines

Thank you for contributing to the **Breast Thermography MVP** project!  
This document outlines the workflow and best practices for collaboration.

---

## 🛠️ Development Workflow

1. **Fork & Clone**  
   - Fork the repo on GitHub and clone your fork locally.  
   - Keep your fork synced with `main`.

2. **Branching Strategy**
   - Use `main` for stable code.  
   - Create feature branches:
     ```
     feature/clahe-preprocessing
     feature/resnet18-training
     fix/data-loader
     doc/add-metrics-report
     ```
   - Branch names: `feature/`, `fix/`, or `doc/` + short description.

3. **Commits**
   - Write clear, descriptive commit messages:
     ```
     feat: add CLAHE preprocessing to pipeline
     fix: corrected dataset path in dataloader
     docs: update README with usage instructions
     ```
   - Use **present tense** (“add” not “added”).

4. **Pull Requests (PRs)**
   - Open PRs against `main`.  
   - Link relevant **Issues**.  
   - Include:
     - Short description of changes
     - Any relevant screenshots/plots
     - Checklist of what was tested

---

## 📌 Issues & Projects

- Use **Issues** for:
  - New features
  - Bug reports
  - Questions
- Tag issues with:
  - `enhancement`
  - `bug`
  - `documentation`
  - `discussion`

- Use the **Projects board** (Kanban) for:
  - Organizing To Do / In Progress / Done
  - Tracking milestones

---

## 📊 Data Guidelines
- Do **not** upload sensitive/private datasets.  
- Use only:
  - Public datasets (e.g., DMR-IR, DMR-Thermal)
  - Synthetic/sample data
- Keep large files (>50MB) in Google Drive, not GitHub.

---

## 🧪 Code Style & Testing
- Python: follow **PEP8** style.
- Add inline comments for clarity.
- Document major functions with docstrings.
- Test before pushing:
  ```bash
  pytest tests/
