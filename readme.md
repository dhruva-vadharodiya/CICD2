# 🚀 GitHub Pages Deployment using Static HTML Workflow

This project demonstrates how to deploy a static HTML website directly from GitHub using **GitHub Pages** and **GitHub Actions** without using any local development tools such as VS Code.

## 📌 Deployment Workflow

### 1. Create a GitHub Repository

Start by creating a new repository on GitHub to host your project files.

### 2. Add Static Website Files

Create your website files directly in the GitHub web editor, such as:

* `index.html`

### 3. Configure GitHub Pages

Navigate to **Settings → Pages** and select **GitHub Actions** as the deployment source.

### 4. Select the Static HTML Workflow

Go to the **Actions** tab and choose the **Static HTML** workflow.

GitHub automatically creates a workflow file:

```text
.github/workflows/static.yml
```

This workflow defines how the deployment process will run automatically.

### 5. Commit the Workflow

Commit the generated workflow file to your repository.

### 6. Automatic Deployment Starts

Once the commit is pushed, GitHub Actions automatically executes the workflow.

The workflow performs the following steps:

* ✅ Checks out the repository
* ✅ Prepares the deployment environment
* ✅ Uploads the static website files as an artifact
* ✅ Deploys the artifact to GitHub Pages

### 7. Website Goes Live

After the workflow completes successfully, GitHub Pages publishes the website and generates a live URL.

Example:

```text
https://your-username.github.io/repository-name
```

## ⚡ Key Features

* Fully automated deployment
* No VS Code or local setup required
* Free static website hosting
* Continuous Deployment (CI/CD)
* Automatic redeployment whenever changes are committed

## 🔄 Deployment Flow

```text
Create Repository
        │
        ▼
Add HTML Files
        │
        ▼
Choose Static HTML Workflow
        │
        ▼
Workflow Created (.github/workflows/static.yml)
        │
        ▼
Commit Changes
        │
        ▼
GitHub Actions Runs Automatically
        │
        ▼
Deploy to GitHub Pages
        │
        ▼
Live Website 🚀
```

## 🎯 Learning Outcome

This project helped me understand how GitHub Actions automates the deployment process and how GitHub Pages hosts static websites with minimal configuration. It also introduced the basic concepts of Continuous Integration (CI) and Continuous Deployment (CD) using GitHub's built-in automation.
