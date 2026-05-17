# Git-Repo
---

# Follow steps below after the content.

---

##  COPY THIS FULL CONTENT

````md
# Git Full Hands-on Lab Guide

## 1. Git Configuration
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@gmail.com"
````

---

## 2. Create / Clone Repository

### Create local repo

```bash
mkdir Practice-repo
cd Practice-repo
git init
```

### OR clone GitHub repo

```bash
git clone https://github.com/username/repo-name.git
cd repo-name
```

---

## 3. Create README.md

```bash
notepad README.md
```

### Content:

```md
# My Git Project
This is my Git practice project.
```

---

## 4. Git Status

```bash
git status
```

---

## 5. Add Files

```bash
git add .
```

---

## 6. Commit Changes

```bash
git commit -m "Initial commit"
```

---

## 7. Connect GitHub Repo

```bash
git remote add origin https://github.com/username/repo-name.git
```

---

## 8. Push to GitHub

```bash
git push -u origin main
```

---

## 9. Create Branch

```bash
git checkout -b feature-login
```

---

## 10. Edit File

```bash
notepad README.md
```

Add:

```md
## Login feature added
```

---

## 11. Commit Branch Changes

```bash
git add .
git commit -m "Added login feature"
```

---

## 12. Push Branch

```bash
git push origin feature-login
```

---

## 13. Pull Request (GitHub)

---

## 14. Merge PR

* Click "Merge pull request"
* Confirm merge

---

## 15. Update Local Repo

```bash
git checkout main
git pull origin main
```

---

## Git Flow Summary

```
clone/init → add → commit → push → branch → edit → commit → push branch → PR → merge
```

```

---

#  HOW TO DOWNLOAD AS .MD FILE

## ✔ STEP 1
Open Notepad

## ✔ STEP 2
Paste the above content

## ✔ STEP 3
Click:
```

File → Save As

```

## ✔ STEP 4
Save like this:

```

File name: README.md
Save as type: All Files
Encoding: UTF-8

```

---

#  DONE
  
---  

```
