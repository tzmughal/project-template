### Clone a GitHub Repository and Remove the `.git` Directory in PowerShell

```powershell
git clone https://github.com/tzmughal/project-template.git
cd project-template
Remove-Item -Recurse -Force .git
code .
