# GitHub Pages Deployment Workflow

## 🚀 Project live URL

https://ayanjyoti17.github.io/gh-deployment-workflow/

---

This project demonstrates a simple CI/CD pipeline using GitHub Actions to automatically deploy a static `index.html` file to GitHub Pages. The workflow is configured to run only when changes are pushed to the `main` branch that specifically affect the `index.html` file.

---

## 🚀 Project Page URL

https://roadmap.sh/projects/github-actions-deployment-workflow

---

## 🛠️ Instructions to Run or Replicate

This project is deployed automatically via GitHub Actions. To replicate this setup for your own project, you would follow these steps:

1.  **Create a repository** containing your static website files (e.g., `index.html`).
2.  **Create a workflow file** at `.github/workflows/deploy.yml` with the necessary steps to checkout, build, and deploy to GitHub Pages.
3.  **Configure the repository settings** by going to **Settings > Pages** and setting the **Source** for "Build and deployment" to **GitHub Actions**.
4.  **Push a change** to the files your workflow is configured to watch (in this case, `index.html`) to trigger the deployment.

---

## ✨ Key Concepts Demonstrated

* **GitHub Actions**: Automating the deployment process.
* **GitHub Pages**: Hosting the static website.
* **Continuous Deployment (CD)**: Automatically deploying new changes.
* **Conditional Workflow Triggers**: Using `on.push.paths` to ensure the workflow only runs when specific files are changed.
