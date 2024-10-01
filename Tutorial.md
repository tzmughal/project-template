### Clone a GitHub Repository and Remove the `.git` Directory in PowerShell

```powershell
# Clone the repository
git clone https://github.com/tzmughal/project-template.git

# Navigate to the cloned repository
cd project-template

# Remove the .git folder and all its contents
Remove-Item -Recurse -Force .git
