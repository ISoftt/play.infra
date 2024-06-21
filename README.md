# play.infra
Play Economy Infrastructure

## Add the GitHub package source
```powershell
$owner="ISoftt"
$github_personal_access_token="specify here"

dotnet nuget add source --username USERNAME --password $github_personal_access_token --store-password-in-clear-text --name github "https://nuget.pkg.github.com/$owner/index.json
```