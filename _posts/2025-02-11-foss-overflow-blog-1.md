---
title: "FOSS Overflow Week 1: Learning & Contributing 🛠️"
date: 2025-02-11 22:30:00 +0530
categories: [FOSS Overlflow]
tags: [MERN, WebDev, open-source, git, github, authentication]
---

Entering FOSS Overflow has been an exciting and enriching experience for me. In just my first week, I have not only contributed features to the project but also expanded my understanding of Git and GitHub workflows. From adding essential authentication features to learning advanced Git operations, this week has been a deep dive into open-source collaboration.

## Features I Worked On
One of my primary contributions this week was implementing authentication-related functionalities. These include:
- **OTP Verification via Email** – Ensuring secure user registration and authentication.
- **Forgot Password** – Allowing users to request a password reset.
- **Reset Password** – Implementing a secure way for users to update their passwords after verification.

These features are crucial in improving the overall security and user experience of the application. Working on them helped me understand authentication flows in a real-world scenario, reinforcing my backend development skills. I used Nodemailer with Brevo SMTP configurations to setup the mailing system.

## Git and GitHub: Leveling Up
While working on these features, I learned several valuable Git and GitHub concepts from my mentor and fellow contributor, which greatly improved my workflow and helped me understand the true potential of Git and GitHub. These concepts were:

- **Adding a Remote** – `git remote add <name> <repo-URL>`\\
I learned how to add and manage multiple remote repositories, a useful skill for contributing to open-source projects and making changes across different forked repositories.

- **Cherry-Picking** – `git cherry-pick <commit-hash>`\\
This technique allows to selectively apply commits from one branch to another, making it easier to manage changes without unnecessary merge conflicts.

- **Committing to an Existing PR** – \\
I explored how to contribute to a pull request created by someone else but not yet merged. This involved cloning the forked repository, making the necessary changes, and pushing commits to the same branch from which the PR was created. Since the PR is linked to this branch, the new commits automatically appear in the PR.

- **Maintaining Code Consistency and Standards** – \\
I learned the importance of following the existing structure and coding standards to ensure seamless integration, improve readability, and make it easier for others to review my contributions.

## Key Takeaways
This first week at FOSS Overflow has been a fantastic learning experience. I not only improved my development and debugging skills but also gained a deeper understanding of collaborative development workflows.

Open-source contribution is more than just writing code; it involves understanding team collaboration, following best practices, and continuously learning.

I am excited about the journey ahead and look forward to contributing more in the coming weeks!
