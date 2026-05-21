# Awesome Microsoft Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of high-quality resources for securing Microsoft cloud environments — covering Microsoft Defender XDR, Microsoft Sentinel, Microsoft Purview, and Microsoft Entra ID.

Covering Zero Trust, identity protection, threat detection, KQL hunting, data security, and compliance across the Microsoft Security ecosystem.

---

## Contents

- [Identity and Access (Entra ID)](#identity-and-access-entra-id)
- [Microsoft Defender XDR](#microsoft-defender-xdr)
  - [Defender for Endpoint](#defender-for-endpoint)
  - [Defender for Office 365](#defender-for-office-365)
  - [Defender for Cloud Apps](#defender-for-cloud-apps)
  - [Defender for Identity](#defender-for-identity)
  - [Defender for Cloud](#defender-for-cloud)
- [Microsoft Sentinel](#microsoft-sentinel)
- [Microsoft Purview](#microsoft-purview)
- [Zero Trust and Core Concepts](#zero-trust-and-core-concepts)
- [KQL and Threat Hunting](#kql-and-threat-hunting)
- [Hands-on Labs](#hands-on-labs)
- [Tools and Utilities](#tools-and-utilities)
- [Learning and Certifications](#learning-and-certifications)
- [Community and Blogs](#community-and-blogs)

---

## Identity and Access (Entra ID)

- [Microsoft Entra documentation](https://learn.microsoft.com/entra/) - Official product documentation hub for all Entra ID features and services.
- [Identity security best practices](https://learn.microsoft.com/security/identity-protection/) - Microsoft guidance on hardening identities against modern attacks.
- [Conditional Access overview](https://learn.microsoft.com/entra/identity/conditional-access/overview) - Reference for designing and deploying Conditional Access policies.
- [Passwordless authentication](https://learn.microsoft.com/entra/identity/authentication/concept-authentication-passwordless) - Concepts and deployment guidance for FIDO2, Windows Hello, and the Authenticator app.
- [Privileged Identity Management (PIM)](https://learn.microsoft.com/entra/id-governance/privileged-identity-management/) - Just-in-time and just-enough-access for privileged roles in Entra ID.
- [Zero Trust identity guidance](https://learn.microsoft.com/security/zero-trust/identity) - Microsoft's Zero Trust deployment guide for identity workloads.
- [Securing privileged access](https://learn.microsoft.com/security/privileged-access-workstations/) - End-to-end strategy for protecting administrative accounts and workstations.
- [Conditional Access Documenter](https://idpowertoys.merill.net/ca) - Export and document your Conditional Access policies as a PowerPoint presentation for review and audits.
- [Entra Mind Maps](https://entra.news/p/entra-mind-maps) - Visual mind maps of Entra ID concepts, useful for studying and presenting architecture.

---

## Microsoft Defender XDR

- [Microsoft Defender XDR overview](https://learn.microsoft.com/microsoft-365/security/defender/microsoft-365-defender) - Official documentation for the unified extended detection and response platform.
- [Advanced hunting overview](https://learn.microsoft.com/microsoft-365/security/defender/advanced-hunting-overview) - How to use the KQL-based hunting interface across all Defender XDR workloads.
- [Attack simulation training](https://learn.microsoft.com/microsoft-365/security/office-365-security/attack-simulation-training) - Simulate phishing and other attacks to measure and improve user resilience.
- [Defend against cyberthreats with Microsoft Defender XDR (Applied Skills)](https://learn.microsoft.com/en-us/credentials/applied-skills/defend-against-cyberthreats-with-microsoft-defender-xdr/) - Hands-on credential validating real-world XDR investigation and response skills.

### Defender for Endpoint

- [Defender for Endpoint documentation](https://learn.microsoft.com/microsoft-365/security/defender-endpoint/) - Official reference for endpoint detection, response, and vulnerability management.

### Defender for Office 365

- [Defender for Office 365 documentation](https://learn.microsoft.com/microsoft-365/security/office-365-security/) - Official reference for email, collaboration, and link protection.
- [Exchange Online Protection](https://learn.microsoft.com/exchange/mail-flow-best-practices/) - Mail flow, anti-spam, and anti-malware best practices for Exchange Online.

### Defender for Cloud Apps

- [Defender for Cloud Apps documentation](https://learn.microsoft.com/defender-cloud-apps/) - Official reference for CASB, SaaS security posture, and app governance.

### Defender for Identity

- [Defender for Identity documentation](https://learn.microsoft.com/defender-for-identity/) - Official reference for protecting Active Directory and Entra ID from identity-based attacks.

### Defender for Cloud

- [Microsoft Defender for Cloud documentation](https://learn.microsoft.com/azure/defender-for-cloud/) - Official reference for cloud security posture management and workload protection.
- [Microsoft Defender for Cloud community repository](https://github.com/Azure/Microsoft-Defender-for-Cloud) - Official community repo with workbooks, playbooks, PowerShell scripts, and policies.
- [Secure AI Solutions in the Cloud (Applied Skills)](https://learn.microsoft.com/en-us/credentials/applied-skills/secure-ai-solutions-in-the-cloud/) - Hands-on credential covering AI workload security with Defender for Cloud.
- [Secure Azure services with Defender for Cloud regulatory compliance (Applied Skills)](https://learn.microsoft.com/en-us/credentials/applied-skills/secure-azure-services-and-workloads-with-microsoft-defender-for-cloud-regulatory-compliance-controls/) - Hands-on credential for applying regulatory compliance controls to Azure workloads.

---

## Microsoft Sentinel

- [Microsoft Sentinel documentation](https://learn.microsoft.com/azure/sentinel/) - Official documentation for the cloud-native SIEM and SOAR platform.
- [Azure/Azure-Sentinel (GitHub)](https://github.com/Azure/Azure-Sentinel) - Official Microsoft community repository with out-of-the-box detections, hunting queries, workbooks, and playbooks.
- [Microsoft Sentinel blog](https://techcommunity.microsoft.com/category/azure-sentinel/blog/microsoftsentinelblog) - Official product blog with deployment guides, new features, and detection content.
- [Microsoft Sentinel Tech Community](https://techcommunity.microsoft.com/t5/microsoft-sentinel/ct-p/MicrosoftSentinel) - Q&A forum and discussion board for Sentinel professionals.
- [Deploy custom content from a repository](https://learn.microsoft.com/azure/sentinel/ci-cd) - How to connect GitHub or Azure DevOps to Sentinel for CI/CD-driven content deployment.
- [sentinel-as-code (GitHub)](https://github.com/microsoft/sentinel-as-code) - Official Microsoft samples for managing Sentinel resources programmatically via REST API and DevOps.

---

## Microsoft Purview

- [Microsoft Purview documentation](https://learn.microsoft.com/purview/) - Official documentation hub for all Purview compliance and data governance features.
- [Data Loss Prevention (DLP)](https://learn.microsoft.com/purview/dlp-learn-about-dlp) - Concepts, policies, and deployment guidance for protecting sensitive data across Microsoft 365.
- [Sensitivity labels overview](https://learn.microsoft.com/purview/sensitivity-labels) - How to classify and protect content with sensitivity labels in Office apps and beyond.
- [Information Protection](https://learn.microsoft.com/purview/information-protection) - End-to-end framework for discovering, classifying, and protecting sensitive information.
- [Insider Risk Management](https://learn.microsoft.com/purview/insider-risk-management) - Detect and act on risky user behavior using ML-driven policies.
- [eDiscovery](https://learn.microsoft.com/purview/ediscovery) - Tools for legal holds, search, and export of content across Microsoft 365.
- [Implement information protection and DLP with Purview (Applied Skills)](https://learn.microsoft.com/en-us/credentials/applied-skills/implement-information-protection-and-data-loss-prevention-by-using-microsoft-purview/) - Hands-on credential for DLP and sensitivity label implementation.
- [Implement retention, eDiscovery, and Communication Compliance in Purview (Applied Skills)](https://learn.microsoft.com/en-us/credentials/applied-skills/implement-retention-ediscovery-and-communication-compliance-in-microsoft-purview/) - Hands-on credential for retention and compliance investigation workflows.

---

## Zero Trust and Core Concepts

- [Microsoft Zero Trust guidance](https://learn.microsoft.com/security/zero-trust/) - Microsoft's comprehensive Zero Trust framework covering identity, endpoints, apps, data, infrastructure, and network.
- [Zero Trust architecture](https://learn.microsoft.com/security/zero-trust/architecture) - Architecture guidance and deployment plans for each Zero Trust pillar.
- [Least privilege model](https://learn.microsoft.com/security/zero-trust/deploy/privileged-access) - How to apply least-privilege principles to privileged access in a Zero Trust model.
- [Microsoft security documentation](https://learn.microsoft.com/en-us/security/) - Central hub for all Microsoft security documentation across products and frameworks.
- [Zero Trust Workshop](https://aka.ms/ztworkshop) - A workshop to help organizations understand and implement Zero Trust principles using Microsoft Security solutions.
- [Zero Trust Explorer](https://zerotrustexplorer.merill.net) - An interactive explorer for Microsoft's Zero Trust Workshop.
- [EntraExporter](https://github.com/microsoft/EntraExporter) - PowerShell module to export a local copy of an Entra (Azure AD) tenant configuration.
- [MSIdentityTools](https://azuread.github.io/MSIdentityTools/) - The Microsoft Identity Tools is an open-source PowerShell module built by the Microsoft Entra Customer Experience Engineering team and provides various tools for performing enhanced Identity administration activities. 

---

## KQL and Threat Hunting

- [KQL quick reference](https://learn.microsoft.com/azure/data-explorer/kql-quick-reference) - Essential KQL operators and syntax for analysts getting started with hunting queries.
- [Must Learn KQL (Rod Trent, GitHub)](https://github.com/rod-trent/MustLearnKQL) - Free, community-driven KQL learning series covering fundamentals through advanced scenarios for Sentinel and Defender XDR.
- [Bert-JanP/Hunting-Queries-Detection-Rules (GitHub)](https://github.com/Bert-JanP/Hunting-Queries-Detection-Rules) - Large, MITRE ATT&CK-mapped collection of ready-to-use KQL queries for Defender for Endpoint and Microsoft Sentinel, with custom detection and analytics rule templates.
- [cyb3rmik3/KQL-threat-hunting-queries (GitHub)](https://github.com/cyb3rmik3/KQL-threat-hunting-queries) - Community KQL query collection focused on threat hunting and detection for Microsoft Sentinel and Defender XDR.
- [LearningKijo/KQL (GitHub)](https://github.com/LearningKijo/KQL) - Out-of-the-box KQL hunting queries for App, Email, Identity, and Endpoint workloads in Defender XDR.
- [kqlquery.com – KQL Sources](https://kqlquery.com/posts/kql-sources-2026/) - Annually curated list of the best community KQL repositories for Sentinel and Defender XDR, maintained by Bert-Jan Pals.
- [Microsoft Defender XDR advanced hunting expert training](https://learn.microsoft.com/microsoft-365/security/defender/advanced-hunting-expert-training) - Official deep-dive training for analysts wanting to master advanced hunting.
- [KQL Search](https://www.kqlsearch.com/) - Community search engine aggregating KQL queries from dozens of GitHub repositories for Sentinel and Defender XDR.
---

## Hands-on Labs

- [Microsoft Defender XDR Ninja Training](https://techcommunity.microsoft.com/blog/microsoftthreatprotectionblog/become-a-microsoft-365-defender-ninja/1789376) - Official self-paced learning path from beginner to expert across all Defender XDR workloads.
- [Microsoft Sentinel Ninja Training](https://techcommunity.microsoft.com/blog/microsoftsentinelblog/become-a-microsoft-sentinel-ninja-the-complete-level-400-training/1246310) - Official self-paced learning path from level 100 to 400 for Microsoft Sentinel.
- [Zero Trust Lab Guide](https://microsoft.github.io/cloudlab/) - Microsoft-hosted lab environment for hands-on Zero Trust deployment practice.
- [SC-200 Lab Exercises (GitHub)](https://github.com/MicrosoftLearning/SC-200T00-Microsoft-Security-Operations-Analyst) - Official lab exercises for the SC-200 Microsoft Security Operations Analyst course.
- [SC-401 Lab Exercises (GitHub)](https://github.com/MicrosoftLearning/SC-401T00-Information-Security-Administrator) - Official lab exercises for the SC-401 Information Security Administrator course.

---

## Tools and Utilities

- [M365 Maps](https://m365maps.com) - Interactive diagrams mapping Microsoft 365 service and license feature coverage.
- [Maester](https://maester.dev/) - Open-source PowerShell-based security test automation framework for Microsoft 365 and Entra ID.
- [cmd.ms](https://cmd.ms/) - Quick-access command-line shortcuts and deep links for Microsoft cloud portals and tools.
- [msportals.io](https://msportals.io/) - Comprehensive directory of all Microsoft administrator portals in one place.
- [Microsoft 365 Message Center Archive](https://mc.merill.net/) - Searchable archive of Microsoft 365 Message Center communications for quick reference.

---

## Learning and Certifications

### SC-900 – Security, Compliance, and Identity Fundamentals

- [SC-900 exam page](https://learn.microsoft.com/certifications/sc-900/) - Official exam details and study resources for the entry-level security fundamentals certification.
- [SC-900 learning series (YouTube)](https://www.youtube.com/watch?v=3D6s2UxNI28&list=PLahhVEj9XNTc3cKjd28NUDFPrV4QcfxH5) - Official Microsoft Learn video series covering all SC-900 exam objectives.

### SC-100 – Microsoft Cybersecurity Architect

- [Study guide for Exam SC-100](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/sc-100) - Official study guide mapping exam objectives to learning resources.
- [SC-100 exam page](https://learn.microsoft.com/en-us/credentials/certifications/exams/sc-100/) - Official exam details, skills outline, and scheduling.
- [SC-100 Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/exams/sc-100/practice/assessment?assessmentId=87&assessment-type=practice) - Free official practice questions to gauge exam readiness.
- [Preparing for SC-100 (4-part series, YouTube)](https://www.youtube.com/watch?v=6-05jW9lMiM&list=PLahhVEj9XNTc0n9Kr47L8N7U1cTr3uWax) - Official Microsoft Learn video series covering all four exam domain areas.

### SC-200 – Security Operations Analyst

- [SC-200 exam page](https://learn.microsoft.com/en-us/credentials/certifications/security-operations-analyst) - Official exam details and skills measured for the SOC analyst role.
- [SC-200 Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/security-operations-analyst/practice/assessment?assessment-type=practice&assessmentId=59&practice-assessment-type=certification) - Free official practice questions to test readiness across all exam domains.
- [Preparing for SC-200 (4-part series, YouTube)](https://www.youtube.com/watch?v=M5RvEabcgZk&list=PLahhVEj9XNTcHNtYH-inn7xFJactEM7zz) - Official Microsoft Learn video series covering all SC-200 exam domains.
- [SC-200 full course (YouTube)](https://www.youtube.com/watch?v=thcE2t1TH50&list=PLahhVEj9XNTfSpvU-_iEvLJXiA0EDXkXQ) - Extended Microsoft Learn course video playlist for comprehensive SC-200 preparation.

### SC-300 – Identity and Access Administrator

- [SC-300 exam page](https://learn.microsoft.com/certifications/sc-300/) - Official exam details for the identity and access administration certification.
- [Preparing for SC-300 (YouTube)](https://www.youtube.com/watch?v=oZ0RkKVrtaM&list=PLahhVEj9XNTfkF9FZHW7FDcdcYRk9kO0d) - Official Microsoft Learn video series covering SC-300 exam objectives.

### SC-401 – Information Security Administrator

> **Note:** SC-400 (Information Protection and Compliance Administrator) was retired on May 31, 2025 and replaced by SC-401: Microsoft Certified: Information Security Administrator Associate.

- [Study guide for Exam SC-401](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/sc-401) - Official study guide for the new SC-401 exam covering Purview in the AI era.
- [Course SC-401T00-A: Protect sensitive information with Microsoft Purview in the AI era](https://learn.microsoft.com/en-us/training/courses/sc-401t00) - Official instructor-led training course aligned to the SC-401 exam.
- [SC-401 Practice Assessment](https://learn.microsoft.com/en-us/credentials/certifications/information-security-administrator/practice/assessment?assessment-type=practice&assessmentId=1801497482&practice-assessment-type=certification) - Free official practice questions for SC-401 exam preparation.
- [SC-401 Lab Exercises (GitHub)](https://github.com/MicrosoftLearning/SC-401T00-Information-Security-Administrator) - Official hands-on lab exercises for the SC-401 course.
- [SC-401 exam prep series (YouTube)](https://www.youtube.com/watch?v=V-tZlBQC2oQ&list=PLahhVEj9XNTfJjEN8nVgE812xSWKXny7q) - Official Microsoft Learn video series for SC-401 preparation.
- [SC-401 Exam Study Guide Series – Peter Rising (YouTube)](https://www.youtube.com/watch?v=b1IcZXkiuH0&list=PL9f-PbmksakAzoA0OIsrVDeguk_svijiO) - Community video series by MVP Peter Rising covering all SC-401 topics in depth.

### SC-730 – Cybersecurity Business Professional (Beta)

> **Note:** SC-730 is currently in beta and expected to be fully released in July 2026.

- [Study guide for Exam SC-730](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/sc-730?wt.mc_id=credentials_SC730_blog_wwl) - Official study guide for the new Cybersecurity Business Professional certification.
- [SC-730 certification details](https://learn.microsoft.com/en-us/credentials/certifications/cybersecurity-business-professional/?wt.mc_id=credentials_SC730_blog_wwl#certification-exams) - Exam overview, objectives, and preparation resources.

---

## Community and Blogs

### Official

- [Microsoft Security Blog](https://www.microsoft.com/security/blog/) - Official blog covering threat intelligence, product announcements, and security research.
- [Microsoft Defender XDR Blog](https://techcommunity.microsoft.com/category/microsoft-defender-xdr/blog/microsoftthreatprotectionblog) - Product team blog with monthly news digests, detection content, and deep dives.
- [Microsoft Sentinel Blog](https://techcommunity.microsoft.com/category/azure-sentinel/blog/microsoftsentinelblog) - Product team blog with detection engineering guides, new features, and SOC content.
- [Microsoft Security Experts Blog](https://techcommunity.microsoft.com/category/microsoft-security-product/blog/microsoftsecurityexperts) - Insights from Microsoft's incident response, threat hunting, and managed detection teams.
- [Microsoft Security Response Center (MSRC)](https://www.microsoft.com/en-us/msrc/blog) - Official channel for security vulnerability disclosures and patch guidance.
- [Microsoft Entra Blog](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/bg-p/Identity) - Identity team blog covering Entra ID, Conditional Access, and governance updates.
- [Microsoft Security Community Virtual Events](https://securitycommunity.microsoft.com/VirtualEvents/) - Free community webinars and virtual workshops across all Microsoft Security products.

### Community

- [Rod Trent's Blog (Substack)](https://rodtrent.substack.com/) - Microsoft Security MVP blog focused on Microsoft Sentinel, Security Copilot, and KQL.
- [Talking Security Podcast](https://podcasts.apple.com/us/podcast/talking-security-insights-from-microsoft-security-experts/id1489282005) - Podcast by Frans Oudendorp and Pouyan Khabazi covering Microsoft Defender, Entra, and Sentinel news.
- [The Microsoft Security Insights Show](https://www.microsoftsecurityinsights.com/) - Weekly show hosted by Ed Walton, Frank Grimberg, and Rod Trent covering the full Microsoft Security stack.
- [Bluesky.ms](https://bluesky.ms/) - Directory for finding and verifying Microsoft community members on Bluesky Social.
- [Microsoft Security Twitter/X list](https://x.com/i/lists/1823156970544603388?s=20) - Curated list of accounts focused on Microsoft Security topics.
- [Microsoft 365 Security & Compliance User Group](https://www.meetup.com/m365sandcug/) - The Microsoft 365 Security & Compliance User Group is an online community focused on M365 Security & Compliance tools and their implementation.

---
