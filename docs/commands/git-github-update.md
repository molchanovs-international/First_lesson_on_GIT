## Update Git and GitHub CLI (Windows)

### Verify current installation
```powershell
where.exe git
where.exe gh
git --version
gh --version
```

### Update via winget (non-interactive)
```powershell
winget upgrade --id Git.Git --source winget --silent --accept-package-agreements --accept-source-agreements
winget upgrade --id GitHub.cli --source winget --silent --accept-package-agreements --accept-source-agreements
```

If not installed:
```powershell
winget install --id Git.Git --source winget --silent --accept-package-agreements --accept-source-agreements
winget install --id GitHub.cli --source winget --silent --accept-package-agreements --accept-source-agreements
```

### After update
```powershell
# Restart terminal to refresh PATH, then verify
git --version
gh --version

# Update all GitHub CLI extensions (optional)
gh extension upgrade --all
```


