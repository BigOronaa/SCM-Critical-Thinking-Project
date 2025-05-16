# Automate Code Quality and Deployment

For this Task i used GitHub Actions to automate testing, code quality checks, and deployment.

###  When is it triggered?
- On every push to any branch starting with `feature-`.

###  What does it do?
1. **Checks out the code.**
2. **Runs unit tests (simulated).**
3. **Checks code quality (simulated).**
4. **If all pass, deploys to a staging environment (simulated).**

###  How to use:
- Create a feature branch: `git checkout -b feature-login-page`
- Push to GitHub: `git push origin feature-login-page`
- GitHub Actions will take over.
