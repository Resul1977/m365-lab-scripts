# m365-lab-scripts
Microsoft 365 lab scripts, automation tests, and developer experiments.

## Graph smoke test (GitHub Actions)

Required GitHub Secrets: `AZURE_TENANT_ID`, `AZURE_CLIENT_ID`, `AZURE_CLIENT_SECRET`  
Graph permissions (App / Application): `User.Read.All` (admin consent required)  
Run: Actions → “Graph smoke test (client secret)” → Run workflow (or weekly schedule)
