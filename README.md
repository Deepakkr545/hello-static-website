
# 🌐 Static Website Deployment with Git Best Practices

## ✅ Task 4: Build a Version-Controlled DevOps Project with Git

### 🎯 Objective
Manage and deploy a static website using Git and GitHub by applying DevOps version control best practices including branching, pull requests, tagging, and CI/CD automation.

---

## 🛠 Tools Used
- **Git** – Version control system for tracking code changes
- **GitHub** – Remote repository for collaboration
- **GitHub Pages** – Hosting the static site
- **GitHub Actions** – CI/CD automation for deployment

---

## 📁 Project Structure

📦hello-static-website/
┣ 📂website/
┃ ┣ 📜index.html
┃ ┗ 📜style.css
┣ 📜.gitignore
┣ 📜README.md
┗ 📜.github/workflows/static.yml

---

## 🚀 Deployment Steps

1. **Initialize Git repository**

   git init
   git remote add origin https://github.com/Deepakkr545/hello-static-website.git
   git add .
   git commit -m "Initial commit"
   git push -u origin main


2. **Create development workflow**
  
   git checkout -b dev

3. **Create a feature branch for homepage**


   git checkout -b feature/homepage
   # Make changes to index.html and style.css
   git add .
   git commit -m "Add stunning homepage design"
   git push origin feature/homepage
  

4. **Open Pull Requests**

   * Merge `feature/homepage` → `dev`
   * Merge `dev` → `main` (via Pull Requests on GitHub)

5. **Create a Git tag for versioning**


   git tag -a v1.0 -m "Initial site release"
   git push origin v1.0


6. **Enable GitHub Pages**

   * Go to **Repo Settings → Pages**
   * Source: Deploy from GitHub Actions



## 🌍 Live Website

🔗 [Visit Live Site](https://deepakkr545.github.io/hello-static-website)


## 📌 Version

* **v1.0** – Initial stable release



## 📝 Author

**Deepak Kumar**
[GitHub](https://github.com/Deepakkr545)

