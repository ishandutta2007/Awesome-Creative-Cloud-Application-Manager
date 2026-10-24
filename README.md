# Awesome-Creative-Cloud-Application-Manager

# Awesome-Creative-Cloud-Application-Manager

## Top Creative Cloud Application Manager Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Self-Service Software Portals, Endpoint App Management & Self-Hosted Distribution Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Creative Cloud Application Managers**. These tools provide a self-service portal or management layer for deploying, updating, and removing applications on end-user devices—ranging from creative-focused app managers like Adobe Creative Cloud Desktop to enterprise endpoint management platforms with curated app catalogs.



**Examples** include Adobe Creative Cloud Desktop, Microsoft Company Portal (Intune), Jamf Self Service, ManageEngine Self Service Portal, VMware Workspace ONE Hub, PDQ Connect, Kandji Self Service, and NinjaOne (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding per-device SaaS fees, and controlling the application distribution pipeline. The open-source landscape is thinner than in other categories—most endpoint management is commercial—but **Distr** provides an open-source control plane for distributing applications to self-managed environments, with **Action1** offering a generous free tier for patching up to 200 endpoints.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



| Product | Description | Pricing | Free Tier Limit |

| :--- | :--- | :--- | :--- |

| **[Adobe Creative Cloud Desktop](https://helpx.adobe.com/creative-cloud/help/manage-apps-services-desktop.html)** | Adobe's app manager for downloading, installing, and updating Creative Cloud applications, managing fonts, and accessing Stock assets . | **Free** to download and use. Requires an Adobe account; paid Creative Cloud subscription for the applications themselves . | **Free Creative Cloud membership** available with limited benefits (Adobe Express, mobile apps, fonts). Paid plans for full apps . |

| **[Microsoft Company Portal (Intune)](https://learn.microsoft.com/en-us/intune/intune-service/user-help/sign-in-to-the-company-portal)** | Intune's self-service app for accessing corporate resources, installing approved apps, and managing device compliance . | Included with **Microsoft Intune** subscriptions. Intune Plan 1 starts at **$8/user/month** . | **No standalone free tier**. Included with qualifying Microsoft 365 or EMS subscriptions. Trial available. |

| **[Jamf Self Service+](https://www.jamf.com/)** | Apple-focused self-service portal for installing approved apps, requesting admin rights, and running troubleshooting scripts . | **Free for all Jamf Pro customers** . Jamf Pro pricing: **iOS $3.33/device/month**, **macOS $7.17/device/month** . | **No standalone free tier**. Requires Jamf Pro subscription. |

| **[ManageEngine Self Service Portal](https://www.manageengine.com/products/desktop-central/)** | Endpoint Central's self-service portal for publishing approved software to users/computers . | Included with **Endpoint Central** licenses. Professional: **$1.09/endpoint/month**; Enterprise: $1.37/endpoint/month . | **Free Edition**: Up to **25 endpoints** permanently. **30-day trial** of full features . |

| **[VMware Workspace ONE Intelligent Hub](https://docs.omnissa.com/)** | Unified app catalog and self-service portal for accessing corporate resources, apps, and support . | **Standard (Shared Cloud)**: **$117.99/user/year** (list via CDW) . | **No free version and no free trial** per Software Advice . |

| **[PDQ Connect](https://www.pdq.com/)** | Cloud-based endpoint management with software deployment, patching, and a curated package library . | **Per-device annual subscription** with three tiers (Basic, Plus, Premium). Published at pdq.com; self-service purchasing . | **14-day free trial** (Premium tier) with identity verification required to unlock custom packages and remote desktop . |

| **[Kandji Self Service (now Iru)](https://www.kandji.io/)** | Apple-focused self-service app for downloading curated apps and tools from IT . | **Free for all Kandji customers** . Kandji pricing: **$3.20–$8/device/month** . | **No standalone free tier**. Requires Kandji subscription. |

| **[NinjaOne](https://www.ninjaone.com/)** | Unified IT operations platform with RMM, patching, MDM, and a self-service portal . | **$1.50–$3.75/device/month** depending on volume . | **14-day free trial** . No permanent free tier. |

| **[Automox](https://www.automox.com/)** | Cloud-native patching and endpoint configuration platform with software deployment . | **Patch OS**: **$1/endpoint/month** (annual). **Automate Essentials**: custom. **Enterprise**: custom . | **Free trial** of full platform. No permanent free tier. |

| **[Rippling App Management](https://www.rippling.com/products/it)** | Unified IT platform with device management, app provisioning, and zero-touch deployment . | **Starting at $8/user/month** (core HRIS); IT modules add cost . | **No free tier**. Demo available. |



## Open-Source GitHub Projects



- **[Distr](https://github.com/syllogy/distr)** [![GitHub Stars](https://img.shields.io/github/stars/syllogy/distr?style=social&color=white)](https://github.com/syllogy/distr/stargazers)  

  **The open-source software distribution platform.** Apache 2.0 licensed. Designed for software and AI companies to distribute applications to self-managed customers with minimal setup . **Features**: centralized management of deployments, artifacts, and agents; deployment automation via Helm and Docker agents; **white-label customer portal** for license management; container registry for OCI artifacts; and a rich SDK. **Deployment**: Docker Compose or Kubernetes Helm chart. **Self-hostable**—full control over the distribution pipeline . Best for software vendors and platform teams needing an open-source control plane for on-prem/BYOC application distribution.



- **[Action1](https://www.action1.com/)**  

  **The free-tier patch and app management platform.** Not fully open-source, but included for its exceptional free tier. Provides cloud-based patch management, software deployment, and endpoint visibility. **Free tier**: Up to **200 endpoints** with all features included . Best for small IT teams wanting zero-cost patching and app deployment without a commercial commitment.



### Additional Strong Open-Source Options



- **Ansible** — Agentless configuration management that can handle software deployment across Linux, Windows, and network devices. Best for scripted, reproducible app installation without a dedicated portal UI.

- **Chocolatey** — Windows package manager for automated software installation. Best as the underlying engine for a self-hosted app catalog.

- **Homebrew** — macOS package manager for command-line software installation. Best for developer-focused macOS fleets.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **Open-source options are scarce in this category**: most Creative Cloud application management is commercial endpoint management. **Distr** is the only fully open-source distribution platform found, and it targets software vendors rather than internal IT self-service portals . **Action1's free tier** (200 endpoints) is the most generous free offering but is proprietary .

- **Adobe Creative Cloud Desktop is not an enterprise self-service portal**: it manages Creative Cloud apps for individual users but lacks the curated catalog, approval workflows, and device compliance features of Intune, Jamf, or Kandji .

- **Pricing varies significantly by model**: Automox charges **$1/endpoint/month** for basic patching ; NinjaOne scales **$1.50–$3.75/device/month** ; Rippling starts at **$8/user/month** for core HRIS . Model your device/user mix before committing.

- **Free trials are standard but limited**: PDQ Connect offers **14 days** with identity verification required ; NinjaOne offers **14 days** . None offer permanent free production tiers except Action1's 200-endpoint allowance .



---



**Made for IT administrators, endpoint engineers, and organizations managing application deployment at scale.**  

Let's make Creative Cloud application management more open, self-serviceable, and appropriately scoped.
