# GitHub Actions demo

This is a demo React project to showcase some GitHub Action workflows.

## Getting Started


To use this project and test the GitHub Actions workflows, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/tobiasvdorp/github-actions-demo
   ```

2. Remove the existing Git history:

   ```bash
   cd github-actions-demo
   rm -rf .git
   ```

3. Initialize a new Git repository:

   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

4. Create a new repository on GitHub:

   - Go to github.com
   - Click "New repository"
   - Give your repository a name
   - Leave the options for README, .gitignore etc. unchecked

5. Push your code to your new repository:
   ```bash
   git remote add origin https://github.com/[your-username]/[your-repo-name].git
   git branch -M main
   git push -u origin main
   ```

Now you can make changes to the workflows (found in `.github/workflows/`) and test them by creating pull requests in your own repository.
