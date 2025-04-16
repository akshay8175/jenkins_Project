# My First Jenkins Project

### step 1 : Login to Jenkins Dashboard

- Login with admin credentials.

### Step 2 : Create a New Item
- Click “New Item” (left sidebar).
- Enter a name (e.g., MyFirstProject).
- Select “Freestyle project”.
- Click OK.

### Step 3 : Source Code Management
- Choose Git.
- Add your repository URL.
- (Optional) Add credentials if it's a private repo.

### Step 4 : Build Triggers
- Select when Jenkins should build Manually

### Step 5 : Build Environment
- Add anything specific like cleaning workspace before build, etc.

### Step 6 : Build Steps
- Click Add build step
- Execute shell (Linux/macOS) or Execute Windows batch command.
- Add a simple command:
> echo "Hello from Jenkins!"

### Step 7 : Save and Build
- Click Save.
- Then click Build Now on the project page.

### Step 8 : check the console output
- click on #1 build number and go to console output
