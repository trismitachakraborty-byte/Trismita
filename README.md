# Trismita
Tools installed, cursor IDE, github, git
Create a GitHub Account
Open https://github.com
Click Sign Up
Enter:
Email address
Username
Password
Verify My email address
Complete the registration process
Select the Free plan
Download and Install Cursor IDE
Open https://cursor.com
Click Download
Download the version for My operating system
Run the installer
Follow the installation wizard
Launch Cursor after installation
Sign In to Cursor
Open Cursor
Sign in using:
GitHub
Google
Email
Download and Install Git
Git is required to connect My local computer to GitHub.
Open https://git-scm.com/downloads
Download Git for My operating system
Run the installer
Keep the default settings
Complete the installation
Verify Installation
Open Command Prompt or Terminal and run:
git --version
You should see a version number.
Configure Git
Open Command Prompt or Terminal.
Set My username:
git config --global user.name "My Name"
Set My email:
git config --global user.email "My@email.com"
Verify configuration:
git config --list
Create a Public GitHub Repository
Log in to GitHub
Click the + icon in the top-right corner
Select New Repository
Enter a repository name
Add an optional description
Select Public
Check Add a README file
Click Create Repository
Example:
Repository Name: my-first-project
Visibility: Public
Install Node.js
Node.js is required for Claude Code and OpenAI Codex.
Open https://nodejs.org
Download the LTS version
Run the installer
Complete the installation
Verify Installation
node -v
npm -v
Both commands should display version numbers.
Install Claude Code
Open Command Prompt or Terminal.
Install Claude Code:
npm install -g @anthropic-ai/claude-code
Verify installation:
claude --version
Login
Start Claude Code:
claude
Follow the browser authentication process.
Step 8: Install OpenAI Codex
Open Command Prompt or Terminal.
Install Codex:
npm install -g @openai/codex
Verify installation:
codex --version
Login
Start Codex:
codex
Follow the browser authentication process.
Clone My GitHub Repository
Open My GitHub repository.
Click the green Code button
Copy the HTTPS URL
Example:
https://github.com/username/my-first-project.git
Open Command Prompt or Terminal.
Navigate to My desired location:
cd Desktop
Clone the repository:
git clone https://github.com/username/my-first-project.git
Move into the project folder:
cd my-first-project
Open Repository in Cursor
Open Cursor
Click File → Open Folder
Select My repository folder
Click Open
Connect GitHub to Cursor
Open Cursor
Press:
Ctrl + Shift + P
Search for:
GitHub Sign In
Select the sign-in option
Complete authentication in My browser
GitHub connected to Cursor
Use Claude Code Inside Cursor
Open the Cursor terminal:
Terminal → New Terminal
Run:
claude
Example prompts:
Explain this codebase
Create a login page
Fix all errors in this project
Use OpenAI Codex Inside Cursor
Open the Cursor terminal.
Run:
codex
Save Changes to GitHub
Check repository status:
git status
Stage all changes:
git add .
Create a commit:
git commit -m "Initial setup"
Push changes to GitHub:
git push origin main
Problems faced and solution
Verification Email Not Received
Check Spam/Junk folder.
Verify email address spelling.
Click "Resend Verification Email".
Use a different email address
Username Already Taken
Try variations:
Cursor Installer Not Starting
Delete installer.
Download again from Cursor website.
Temporarily disable antivirus if safe.
Run installer as Administrator.
Git Shows Unknown Author
Try commit again.
Claude Command Not Found
Reinstall
Codex Command Not Found
Git Commit Problems
Modify a file before committing.