# HW5 - Configuration Management and Continuous Deployment

Create an ansible playbook that is able to:

* **Setup: (40 points)** Install the following items:
    * Install node.js
    * Install forever
    * Pull/clone git repo into a destination: https://github.com/CSC-DevOps/App
    * Install npm packages
    
* **Tasks: (40 points)**:
    * Run app: `forever start node main.js`
    * Security: Create a task that ensures `bash`, `openssl`, `openssh-client`, and `openssh-server` are running latest version.
    * Cleanup: Remove content in `/tmp/*`

* **Concepts (20 points)**:

    * Why should developers use configuration management tools to manage their software programs? What can go wrong?
    * Explain the difference bewteen continuous integration, continuous delivery, and continuous deployment, in your own words.

## Submission

Submit your [repo link](https://docs.google.com/forms/d/e/1FAIpQLScBUOZO7S2tJdWowgzc1VzjvOgG-bHhIoKfZdQSCvYAl2jxoQ/viewform?usp=sf_link).

* README.md (which documents steps for running ansible and playbook).
* Ansible playbook files
* Screencast demo of performing setup, tasks, running app.

Due, Friday, November 17th, midnight.
