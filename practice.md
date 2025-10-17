# 🧩 Git Practice Guide

Welcome! This document will guide you through basic Git and GitHub practice tasks.  
You can complete them step by step to get familiar with version control workflows.

---

## 🛠️ 1. Setup

1. **Install Git**  
   - [Download Git](https://git-scm.com/downloads)  
   - Configure your user info:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "your_email@example.com"
     ```

2. **Clone the repository**
  ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
  ```

---

## ✏️ 2. Basic Git Commands

Try these in order:

| Goal                | Command Example                     |
| ------------------- | ----------------------------------- |
| Check your branch   | `git branch`                        |
| Create a new branch | `git checkout -b feature/hello-git` |
| Add a new file      | `echo "Hello Git!" > hello.txt`     |
| Stage changes       | `git add hello.txt`                 |
| Commit changes      | `git commit -m "Add hello.txt"`     |
| Push to GitHub      | `git push origin feature/hello-git` |

Then go to GitHub and **create a Pull Request (PR)** to merge your branch into `main`.

---

## 🧠 3. Practice Exercises

1. **Create a new branch**

   * Name it `feature/<your-name>`.
   * Add a file named `<your-name>.md` that includes a short introduction about yourself.

2. **Modify an existing file**

   * Edit `practice.md` to add your name to the "Contributors" section.

3. **Fix a conflict**

   * Pair with a friend or classmate.
   * Both of you edit the same line in the same file on separate branches.
   * Try merging and resolve the merge conflict.

---

## 👥 5. Contributors

Add your name below once you’ve completed your practice:

* [ ] Your Name
* [ ] (Add more names here!)

---

## 💡 Tips

* Keep commit messages **clear and meaningful**.
  Example:

  ```
  feat: add new greeting feature
  fix: correct typo in readme
  docs: update practice instructions
  ```
* Always pull the latest code before starting a new feature:

  ```bash
  git pull origin main
  ```

---

Happy coding 🎉
If you get stuck, check the [Git Handbook](https://guides.github.com/introduction/git-handbook/).


