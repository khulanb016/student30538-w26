# PPHA 30538: Data Analytics and Visualization for Public Policy
## Winter 2026
## University of Chicago Harris School of Public Policy
## Peter Ganong and Maggie Shi

# Repository Structure

Lectures are stored in the `lectures` folder. Within each folder, each lecture will have its own folder with slides. 
Each problem set and mini-lesson will have their own folders within their respective folders. 

---
# Accessing the Repository
## Step 1: Fork the Repository  
- Go to the [original repository](https://github.com/uchicago-harris-dap/student30538-w26) on GitHub.  
- Click the **Fork** button in the upper-right corner of the repository page. This will create a personal copy of the repository in your GitHub account.

---

### Step 2: Clone Your Forked Repository  
1. In your GitHub account, navigate to your **forked repository**.  
2. Click the green **Code** button and copy the **HTTPS URL**, **https://github.com/uchicago-harris-dap/student30538-w26**.  
3. Open a terminal and run the following command:
   ```bash
   git clone https://github.com/uchicago-harris-dap/student30538-w26
   ```

### Step 3: Set the Upstream Remote  
(Optional but recommended to keep your fork updated.)  
1. Navigate to the cloned repository in your terminal:
   ```bash
   cd student30538-w26
   ```
2. Add the upstream remote:
   ```bash
   git remote add upstream https://github.com/uchicago-harris-dap/student30538-w26
   ```
3. Confirm your remotes:
   ```bash
   git remote -v
   ```

### Step 4: Sync Your Fork with the Original Repository  
1. Fetch updates from the original repository:
   ```bash
   git fetch upstream
   ```
2. Merge the updates into your local branch:
   ```bash
   git merge upstream/main
   ```
   Replace `main` if the default branch has a different name (e.g., `master`).

### Step 5: Push Changes to Your Fork  
1. After making changes, stage and commit them:
   ```bash
   git add .
   git commit -m "Your commit message"
   ```
2. Push the changes to your fork:
   ```bash
   git push origin main
   ```

---


Feel free to reach out via EdDiscussion if you have any questions or run into any issues. Happy coding!
