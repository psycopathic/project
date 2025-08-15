# Project Development Workflow

This repository is divided into **frontend** and **backend** sections.  
We follow a **feature-branch workflow** for both sides of the project.

---

## 📂 Branch Naming Conventions

- **Frontend:**  
Example:  
`frontend/login-page`

- **Backend:**  
Example:  
`backend/user-authentication`

---

## 🚀 Creating a New Branch

```bash
# For Backend Feature
git checkout -b backend/<feature-name>

# For Frontend Feature
git checkout -b frontend/<feature-name>

examples:

git checkout -b backend/api-events
git checkout -b frontend/dashboard-ui
