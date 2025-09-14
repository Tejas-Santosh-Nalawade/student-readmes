# 🎓 Student GitHub Profiles Repository

Welcome to **student-readmes** 🚀  
This repo showcases personalized GitHub profile READMEs from students.  

---

## 📌 Steps to Contribute


---

### 1️⃣ Prepare Your Profile
1. **Fork** this repository 🍴
2. Go to the `/students/` folder
3. Copy `template.yml` → create a new file named **<your-github-username>.yml**

### 2️⃣ Add Your Details
4. Fill in your details (name, roll number, skills, dream company)
5. **Commit & Push** your changes

###  Submit & Celebrate
6. **Create a Pull Request (PR)**
7. ⭐ Don’t forget to **Star this repo** after your PR

---


### 3️⃣ Configure Your Personal Access Token (PAT)

1. Go to **Settings → Developer settings → Personal access tokens → Tokens (classic)**.  
2. Generate a token with **`repo` scope**.  
3. Go to your fork → **Settings → Secrets → Actions → New repository secret**.  
4. Name it: `STUDENT_PAT`  
5. Paste your token.  

> This allows the workflow to create your **personal profile repo automatically**.

---

### 4️⃣ Commit & Push

- Commit your YAML file.  
- Push to your fork (**not the main branch** is preferred, e.g., `add-my-profile`).  

---

### 5️⃣ Create a Pull Request (PR)

- Click **Compare & Pull Request** on your fork.  
- Target branch: `student-readmes/main`.  
- Add description (optional): "Add my profile".  
- Submit the PR.

---

### 6️⃣ PR Validation

- GitHub Action automatically checks your template:  
  - Correct folder (`/students/`)  
  - YAML syntax valid  
  - All required fields filled  
  - Username format correct  

- If mistakes exist → workflow **comments on your PR**.  
- Fix them and push again.

---

### 7️⃣ Merge PR

- Teacher/Admin merges the PR once validation passes.

---

### 8️⃣ Automatic Personal Repo Creation

- Workflow triggers after merge:  
  - Checks if personal repo `<github-username>-profile` exists.  
  - Creates it if not.  
  - Adds `README.md` with your profile information.  
  - If exists → updates your README.

---
 
###  9️⃣ Central Showcase Update

- Another workflow updates this repo’s `README.md` automatically:  
  - Adds you to **Contributors list**.  
  - Shows **preview of your profile** in the Showcase section.

---

### 🔟 Celebrate! 🎉

- Your **personal GitHub repo** is live.  
- You are listed in the **central repo showcase**.  
- Recruiters can see your **skills and GitHub stats**.  
- You learned **fork → commit → PR → workflow → open-source contribution**.

---

### 📝 Optional Steps

- ⭐ Star this repository.  
- Customize your personal README further.  
- Share your personal repo link on LinkedIn/portfolio.


## 🏆 Contributors

The following students have added their profiles 👇 (auto-updated):

<!-- CONTRIBUTORS-LIST:START -->
<!-- CONTRIBUTORS-LIST:END -->

---

## 🎨 Student Showcases

Here are some student profile previews 👇 (auto-updated)

<!-- SHOWCASE-LIST:START -->
<!-- SHOWCASE-LIST:END -->
