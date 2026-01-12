# Contributing to Basic-Vanilla-Sass

First off, thank you for helping! To keep the code clean and the history readable, please follow these guidelines.

## 🚀 How to Contribute
1. **Branching:** Create a new branch for every task.
   - `git checkout -b feat/your-feature-name` or `fix/issue-description`
2. **Coding Standards:**
   - Use **BEM** (Block-Element-Modifier) for CSS classes.
   - Place partials in the correct `7-1` folder structure.
   - Ensure your SCSS compiles without errors (the GitHub Action will check this!).
3. **Commit Messages:** We use simplified Conventional Commits:
   - `feat:` for new additions.
   - `fix:` for bug fixes.
   - `style:` for styling changes that don't change logic.

## 📥 Pull Request Process
- Open a PR against the `master` branch.
- Fill out the provided PR Template.
- Wait for a review from **@Tchetta**. 
- You cannot merge your own PR; only the project owner can hit the "Merge" button.

## 🏷️ Versioning
Versions are managed by the project owner using `npm version`. Please do not update the `version` field in `package.json` yourself.