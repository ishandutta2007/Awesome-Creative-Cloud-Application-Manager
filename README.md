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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Unified Endpoint Management (UEM) and self-service application portal market is estimated at **$8.7B–$10.5B in 2026**, growing at a CAGR of ~18–22% fueled by hybrid enterprise fleets, multi-OS environments, and zero-trust security postures. The sector is **moderately concentrated**: foundational platform giants (such as Microsoft and VMware/Omnissa) anchor enterprise suites through bundled identity and security contracts, while specialized and mid-market vendors (such as NinjaOne, Jamf, ManageEngine, and Kandji) maintain significant share by addressing Apple-specific workflows, MSP tooling, and lean IT automation.

## SaaS/Hosted Platforms

| Product | Company Valuation / Revenue | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Company Portal (Intune)](https://learn.microsoft.com/en-us/intune/intune-service/user-help/sign-in-to-the-company-portal)** | **$3.1T+** Market Cap (Microsoft) | Intune's self-service app for accessing corporate resources, installing approved apps, and managing device compliance. | Intune Plan 1 starts at **$8.00/user/month** (annual commitment). Also included with Microsoft 365 Business Premium ($22.00/user/month). | **30-day free trial** of Microsoft Intune Plan 1 / Microsoft 365 Enterprise (supporting up to 25 user licenses); no permanent free tier. |
| **[Adobe Creative Cloud Desktop](https://helpx.adobe.com/creative-cloud/help/manage-apps-services-desktop.html)** | **$215B+** Market Cap / ~$21.5B Revenue (Adobe) | Adobe's client application manager for installing and updating Creative Cloud apps, syncing cloud assets, and managing fonts. | Client app is **Free** to install. Paid app plans start at **$9.99/month** (Lightroom) and Creative Cloud All Apps starts at **$59.99/month**. | **Free-for-ever membership** included with free Adobe ID (access to Adobe Express Free tier, 2GB cloud storage, limited Adobe Fonts, and trial downloads). |
| **[Rippling App Management](https://www.rippling.com/products/it)** | **$13.5B** Valuation | Unified IT workforce platform providing automated hardware deployment, app catalog provisioning, and zero-touch employee offboarding. | Base platform starts at **$8.00/user/month** plus a ~$35/month base fee; IT App & Device Management add-on modules start at **~$6.00/user/month**. | **No free tier or public self-serve trial**; private product walkthrough and tailored quote sandbox provided via sales demo only. |
| **[NinjaOne](https://www.ninjaone.com/)** | **$12.3B** Valuation | Unified IT operations and endpoint management platform with multi-tenant RMM, patch deployment, MDM, and end-user self-service portal. | Starts at **$1.50–$3.75/device/month** based on volume commitments and selected platform modules. | **14-day free trial** with full access to RMM, endpoint patching, and remote management features for up to 50 devices; no permanent free tier. |
| **[VMware Workspace ONE Intelligent Hub](https://docs.omnissa.com/)** | **$4.0B** Valuation / ~$1.5B ARR (Omnissa) | Enterprise unified app catalog, single sign-on launcher, and digital workspace self-service portal (formerly VMware EUC, now Omnissa). | Standard Shared Cloud edition starts at **$117.99/user/year** (~$9.83/user/month list via CDW / enterprise resellers). | **No standalone free tier and no public self-service free trial**; pilot environments require enterprise sales engagement. |
| **[Jamf Self Service+](https://www.jamf.com/)** | **$2.2B** Acquisition Value / ~$650M Revenue (Francisco Partners) | Apple-focused enterprise self-service application catalog allowing users to install approved macOS/iOS apps, run scripts, and manage privileges. | Self Service is bundled with Jamf Pro: iOS/iPadOS starts at **$3.33/device/month**, macOS starts at **$7.17/device/month** (billed annually). | **No permanent free tier**; offers a **14-day free trial** of Jamf Pro with full administrative and self-service capabilities for test devices. |
| **[ManageEngine Self Service Portal](https://www.manageengine.com/products/desktop-central/)** | **$1.5B** Revenue (~$580M ManageEngine division / Zoho Corp) | Endpoint Central's self-service portal allowing IT teams to publish curated software repositories for user self-installation. | Endpoint Central Professional edition starts at **$1.09/endpoint/month** ($104/year for 25 computers); Enterprise edition starts at **$1.37/endpoint/month**. | **Free-for-ever edition** for up to **25 endpoints** with full patch and software deployment; also offers a **30-day unrestricted trial** for larger deployments. |
| **[Kandji Self Service (now Iru)](https://www.kandji.io/)** | **$850M** Valuation | Modern Apple and multi-OS device management portal enabling zero-touch installation of pre-approved enterprise applications. | Pricing starts at **$3.20/device/month** for basic tiers and scales to **$8.00/device/month** for full enterprise device suites (annual billing, 100-device minimum). | **14-day free trial** available for qualified organizations via sales onboarding; no permanent free tier. |
| **[Automox](https://www.automox.com/)** | **$600M** Valuation | Cloud-native endpoint configuration, automated third-party software distribution, and cross-OS vulnerability remediation platform. | **Patch OS** tier starts at **$1.00/endpoint/month** (billed annually); full third-party app deployment (Automate Essentials) starts at **$3.00/endpoint/month**. | **15-day free trial** providing unrestricted access to patch deployment, worklets, and inventory reporting; no permanent free tier. |
| **[PDQ Connect](https://www.pdq.com/)** | **~$45M** Revenue / ~$300M+ PE Institutional Funding | Agent-based cloud endpoint management platform providing automated software distribution, third-party package libraries, and inventory. | **Connect Basic** tier starts at **$12.00/device/year** ($1.00/device/month); **Connect Plus** starts at **$18.00/device/year** ($1.50/device/month). | **14-day free trial** of Connect Premium (identity verification required to unlock custom package deployment and remote tools); no permanent free tier. |

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
