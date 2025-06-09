# Printable Handout: Beginner Coding Workshop  
**Topic:** Building a Calculator with VS Code, GitHub & Copilot  
**For:** New Computer Science Students  
**Duration:** 3 Sessions (1 hour each)  

---

## Session 1: Setting Up Your Environment

### 1. Install Visual Studio Code
- Visit [https://code.visualstudio.com/](https://code.visualstudio.com/)
- Download and install for your operating system (Windows/Mac/Linux).
- Open VS Code after installation.

### 2. Install Git
- Visit [https://git-scm.com/downloads](https://git-scm.com/downloads)
- Download and install Git.
- Open a terminal and enter: `git --version` (should show installed version).

### 3. Create a GitHub Account
- Visit [https://github.com/](https://github.com/)
- Click **Sign Up** and follow instructions.

### 4. Install Node.js (for JavaScript projects)
- Visit [https://nodejs.org/](https://nodejs.org/)
- Download the LTS version and install.

### 5. Install GitHub Copilot in VS Code
- In VS Code, open the Extensions sidebar (Ctrl+Shift+X)
- Search for “GitHub Copilot” and click **Install**

### 6. Sign in to GitHub in VS Code
- Click the Accounts icon (bottom left)
- Select **Sign in with GitHub** and follow prompts

---

## Session 2: Creating a Repository & Starting Your Project

### 1. Create a New Repository on GitHub
- Go to [https://github.com/](https://github.com/)
- Click the **+** icon (top right), select **New repository**
- Name: `calculator-project`
- Description: “A simple calculator app”
- Select **Public** or **Private**
- Click **Create repository**

### 2. Clone the Repository Locally
- Click the green **Code** button in your repo, copy the URL (HTTPS)
- In VS Code, open the command palette (Ctrl+Shift+P)
- Type `Git: Clone`, paste the URL, and select a folder to save
- Open the folder in VS Code

### 3. Initialize Your Calculator Project
- Create a new folder called `calculator`
- Inside, create:
  - `index.html`
  - `style.css`
  - `script.js`

#### Sample index.html
```html
<!DOCTYPE html>
<html>
<head>
  <title>Simple Calculator</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="calculator">
    <input type="text" id="display" disabled />
    <div class="buttons">
      <!-- Buttons go here -->
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
```

---

## Session 3: Coding with Copilot & Collaboration

### 1. Using Copilot to Build the Calculator
- In `script.js`, type a comment like:  
  `// Add event listeners to calculator buttons`
- Press `Tab` or `Ctrl+Enter` to accept Copilot’s suggestion.

#### Example Prompts for Copilot
- `// Create calculator buttons for numbers and operations`
- `// Implement function to handle button clicks`
- `// Display results in the input field`
- `// Clear display when C is pressed`
- `// Add keyboard support for calculator`

_Tip: If Copilot’s suggestion isn’t right, keep typing or rephrase your comment._

### 2. Commit and Push Your Changes
- Go to the Source Control tab in VS Code
- Enter a commit message (e.g., “Initial calculator UI”)
- Click the checkmark to commit
- Click the three dots (`...`), select **Push**

### 3. Collaborating on GitHub
- Invite collaborators via repo **Settings > Collaborators**
- Create a feature branch:  
  ```sh
  git checkout -b feature/your-feature
  ```
- Commit and push as before

---

## Checklist

- [ ] VS Code installed
- [ ] Git and Node.js installed
- [ ] GitHub account created
- [ ] Repository created & cloned locally
- [ ] Project files set up
- [ ] Copilot enabled & used for code suggestions
- [ ] Code committed & pushed to GitHub

---

## Useful Resources

- [VS Code Docs](https://code.visualstudio.com/docs)
- [GitHub Docs](https://docs.github.com/)
- [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- [HTML Calculator Tutorial](https://www.w3schools.com/howto/howto_js_calculator.asp)

---

**End of Printable Handout**