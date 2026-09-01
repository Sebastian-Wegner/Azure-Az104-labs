# Azure AZ-104 Labs

Hands-on-Projekte auf dem Weg zur Zertifizierung **AZ-104 (Azure Administrator Associate)**.
Ich baue nach und nach eine komplette Azure-Umgebung für die fiktive Firma „Contoso" auf –
jedes Projekt deckt einen Prüfungsbereich mit echter Praxis ab.

## Über mich
Ich befinde mich in einer Umschulung Richtung Cloud Engineering und bereite mich aktuell
auf die AZ-104-Zertifizierung vor. Dieses Repo dokumentiert meine praktischen Übungen.

## Projekte

| Projekt | Thema | Status |
|---------|-------|--------|
| 1 – Governance | Entra ID, RBAC, Custom Roles, Azure Policy, Resource Locks | ✅ Fertig |
| 2 – Storage | Redundanz, Blob Tiers, Lifecycle, Private Endpoints | 🔜 Geplant |
| 3 – Networking | VNets, NSG, Peering, Bastion, Network Watcher | 🔜 Geplant |
| 4 – Compute | VMs, Availability, Scale Sets, App Service | 🔜 Geplant |
| 5 – Monitoring | Azure Monitor, Log Analytics, KQL, Backup | 🔜 Geplant |
| 6 – Infrastructure as Code | Bicep / ARM Templates | 🔜 Geplant |

## Skills
Microsoft Entra ID · RBAC · Azure Policy · Governance · Storage · Virtual Networking · Bicep

## Projekt 1 – Governance
- **CustomRoleDefinition.json** – selbst erstellte RBAC-Rolle „VM Operator" (start/restart/power off, ohne Löschrecht)
- **policy-require-tag.json** – Azure Policy, die ein Pflicht-Tag „Environment" erzwingt
