# Authentication Service
CLI libraries used by trita gate services.
```powershell

## Publish to IIS cli
$deploy_password = "[PASSWORD HERE]"

dotnet publish -c Release /p:PublishProfile=Properties\PublishProfiles\XXX.pubxml /p:password=$DEPLOY_PASSWD
```
