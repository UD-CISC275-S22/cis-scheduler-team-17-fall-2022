[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9219476&assignment_repo_type=AssignmentRepo)
# React TypeScript Starter Repo

Hello! This repository has been pre-configured with eslint and gh-pages to automatically deploy your app when you push to the main branch.

You will, however, need to finish setting up the deployment.

### 1. Generate a personal access token

1. Click on your picture -> `settings` in the top right of Github.
2. Then, scroll to `Developer Settings` and click `Personal access tokens`
3. Generate a new token with `repo` access and no expiration date.
4. Make sure you copy the created token as you will not be able to see it after this.

### 2. Add a secret to the forked repo

Back in this repository, go to `settings` -> `secrets` -> `Actions` and click the `New repository secret` button in the topright.

Name the secret "GH_TOKEN" and paste in the token you copied in the previous step.
