# Hello Jenkins

A simple Maven project for GitHub + Jenkins + Webhook.

## Steps
1. Push this project to GitHub.
2. Create a Jenkins Pipeline job.
3. Select 'Pipeline script from SCM'.
4. Enable 'GitHub hook trigger for GITScm polling'.
5. Add the GitHub webhook:
   http://<JENKINS-IP>:8080/github-webhook/
6. Push changes to GitHub to trigger builds.
