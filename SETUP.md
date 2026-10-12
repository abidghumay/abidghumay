# 🚀 Setup Guide for Your GitHub Profile

Follow these steps to deploy your profile and activate the **3D Isometric Contribution Graph** and **Snake Game** animations.

---

### Step 1: Create Your Special Profile Repository
1. Go to [GitHub New Repository](https://github.com/new).
2. Set the **Repository name** to exactly:
   ```text
   abidghumay
   ```
   *(GitHub will show a banner saying: "You found a secret! abidghumay/abidghumay is a special repository that you can use to add a README.md to your GitHub profile.")*
3. Make sure the repository is **Public**.
4. Leave **"Add a README file" UNCHECKED** (we already have one ready).
5. Click **Create repository**.

---

### Step 2: Enable Workflow Write Permissions (Crucial for 3D & Snake)
By default, GitHub Actions workflows have read-only permissions. To let the actions commit the 3D graph and snake game:
1. In your `abidghumay/abidghumay` repository, go to **Settings** (top right tab).
2. On the left sidebar, click **Actions** ➔ **General**.
3. Scroll down to the **Workflow permissions** section.
4. Select **Read and write permissions**.
5. Check **Allow GitHub Actions to approve pull requests** (optional, recommended).
6. Click **Save**.

---

### Step 3: Push This Folder to GitHub
Open your terminal in this `readme` directory and run:

```bash
git init
git add .
git commit -m "feat: initial obsidian systems profile with 3d and snake workflows"
git branch -M main
git remote add origin https://github.com/abidghumay/abidghumay.git
git push -u origin main
```

---

### Step 4: Run the Workflows Manually (First Time)
Once pushed, run the workflows once to generate your 3D graphs and snake immediately:
1. Go to the **Actions** tab in your repository.
2. In the left sidebar:
   * Click **GitHub-Profile-3D-Contrib** ➔ Click the **Run workflow** button on the right ➔ Click green **Run workflow**.
   * Click **Generate Snake Animation** ➔ Click the **Run workflow** button on the right ➔ Click green **Run workflow**.
3. Wait 1–2 minutes for them to finish.
4. Refresh [your GitHub profile](https://github.com/abidghumay) — your 3D contribution city and animated snake game will now be live!
