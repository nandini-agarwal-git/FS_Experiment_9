# 🚀 CI/CD Pipeline using GitHub Actions

## 🎯 Objective
Automate testing and deployment for a React app using **GitHub Actions**.

## 📁 Project Structure
- `.github/workflows/main.yml` → Workflow configuration
- `src/` → React app source files
- `public/` → Static assets

## ⚙️ Workflow Summary
1. Runs automatically on every push to `main`.
2. Installs dependencies.
3. Runs tests.
4. Builds the app.
5. Deploys to GitHub Pages (if configured).

## 🧠 Deployment Setup
1. Go to your repository **Settings → Pages**.
2. Set the branch to `gh-pages` and folder to `/ (root)`.
3. Commit and push — your app will deploy automatically.
4. Check the **Actions tab** for workflow progress.

## ✅ Expected Output
- A running CI/CD pipeline visible in GitHub’s **Actions tab**.
- Automatic deployment after successful build.
- Live React app on GitHub Pages.
