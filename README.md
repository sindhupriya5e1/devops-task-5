# Task 5: Host a Static Website with GitHub Pages

## 1. Project Overview

This project was completed as part of my Cloud & DevOps internship. The objective was to create a static website using HTML and CSS, upload the source code to GitHub, and publish the website using GitHub Pages.

The website presents my professional profile, technical skills, projects, and contact links as an aspiring Cloud & DevOps Engineer.

## 2. Project Objectives

* Create a static website using HTML and CSS.
* Manage source code using Git and GitHub.
* Host the website using GitHub Pages.
* Configure deployment from the `main` branch and root directory.
* Verify the deployment workflow using GitHub Actions.
* Understand the basic website hosting and version-control workflow.

## 3. Live Website and Repository

**Live Website:**
https://sindhupriya5e1.github.io/devops-task-5/

**GitHub Repository:**
https://github.com/sindhupriya5e1/devops-task-5

**GitHub Actions:**
https://github.com/sindhupriya5e1/devops-task5-/actions

## 4. Technologies Used

| Technology     | Purpose                                           |
| -------------- | ------------------------------------------------- |
| HTML5          | Defines the website structure and content         |
| CSS3           | Styles the website and provides responsive layout |
| Git            | Tracks source-code changes                        |
| GitHub         | Hosts the source-code repository                  |
| GitHub Pages   | Publishes the static website                      |
| GitHub Actions | Displays and runs the deployment workflow         |

## 5. Website Features

* Personal introduction and career objective
* Cloud and DevOps technical skills
* Project descriptions
* GitHub profile link
* LinkedIn profile link
* Navigation links for About, Skills, Projects, and Contact
* Styled layout for presenting a professional portfolio

## 6. Technical Skills Featured

* **Cloud:** AWS EC2, S3, IAM, and VPC
* **Operating Systems:** Linux and Ubuntu
* **Version Control:** Git and GitHub
* **CI/CD:** Jenkins and GitHub Actions
* **Containers:** Docker and Kubernetes
* **Infrastructure as Code:** Terraform
* **Programming and Databases:** Python and MySQL

## 7. Project Structure

```text
devops-task5-github-pages/
├── index.html
├── style.css
└── README.md
```

* `index.html` contains the website content and structure.
* `style.css` controls the website's appearance and layout.
* `README.md` documents the project, setup, deployment, and interview preparation.

## 8. Implementation and Deployment Steps

### Step 1: Create the website files

Created `index.html` for the portfolio content and `style.css` for the website styling.

### Step 2: Initialize Git

```bash
git init
git branch -M main
```

### Step 3: Add and commit the project files

```bash
git add index.html style.css
git commit -m "Add Task 5 static website"
```

### Step 4: Create a GitHub repository

Created a public repository named `devops-task5-github-pages`.

### Step 5: Connect the local repository to GitHub

```bash
git remote add origin https://github.com/sindhupriya5e1/devops-task-5.git
git push -u origin main
```

### Step 6: Enable GitHub Pages

1. Open the GitHub repository.
2. Navigate to **Settings → Pages**.
3. Under Build and deployment, select **Deploy from a branch**.
4. Select the `main` branch.
5. Select the `/(root)` folder.
6. Click **Save**.

### Step 7: Verify the deployment

Checked the GitHub Actions workflow and confirmed that the displayed run status was **Success**.

Opened the published website in a browser to verify that the portfolio content was accessible.

### Step 8: Update project documentation

Added this README to explain the project's objectives, technologies, deployment procedure, and interview questions.

## 9. Verification Checklist

* [x] Created `index.html`.
* [x] Created `style.css`.
* [x] Initialized the Git repository.
* [x] Pushed the source code to GitHub.
* [x] Published the website through GitHub Pages.
* [x] Observed a successful GitHub Actions workflow run.
* [x] Opened the live website.
* [ ] Added the final README and pushed it to GitHub.
* [ ] Captured screenshots for internship submission, if required.

## 10. Common Issues and Troubleshooting

### Issue: Website shows a 404 error

**Possible solutions:**

* Check that GitHub Pages is enabled in repository settings.
* Confirm that the correct branch and root folder are selected.
* Confirm that `index.html` exists in the repository root.
* Check the deployment workflow and wait briefly for publishing to finish.

### Issue: CSS styling is missing

**Possible solutions:**

* Confirm that `style.css` exists in the repository.
* Check that the stylesheet link in `index.html` uses the correct filename.
* Check the capitalization of the filename.
* Refresh the browser after deployment.

### Issue: Changes do not appear on the live website

**Possible solutions:**

* Commit and push the latest changes.
* Check the latest GitHub Actions workflow.
* Wait for the deployment to finish.
* Refresh the page or try a hard refresh.

### Issue: Git push is rejected

**Possible solutions:**

* Run `git status` to inspect the current repository state.
* Confirm the branch using `git branch`.
* Check the remote using `git remote -v`.
* Authenticate with GitHub using an appropriate supported method.

## 11. GitHub Pages Interview Questions and Answers

### Q1. What is GitHub Pages?

GitHub Pages is a hosting service that publishes static websites directly from a GitHub repository.

### Q2. What is a static website?

A static website serves files such as HTML, CSS, JavaScript, and images without requiring a server-side application to generate each page dynamically.

### Q3. What is the purpose of `index.html`?

`index.html` is commonly used as the default entry page of a website.

### Q4. What is the role of CSS?

CSS controls the presentation of a webpage, including colors, fonts, spacing, layout, and responsive styling.

### Q5. What is Git?

Git is a distributed version-control system used to track file changes and collaborate on software projects.

### Q6. What is GitHub?

GitHub is a platform for hosting Git repositories and collaborating on source code.

### Q7. What is the difference between Git and GitHub?

Git is the version-control tool; GitHub is an online platform that hosts Git repositories and provides collaboration features.

### Q8. What is a Git repository?

A Git repository stores project files and their version history.

### Q9. What does `git add` do?

`git add` stages selected changes so they can be included in the next commit.

### Q10. What does `git commit` do?

`git commit` records staged changes in the local Git repository.

### Q11. What does `git push` do?

`git push` uploads local commits to a remote repository, such as GitHub.

### Q12. What is a branch in Git?

A branch is an independent line of development. In this project, the source code was pushed to the `main` branch.

### Q13. What is GitHub Actions?

GitHub Actions is an automation platform used to run workflows for tasks such as testing, building, and deploying applications.

### Q14. What does a successful GitHub Actions run mean?

It means the workflow completed successfully according to its configured steps. It does not, by itself, guarantee that every aspect of the website works correctly in the browser.

### Q15. How did you deploy your website?

I pushed the HTML and CSS files to a public GitHub repository, configured GitHub Pages to deploy from the `main` branch and root folder, and checked the workflow and published website.

### Q16. What is the live URL of your project?

https://sindhupriya5e1.github.io/devops-task-5/

### Q17. Is an EC2 instance required to host a website on GitHub Pages?

No. GitHub Pages hosts the static website, so an EC2 instance is not required for the hosting itself.

### Q18. Can GitHub Pages host a backend application?

GitHub Pages is intended for static websites. A backend requiring server-side execution needs a separate hosting service.

### Q19. What is the difference between a static website and a dynamic website?

A static website serves prepared files, while a dynamic website can generate content at runtime using server-side code, databases, or APIs.

### Q20. How would you update the website after deployment?

I would edit the relevant files, stage and commit the changes, push them to the configured branch, and verify that the deployment completed and the live website reflects the changes.

## 12. Learning Outcomes

Through this task, I practised:

* Creating a static website with HTML and CSS.
* Using Git for version control.
* Hosting a source-code project on GitHub.
* Deploying a website using GitHub Pages.
* Checking workflow status through GitHub Actions.
* Documenting a technical project and troubleshooting common deployment issues.

## 13. Project Deliverables

* Source code: `index.html` and `style.css`
* GitHub repository link
* Live GitHub Pages URL
* Successful GitHub Actions workflow run
* README project documentation
* Screenshots of the live website, repository, and workflow, if required by the internship team

## 14. Author

**Abbineni sindhupriya**
Aspiring Cloud & DevOps Engineer
2026 Computer Science and Engineering Graduate

* GitHub: https://github.com/sindhupriya5e1
* LinkedIn :https://WWW.linkedin.com/in/abbineni-sindhupriya

---

**Task:** Task 5 — Host a Static Website with GitHub Pages
**Status:** Website deployed; README documentation update in progress.
