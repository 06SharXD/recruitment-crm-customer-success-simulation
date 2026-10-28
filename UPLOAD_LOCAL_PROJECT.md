# Upload the local project files

The GitHub-connected tool cannot read files directly from your Windows drive. This repository has a starter README only; the project application and source datasets still need to be pushed from your computer.

From PowerShell, run these commands:

```powershell
cd "E:\proj\proj4\Recruit_CRM_Customer_Success_Simulation"

git rev-parse --show-toplevel
```

If the command reports this exact project folder, check the remote:

```powershell
git remote -v
```

If `origin` is missing:

```powershell
git remote add origin https://github.com/06SharXD/recruitment-crm-customer-success-simulation.git
```

If `origin` exists but points somewhere else:

```powershell
git remote set-url origin https://github.com/06SharXD/recruitment-crm-customer-success-simulation.git
```

Then stage and push **only after confirming `git rev-parse --show-toplevel` reports the project folder**:

```powershell
git add README.md demo data docs conversations
 git status
```

Inspect `git status` and confirm it lists only this project's files. Then commit and push:

```powershell
git commit -m "Add recruitment CRM customer success simulation"
git branch -M main
git push -u origin main
```

If the project folder is not itself the Git root, do not run `git add .` from a parent repository. First initialize Git from this project folder or use GitHub Desktop to add this exact folder as a repository. Never force-push over existing commits to solve a path/ownership issue.
