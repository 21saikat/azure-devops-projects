#### **Step 1: Create a Repository on GitHub**

1. Go to [GitHub](https://github.com/) and log in.  
2. Click on the **"+"** icon (top right) and select **"New repository"**.  
3. Enter **Repository Name** (e.g., `azure-devops-projects`).  
4. Choose the **public** or **private** option.  
5. **Do not initialize with a README** (we'll add it later).  
6. Click **"Create repository"**.

---

#### **Step 2: Setup Git Locally**

1. Open a terminal (Linux/macOS) or Git Bash (Windows).

Navigate to your project folder:

`cd /path/to/your/project`

Initialize Git:

`git init`

Add the GitHub repository as a remote origin:

`git remote add origin https://github.com/your-username/azure-devops-projects.git`

2. 

---

#### **Step 3: Upload Your Project Files**

**Check Status** (to see untracked files):

`git status`

**Stage All Files**:

`git add .`

**Commit Changes**:

`git commit -m "Initial commit - uploading project"`

1. 

**Push Code to GitHub**:

`git branch -M main`  
`git push -u origin main`

---

#### **Step 4: Verify on GitHub**

1. Go to your repository on GitHub.  
2. Refresh the page to see your uploaded files.

---

#### **Step 5: (Optional) Add a README File**

To add a `README.md` file for documentation:

`echo "# Azure DevOps Projects" >> README.md`  
`git add README.md`  
`git commit -m "Added README"`  
`git push origin main`

