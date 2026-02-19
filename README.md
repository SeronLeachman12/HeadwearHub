# 🧢 Headwear Hub Overhaul

A premium, modern e-commerce experience for headwear enthusiasts. This project has been overhauled from static HTML to a dynamic **Express.js** application using **EJS** templates and a sleek **Vanilla CSS** design system.

---

## 🛠️ Tools & Prerequisites

To get this project running on your local machine, you'll need the following tools:

### 1. Node.js & NPM
Node.js is the runtime that executes JavaScript on your server.
- **Download**: [nodejs.org](https://nodejs.org/) (Recommend the **LTS** version).
- **Verify**: Open your terminal and type `node -v` and `npm -v`.

### 2. Git
Used for version control and managing your code history.
- **Download**: [git-scm.com](https://git-scm.com/)
- **Verify**: Type `git --version` in your terminal.

### 3. Integrated Development Environment (IDE)
We recommend **Visual Studio Code** for the best development experience.
- **Download**: [code.visualstudio.com](https://code.visualstudio.com/)

---

## 🚀 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/SeronLeachman12/HeadwearHub.git
   cd HeadwearHub
   ```

2. **Install Dependencies**
   This installs Express.js and EJS as defined in `package.json`.
   ```bash
   npm install
   ```

3. **Start the Application**
   ```bash
   npm start
   ```
   The site will be available at `http://localhost:3000`.

---

## 🌿 Git Version Control

### Changing Branches
Branches allow you to work on new features without affecting the main code.

- **View all branches**: `git branch`
- **Create and switch to a new branch**: `git checkout -b feature-name`
- **Switch back to an existing branch**: `git checkout main`
- **Merge a branch into main**:
  1. `git checkout main`
  2. `git merge feature-name`

---

## 📑 Git Cheat Sheet

| Command | Description |
| :--- | :--- |
| `git status` | See which files are changed/staged |
| `git add .` | Stage all changes for the next commit |
| `git commit -m "Your Message"` | Save your staged changes with a descriptive note |
| `git push origin branch-name` | Send your local commits to the online repository |
| `git pull origin branch-name` | Fetch and download content from the remote repo |
| `git log --oneline` | View a condensed history of your commits |
| `git diff` | Show changes between your working directory and the last commit |
| `git stash` | Temporarily save changes you aren't ready to commit |

---

## 🎨 Project Structure

- `app.js`: The heart of the application (Express server).
- `views/`: EJS templates (HTML with logic).
- `public/`: Static assets like CSS and JS.
- `package.json`: Project manifest and dependency list.

---

*Enjoy the overhaul! Elevate your style with Headwear Hub.* 🧢✨
