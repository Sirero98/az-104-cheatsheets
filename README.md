# AZ-104 Cheatsheets · Azure Administrator Associate

![AZ-104](https://img.shields.io/badge/Microsoft-AZ--104-0078D4?logo=microsoftazure&logoColor=white)
![Languages](https://img.shields.io/badge/languages-EN%20%7C%20ES-success)
![PDFs](https://img.shields.io/badge/PDFs-36-informational)
![License](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)

> 🇬🇧 English below · 🇪🇸 [Versión en español](#-español)

**Cheatsheet-style** notes to prepare for the **AZ-104: Microsoft Azure Administrator** exam. Each topic fits in 3 to 5 pages, goes straight to the point and is built for last-minute review: comparison tables, decision trees, the Azure CLI and PowerShell commands that show up in questions, and the keywords that usually reveal which answer the exam wants.

Available in **English** and **Spanish**.

---

## 🇬🇧 English

### What's inside?

- **16 topic cheatsheets** covering the five exam areas (skills measured as of April 17, 2026): identities and governance, storage, compute, virtual networking, and monitoring and maintenance.
- **One extra cheatsheet** with the equivalent Azure CLI and PowerShell commands side by side, Cloud Shell and exam tricks.
- **One complete PDF** with every cheatsheet merged and bookmarked, if you prefer a single document.
- Each cheatsheet ends with a **decision tree**, a **"question keywords → answer"** table and a list of **mistakes to avoid**.

### How to use them

1. Learn the theory first on [Microsoft Learn](https://learn.microsoft.com/credentials/certifications/azure-administrator/) or in whatever course you are following.
2. Use these cheatsheets to **consolidate** and compare similar options (service endpoint vs private endpoint, availability set vs zones, Recovery Services vault vs Site Recovery, and so on).
3. In the final days, review only the tables, the decision trees and the keyword sections.

### Index

| # | Topic | 🇬🇧 PDF | 🇪🇸 PDF |
|---|-------|---------|---------|
| 01 | Microsoft Entra ID: users, groups, licensing, guests and SSPR | [EN](en/cheatsheet-01-entra-id-users-groups-licensing-sspr.pdf) | [ES](es/cheatsheet-01-entra-id-usuarios-grupos-licencias-sspr.pdf) |
| 02 | RBAC: built-in roles, scopes, inheritance and interpreting assignments | [EN](en/cheatsheet-02-rbac-roles-scopes-assignments.pdf) | [ES](es/cheatsheet-02-rbac-roles-ambitos-asignaciones.pdf) |
| 03 | Governance: subscriptions, management groups, Policy, locks, tags, costs and Advisor | [EN](en/cheatsheet-03-governance-subscriptions-policy-locks-tags-costs.pdf) | [ES](es/cheatsheet-03-gobernanza-suscripciones-policy-locks-tags-costes.pdf) |
| 04 | Storage accounts: types, redundancy, encryption, object replication, firewall, Storage Explorer and AzCopy | [EN](en/cheatsheet-04-storage-accounts-redundancy-encryption-firewall-azcopy.pdf) | [ES](es/cheatsheet-04-storage-accounts-redundancia-cifrado-firewall-azcopy.pdf) |
| 05 | Storage access: keys, SAS, stored access policies and identity for Azure Files | [EN](en/cheatsheet-05-storage-access-keys-sas-files-identity.pdf) | [ES](es/cheatsheet-05-acceso-storage-claves-sas-identidad-files.pdf) |
| 06 | Blob and Files: tiers, lifecycle, versioning, soft delete, snapshots and Azure File Sync | [EN](en/cheatsheet-06-blob-files-tiers-lifecycle-versioning-file-sync.pdf) | [ES](es/cheatsheet-06-blob-files-tiers-lifecycle-versioning-file-sync.pdf) |
| 07 | ARM templates and Bicep: structure, deployment, export and conversion | [EN](en/cheatsheet-07-arm-templates-bicep.pdf) | [ES](es/cheatsheet-07-arm-templates-bicep.pdf) |
| 08 | Virtual machines: creation, sizes, disks, encryption, moves and availability | [EN](en/cheatsheet-08-virtual-machines-disks-encryption-availability.pdf) | [ES](es/cheatsheet-08-maquinas-virtuales-discos-cifrado-disponibilidad.pdf) |
| 09 | VM Scale Sets, autoscale, extensions and VM access | [EN](en/cheatsheet-09-vmss-extensions-vm-operations.pdf) | [ES](es/cheatsheet-09-vmss-extensiones-operaciones-vm.pdf) |
| 10 | Containers: Container Registry, Container Instances and Container Apps | [EN](en/cheatsheet-10-containers-acr-aci-container-apps.pdf) | [ES](es/cheatsheet-10-contenedores-acr-aci-container-apps.pdf) |
| 11 | App Service: plans, scaling, slots, domains, TLS, backup and networking | [EN](en/cheatsheet-11-app-service-plans-slots-domains-tls-backup-networking.pdf) | [ES](es/cheatsheet-11-app-service-planes-slots-dominios-tls-backup-redes.pdf) |
| 12 | Virtual networks: VNet, subnets, public IPs, peering, routing and troubleshooting | [EN](en/cheatsheet-12-virtual-networks-vnet-ip-peering-routing.pdf) | [ES](es/cheatsheet-12-redes-virtuales-vnet-ip-peering-rutas.pdf) |
| 13 | Network security: NSG and ASG, effective rules, Bastion, service endpoints and private endpoints | [EN](en/cheatsheet-13-network-security-nsg-asg-bastion-endpoints.pdf) | [ES](es/cheatsheet-13-seguridad-red-nsg-asg-bastion-endpoints.pdf) |
| 14 | DNS and load balancing: Azure DNS, private zones, Load Balancer and troubleshooting | [EN](en/cheatsheet-14-dns-load-balancer.pdf) | [ES](es/cheatsheet-14-dns-load-balancer.pdf) |
| 15 | Azure Monitor: metrics, logs and KQL, alerts, Insights and Network Watcher | [EN](en/cheatsheet-15-azure-monitor-metrics-logs-kql-alerts-network-watcher.pdf) | [ES](es/cheatsheet-15-azure-monitor-metricas-logs-kql-alertas-network-watcher.pdf) |
| 16 | Backup and recovery: vaults, policies, restore and Site Recovery | [EN](en/cheatsheet-16-backup-site-recovery.pdf) | [ES](es/cheatsheet-16-backup-site-recovery.pdf) |
| ★ | Commands: equivalent Azure CLI and PowerShell, Cloud Shell and exam tricks | [EN](en/cheatsheet-commands-cli-powershell.pdf) | [ES](es/cheatsheet-comandos-cli-powershell.pdf) |

**📘 Everything in one PDF:** [English (67 pages)](en/AZ-104-cheatsheets-complete-EN.pdf) · [Español (67 págs.)](es/AZ-104-cheatsheets-completo.pdf)

### Repository layout

```
.
├── en/   English PDFs (17 cheatsheets + complete version)
└── es/   Spanish PDFs (17 cheatsheets + complete version)
```

### Disclaimer

This is **unofficial** material, not affiliated with Microsoft. These are personal study notes: always double-check details against the official documentation, since Azure services change often (several retirements and defaults changed during 2025 and 2026 and are reflected here as of October 2026). If you spot a mistake, please open an issue.

### License

[CC BY 4.0](LICENSE). You may copy, redistribute and adapt this material, even commercially, as long as you give credit.

---

## 🇪🇸 Español

### ¿Qué vas a encontrar?

Apuntes en formato **cheatsheet** para preparar el examen **AZ-104: Microsoft Azure Administrator**. Cada tema cabe en 3 a 5 páginas, va al grano y está pensado para repasar justo antes del examen: tablas comparativas, árboles de decisión, los comandos de Azure CLI y PowerShell que salen en las preguntas y las palabras clave que delatan la respuesta.

- **16 cheatsheets temáticas** que cubren las cinco áreas del examen (temario vigente desde el 17 de abril de 2026): identidades y gobernanza, almacenamiento, cómputo, redes virtuales, y monitorización y mantenimiento.
- **Una cheatsheet extra** con los comandos equivalentes de Azure CLI y PowerShell lado a lado, Cloud Shell y trucos de examen.
- **Un PDF completo** con todas las cheatsheets unidas y con índice, por si prefieres un único documento.
- Cada cheatsheet termina con un **árbol de decisión**, una tabla de **"palabras clave del enunciado → respuesta"** y una lista de **errores a evitar**.

### Cómo usarlas

1. Estudia primero la teoría en [Microsoft Learn](https://learn.microsoft.com/credentials/certifications/azure-administrator/) o en el curso que estés siguiendo.
2. Usa estas cheatsheets para **consolidar** y comparar opciones parecidas (service endpoint vs private endpoint, availability set vs zonas, Recovery Services vault vs Site Recovery, etc.).
3. Los últimos días, repasa solo las tablas, los árboles de decisión y las secciones de palabras clave.

### Índice

| # | Tema | 🇪🇸 PDF | 🇬🇧 PDF |
|---|------|---------|---------|
| 01 | Microsoft Entra ID: usuarios, grupos, licencias, invitados y SSPR | [ES](es/cheatsheet-01-entra-id-usuarios-grupos-licencias-sspr.pdf) | [EN](en/cheatsheet-01-entra-id-users-groups-licensing-sspr.pdf) |
| 02 | RBAC: roles integrados, ámbitos, herencia e interpretación de asignaciones | [ES](es/cheatsheet-02-rbac-roles-ambitos-asignaciones.pdf) | [EN](en/cheatsheet-02-rbac-roles-scopes-assignments.pdf) |
| 03 | Gobernanza: suscripciones, management groups, Policy, locks, tags, costes y Advisor | [ES](es/cheatsheet-03-gobernanza-suscripciones-policy-locks-tags-costes.pdf) | [EN](en/cheatsheet-03-governance-subscriptions-policy-locks-tags-costs.pdf) |
| 04 | Storage accounts: tipos, redundancia, cifrado, object replication, firewall, Storage Explorer y AzCopy | [ES](es/cheatsheet-04-storage-accounts-redundancia-cifrado-firewall-azcopy.pdf) | [EN](en/cheatsheet-04-storage-accounts-redundancy-encryption-firewall-azcopy.pdf) |
| 05 | Acceso a storage: claves, SAS, stored access policies e identidad para Azure Files | [ES](es/cheatsheet-05-acceso-storage-claves-sas-identidad-files.pdf) | [EN](en/cheatsheet-05-storage-access-keys-sas-files-identity.pdf) |
| 06 | Blob y Files: tiers, lifecycle, versioning, soft delete, snapshots y Azure File Sync | [ES](es/cheatsheet-06-blob-files-tiers-lifecycle-versioning-file-sync.pdf) | [EN](en/cheatsheet-06-blob-files-tiers-lifecycle-versioning-file-sync.pdf) |
| 07 | ARM templates y Bicep: estructura, despliegue, exportación y conversión | [ES](es/cheatsheet-07-arm-templates-bicep.pdf) | [EN](en/cheatsheet-07-arm-templates-bicep.pdf) |
| 08 | Máquinas virtuales: creación, tamaños, discos, cifrado, mover y disponibilidad | [ES](es/cheatsheet-08-maquinas-virtuales-discos-cifrado-disponibilidad.pdf) | [EN](en/cheatsheet-08-virtual-machines-disks-encryption-availability.pdf) |
| 09 | VM Scale Sets, autoscale, extensiones y acceso a las VMs | [ES](es/cheatsheet-09-vmss-extensiones-operaciones-vm.pdf) | [EN](en/cheatsheet-09-vmss-extensions-vm-operations.pdf) |
| 10 | Contenedores: Container Registry, Container Instances y Container Apps | [ES](es/cheatsheet-10-contenedores-acr-aci-container-apps.pdf) | [EN](en/cheatsheet-10-containers-acr-aci-container-apps.pdf) |
| 11 | App Service: planes, escalado, slots, dominios, TLS, backup y redes | [ES](es/cheatsheet-11-app-service-planes-slots-dominios-tls-backup-redes.pdf) | [EN](en/cheatsheet-11-app-service-plans-slots-domains-tls-backup-networking.pdf) |
| 12 | Redes virtuales: VNet, subredes, IPs públicas, peering, rutas y troubleshooting | [ES](es/cheatsheet-12-redes-virtuales-vnet-ip-peering-rutas.pdf) | [EN](en/cheatsheet-12-virtual-networks-vnet-ip-peering-routing.pdf) |
| 13 | Seguridad de red: NSG y ASG, reglas efectivas, Bastion, service endpoints y private endpoints | [ES](es/cheatsheet-13-seguridad-red-nsg-asg-bastion-endpoints.pdf) | [EN](en/cheatsheet-13-network-security-nsg-asg-bastion-endpoints.pdf) |
| 14 | DNS y balanceo: Azure DNS, zonas privadas, Load Balancer y su troubleshooting | [ES](es/cheatsheet-14-dns-load-balancer.pdf) | [EN](en/cheatsheet-14-dns-load-balancer.pdf) |
| 15 | Azure Monitor: métricas, logs y KQL, alertas, Insights y Network Watcher | [ES](es/cheatsheet-15-azure-monitor-metricas-logs-kql-alertas-network-watcher.pdf) | [EN](en/cheatsheet-15-azure-monitor-metrics-logs-kql-alerts-network-watcher.pdf) |
| 16 | Backup y recuperación: vaults, políticas, restore y Site Recovery | [ES](es/cheatsheet-16-backup-site-recovery.pdf) | [EN](en/cheatsheet-16-backup-site-recovery.pdf) |
| ★ | Comandos: Azure CLI y PowerShell equivalentes, Cloud Shell y trucos de examen | [ES](es/cheatsheet-comandos-cli-powershell.pdf) | [EN](en/cheatsheet-commands-cli-powershell.pdf) |

**📘 Todo en un PDF:** [Español (67 págs.)](es/AZ-104-cheatsheets-completo.pdf) · [English (67 pages)](en/AZ-104-cheatsheets-complete-EN.pdf)

### Estructura del repositorio

```
.
├── es/   PDFs en español (17 cheatsheets + versión completa)
└── en/   PDFs en inglés  (17 cheatsheets + versión completa)
```

### Aviso

Este material es **no oficial** y no está afiliado a Microsoft. Son apuntes personales de preparación: contrasta siempre los detalles con la documentación oficial, porque los servicios de Azure cambian con frecuencia (varias retiradas y cambios de valores por defecto de 2025 y 2026 están reflejados a fecha de octubre de 2026). Si encuentras un error, abre un *issue*.

### Licencia

[CC BY 4.0](LICENSE). Puedes copiar, redistribuir y adaptar este material, incluso con fines comerciales, siempre que cites la fuente.
