# KUCC Git & GitHub Reference Library & Presentation 

Welcome to the **KUCC Git & GitHub Masterclass and Hands-On Workshop** repository! Organized by the **Kathmandu University Computer Club (KUCC)**, this project is designed specifically for first-year students to learn the fundamentals of modern version control, collaborative development, and team workflows.

This repository serves as both the backend for our live workshop assignment and a robust, permanent reference library you can bookmark and use for your semester projects.

---

## 📂 Repository Contents


The workspace contains two core assets:

1. **`index.html` (Interactive Reference Library)**
   * A beautiful, interactive dashboard built with Tailwind CSS, custom dark theme colors, and responsive cards.
   * Includes step-by-step instructions for today's live assignment mission.
   * Categorized database of real-world Git commands (Setup, Daily Pipeline, Branching, Stashing, History Inspection, and Safe Undos) with one-click copy-to-clipboard functionality.
   * A local sandbox/playground showcasing contributor badges.

2. **`git_github_masterclass_unified.html` (Presentation Slide Deck)**
   * A fully customized, modern glassmorphic presentation deck.
   * Explains version control history, Git architecture, local/remote data transportation flows, branch release strategies, Conventional Commits, merge conflict troubleshooting, and team practices.
   * Use arrow keys or the built-in control buttons to navigate the slides.

---

## 🎯 Today's Workshop Mission (Live Lab)

To complete your workshop assignment, follow this standard collaborative workflow:

### Step 1: Fork & Star ⭐
1. Click the **Star** button at the top-right of this repository to support KUCC.
2. Click the **Fork** button to generate your own independent copy of this project under your personal GitHub profile.

### Step 2: Clone Locally 💻
Open your terminal and clone down your unique forked copy to your local machine:
```bash
git clone https://github.com/YOUR-USERNAME/git-and-github-workshop.git
```

### Step 3: Modify Code & Add Your Profile Badge 📝
1. Open the project folder in VS Code:
   ```bash
   cd git-and-github-workshop
   code .
   ```
2. Open `index.html` and search for the `<!-- EDIT ME -->` comment block.
3. Duplicate one of the profile card structures and customize it with your own name, roll number, and division, then append it inside the **Playground** column:
   ```html
   <div class="bg-slate-900/60 border border-devBorder p-3 rounded-lg flex items-center justify-between hover:border-slate-700 transition">
       <div>
           <h4 class="font-medium text-white text-sm">Your Full Name</h4>
           <span class="text-xs text-slate-500 font-mono">Roll: XX (CS-1st Yr)</span>
       </div>
       <span class="text-xs bg-devBlue/10 text-devBlue border border-devBlue/20 px-2 py-0.5 rounded font-medium">Contributor</span>
   </div>
   ```

### Step 4: Commit & Pull Request 🚀
Stage your additions, snapshot them using a descriptive commit message, push them to your fork, and open a Pull Request back to our repository:
```bash
# Verify modified files
git status

# Stage changes
git add index.html

# Commit using conventional style
git commit -m "feat: add [Your Name] profile badge to playground"

# Push to your fork's main branch
git push origin main
```
Go to your fork's GitHub page, click **Contribute**, and initiate a new **Pull Request** back to the primary repository!

---

## 📚 Essential Git Commands Quick Reference

Here are the standard commands documented inside the interactive dashboard:

| Category | Commands |
|---|---|
| **Setup & Identity** | `git config --global user.name` \| `git config --global user.email` \| `git init` \| `git clone` \| `git remote` |
| **Daily Workflow** | `git status` \| `git add` \| `git commit -m` \| `git push` \| `git pull` |
| **Branch Management** | `git checkout -b` \| `git switch` \| `git branch` \| `git merge` |
| **The Stash Store** | `git stash` \| `git stash list` \| `git stash pop` \| `git stash apply` |
| **Inspection & Blame** | `git log --oneline --graph` \| `git diff` \| `git diff --staged` \| `git blame` |
| **The Panic Buttons** | `git restore` \| `git reset --hard` \| `git revert` |

---

## 🖥️ How to Run & View Locally

Since the presentation slides and the reference library are unified single-file HTML implementations, they require no heavy installation or build server setup. 

To open them:
*   **Interactive Reference Dashboard**: Double-click `index.html` inside your file manager (or run `open index.html` / `xdg-open index.html` from your terminal).
*   **Presentation Slides**: Double-click `git_github_masterclass_unified.html` in your file explorer to launch the presentation.

---

*Organized with ❤️ by Kathmandu University Computer Club (KUCC) — Department of Computer Science and Engineering.*
