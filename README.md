# Azure Security Audit Scripts

PowerShell and Azure CLI scripts for auditing common Azure security misconfigurations.

## Scripts

| Script | Description |
|--------|-------------|
| `check-storage-public.ps1` | Identify publicly accessible storage accounts |
| `audit-iam-roles.ps1` | List over-privileged IAM assignments |
| `nsg-analysis.ps1` | Review NSG rules for overly permissive entries |
| `mfa-status.ps1` | Check MFA status for all users |

## Usage

```powershell
Connect-AzAccount
.\check-storage-public.ps1
