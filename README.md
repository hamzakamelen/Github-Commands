
# Push a Repository to GitHub

## Prerequisites

1. **Git**: Make sure Git is installed on your system.
   - Install Git from [git-scm.com](https://git-scm.com).

2. **GitHub Account**: Create an account at [GitHub](https://github.com) if you don't have one already.

## Steps to Push a Repository to GitHub

1. **Create a New Repository on GitHub**
   - Go to [GitHub](https://github.com).
   - Click the **+** icon in the top right corner and select **New repository**.
   - Give it a name and click **Create repository**. Do not initialize with a README, .gitignore, or license.

2. **Initialize a Git Repository Locally**
   If you haven't already initialized your project folder as a Git repository, open a terminal/command prompt and run:
   ```bash
   git init
   ```

3. **Add Your Files to the Repository**
   Add all files in your project directory to Git:
   ```bash
   git add .
   ```

4. **Commit Your Changes**
   Commit your files with a message:
   ```bash
   git commit -m "Initial commit"
   ```

5. **Add the Remote Repository**
   Add the URL of your GitHub repository as a remote origin:
   ```bash
   git remote add origin https://github.com/your-username/your-repository.git
   ```

6. **Push Your Local Repository to GitHub**
   Push your changes to GitHub:
   ```bash
   git push -u origin master
   ```

   If you're using Git version 2.28 or newer, the default branch might be `main` instead of `master`. In that case, use:
   ```bash
   git push -u origin main
   ```

7. **Verify Your Changes on GitHub**
   Go to your GitHub repository in your browser, and you should see your files there.

---

## Helpful Links

- [GitHub Documentation](https://docs.github.com/en/github)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

---

That's it! Your repository is now on GitHub!
