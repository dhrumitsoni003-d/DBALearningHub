# How to Host on GitHub Pages

Since I have already initialized the Git repository for you locally, follow these simple steps to put your website online for free.

## 1. Create a Repository on GitHub
1. Log in to your [GitHub account](https://github.com/).
2. Click the **+** icon in the top right and select **New repository**.
3. Name it `dba-learning-hub` (or any name you prefer).
4. Make sure it is **Public**.
5. Do **exclude** "Initialize with a README" (keep the repo empty).
6. Click **Create repository**.

## 2. Push Your Code
You will see a page with "Quick setup". Look for the section **"…or push an existing repository from the command line"**.

Copy the commands shown there. They will look like this (replace `YOUR_USERNAME` with your actual GitHub username):

```bash
git remote add origin https://github.com/YOUR_USERNAME/dba-learning-hub.git
git branch -M main
git push -u origin main
```

Run these commands in your terminal inside the `e:\DBA Learning Hub` folder.

## 3. Enable GitHub Pages
1. Go to your repository **Settings** tab.
2. Click on **Pages** in the left sidebar (under "Code and automation").
3. Under **Build and deployment** > **Branch**, select `main` and ensure the folder is `/(root)`.
4. Click **Save**.

Wait a minute or two, and GitHub will give you a link (e.g., `https://your-username.github.io/dba-learning-hub/`). That is your live website!
