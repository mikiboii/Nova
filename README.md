1️⃣ Initialize git (if not already)

From your project root (C:\Users\miki\Downloads\Programs\Pr_plugin\FX Studio):

git init 

2️⃣ Set up .gitignore

Create a .gitignore file in the project root with entries like this:

3️⃣ Add remote 
git remote add origin https://github.com/mikiboii/Nova.git
 4️⃣ Add files 
 git add . 
 5️⃣ Commit 
 git commit -m "Initial commit of Nova" 


 6️⃣ Push to GitHub 

 git branch -M main 
 git push -u origin main



******* only on new gits

git push -u origin main --force
*******

Regular commits
git add .
git commit -m "added readme"
git push

new version commit
Modify your code as usual.

Stage and commit your changes:

git add . git commit -m "new ae support"

Tag the new version (like v1.1):

git tag -a v1.0.2 -m "Version 1.0.2 – comment "

Push the tag to GitHub:

git push origin v1.0.2

Run dev server

npm run web



$env:NODE_OPTIONS="--openssl-legacy-provider"









---

# 🚀 Nova Project – Git Workflow Guide

## 📦 1. Initialize Git (first time only)

Run this in your project root:

```bash
git init
```

---

## 📁 2. Create `.gitignore`

Create a `.gitignore` file in the project root to exclude unnecessary files:

Example:

```
node_modules/
dist/
.env
.DS_Store
```

---

## 🔗 3. Connect to GitHub (remote)

```bash
git remote add origin https://github.com/mikiboii/Nova.git
```

---

## 📥 4. Add files

```bash
git add .
```

---

## 💾 5. First commit

```bash
git commit -m "Initial commit of Nova"
```

---

## 🚀 6. Push to GitHub (first push only)

Set branch and push:

```bash
git branch -M main
git push -u origin main
```

👉 After this, your branch is linked to GitHub (upstream is set)

---

# 🔄 Regular Workflow (daily development)

After making changes:

```bash
git add .
git commit -m "your update message"
git push
```

Example:

```bash
git commit -m "added new AE support"
git push
```

---

# 🏷️ Versioning (Tags / Releases)

Use tags to save stable versions of your project.

## Create a version tag

```bash
git tag -a v1.0.2 -m "Version 1.0.2 - added new features"
```

## Push the tag to GitHub

```bash
git push origin v1.0.2
```

## Push all tags (optional)

```bash
git push origin --tags
```

---

# ⚠️ Force push (USE CAREFULLY)

Only use this if you KNOW what you're doing (like rewriting history):

```bash
git push -u origin main --force
```

⚠️ This can overwrite GitHub history and break collaboration.

---

# 🧪 Run Dev Server

```bash
npm run web
```

---

# ⚡ Fix for OpenSSL error (if needed)

If you see crypto/OpenSSL errors in Node.js:

```bash
$env:NODE_OPTIONS="--openssl-legacy-provider"
```

---

# 🧠 Summary Workflow

### First setup:

```bash
git init
git remote add origin <repo>
git add .
git commit -m "init"
git push -u origin main
```

### Normal updates:

```bash
git add .
git commit -m "message"
git push
```

### Version release:

```bash
git tag -a v1.0.0 -m "version"
git push origin v1.0.0
```

---


