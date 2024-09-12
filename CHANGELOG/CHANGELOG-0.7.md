# v0.7 Release notes

## Features
- Upgrade van Backstage naar laatste stable versie (v1.30)
- Backstage integratie met Microsoft Entra (bèta)
- Backstage backend voorbereid op testen RBAC policies
- Backstage RBAC policy aangemaakt waarbij je geen componenten van andere gebruikers mag deleten (alpha)
- Backstage RBAC policy aangemaakt waarbij je alleen componenten mag aanmaken binnen je eigen Backstage Group (alpha)
- Inzicht in je eigen Group via de Backstage portal
- Azure Devops is voorbereid op het gebruik van meerdere Azure Devops projecten (bèta)
- Argocd is aangepast op het gebruik van meerdere Azure Devops projecten (bèta)
 
Binnen de Microsoft Entra integratie zal de benodgide informatie uit onderstaande conventie worden opgehaald.
De huidige groepen:
SG_AKS_Backtage_Administrators
SG_AKS_Backstage_<team-name>_Reader
SG_AKS_Backstage_<team-name>_Contributor