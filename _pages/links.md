---
title: "Links"
excerpt: "List of external resources and tools for IAM Security + Management from #Azure community, Microsoft and cloud (security) vendors"
header:
  overlay_image: /assets/images/library.jpg
  overlay_filter: rgba(102, 102, 153, 0.75)
toc: true
toc_sticky: true  
permalink: /links/
author_profile: false
---

_These links are being provided as a convenience and for informational purposes only; they do not constitute an endorsement or an approval me.
I'm not responsibility for the accuracy, legality or content of the external site or for that of subsequent links.
Contact the external site for answers to questions regarding its content._

# Microsoft Entra Management and Security Tools

## 🧰 PowerShell Modules and other Management Tools

| Name | Description from Project/Repo page | Repository | Project page/Blog |
| --- | --- | --- | --- |
| AzureAD | Azure Active Directory PowerShell for Graph (Azure AD PowerShell) is a module IT Pros commonly use to manage their Azure Active Directory. The cmdlets in the Azure AD PowerShell module enable you to retrieve data from the directory, create new objects in the directory, update existing objects, remove objects, as well as configure the directory and its features. ⚠️This module is planned for deprecation. For more details on the deprecation plans, see the [deprecation update](https://techcommunity.microsoft.com/t5/microsoft-entra-azure-ad-blog/azure-ad-change-management-simplified/ba-p/2967456) | [PowerShell Gallery: AzureAD](https://www.powershellgallery.com/packages/AzureAD) | [AzureAD Module](https://learn.microsoft.com/en-us/powershell/module/azuread/?view=azureadps-2.0) |
| Azure AD application secret rotator for Azure web sites | Azure AD App Secret Manager automates the rotation of your Azure web sites secrets integrated with user approval and notification in Microsoft Teams | [Azure/AzureAD-AppSecretManager](https://github.com/Azure/AzureAD-AppSecretManager) |  |
| AzureADExporter | The Azure AD Exporter is a PowerShell module that allows you to export your Azure AD and Azure AD B2C configuration settings to local .json files. This module can be run as a nightly scheduled task or a DevOps component (Azure DevOps, GitHub, Jenkins) and the exported files can be version controlled in Git or SharePoint. | [microsoft/azureadexporter](https://github.com/microsoft/azureadexporter) |  |
| Azure AD Toolkit | The Azure AD Toolkit is a PowerShell module that providers helper cmdlets to manage the credentials of your application or service principal. | [microsoft/AzureADToolkit](https://github.com/microsoft/AzureADToolkit) |  |
| AzADServicePrincipalInsights | Insights and change tracking on Azure Active Directory Service Principals (Enterprise Applications and Applications) | [JulianHayward/AzADServicePrincipalInsights](https://github.com/JulianHayward/AzADServicePrincipalInsights) |  |
| AzureADAssessment | The Azure AD Governance Assessment module runs an analysis of guest users and their permissions in a tenant. | [AzureAD/AzureADAssessment](https://github.com/AzureAD/AzureADAssessment) | [AzureADAssessement and PowerBI Reports (icewolf.ch)](https://blog.icewolf.ch/archive/2022/09/03/azureadassessement-and-powerbi-reports.aspx) |
| Azure AD Governance Assessment | Tooling for assessing an Azure AD tenant state and configuration | [AzureAD-Governance-Assessment](https://github.com/AzureAD/AzureAD-Governance-Assessment) | [AzureADAssessement and PowerBI Reports (icewolf.ch)](https://blog.icewolf.ch/archive/2022/09/03/azureadassessement-and-powerbi-reports.aspx) |
| Azure AD B2C Custom Policy Manager | This is a sample management tool for B2C Custom Policies. Custom policy allows you to customize every aspect of the authentication flow. | [azure-ad-b2c/custom-policy-manager](https://github.com/azure-ad-b2c/custom-policy-manager) |  |
| Azure AD B2C Load Tests | This sample intends to show how to create and run a load test of Azure AD B2C user flows and custom policies (including dependencies), and evaluate the results using the Azure Load Testing Service. Use this sample to perform a load test and determine your web application and B2C flows behavior under anticipated peak load conditions, identify bottlenecks and determine which element is causing degradation. | [azure-ad-b2c/load-tests](https://github.com/azure-ad-b2c/load-tests) |  |
| Azure AD Connect Configuration Documenter | AAD Connect configuration documenter is a tool to generate documentation of an Azure AD Connect installation. Currently, the documentation is only limited to the Azure AD Connect sync configuration. | [microsoft/AADConnectConfigDocumenter](https://github.com/microsoft/AADConnectConfigDocumenter) |  |
| AzureAuth | CLI wrapper for performing AAD Authentication. It makes use of MSAL for authentication and MSAL Extensions for caching. The CLI is designed for authenticating and returning an access token for public client AAD applications. This acts like a credential provider for Azure Devops and any other public client app. | [AzureAD/microsoft-authentication-cli](https://github.com/AzureAD/microsoft-authentication-cli) |  |
| CA Optics - Azure AD Conditional Access Gap Analyzer | Azure AD Conditional Access Gap Analyzer is a solution for scanning gaps that might exist within complex Azure Active Directory Conditional Access Policy setups. | [jsa2/caOptics](https://github.com/jsa2/caOptics) | |
| DCToolbox | A PowerShell toolbox for Microsoft 365 security fans. | [DanielChronlund/DCToolbox](https://github.com/DanielChronlund/DCToolbox) | [DCToolbox PowerShell Module for Microsoft 365 Security, Conditional Access Automation, and more](https://danielchronlund.com/2020/11/09/dctoolbox-powershell-module-for-microsoft-365-security-conditional-access-automation-and-more/) |
| EasyPIM | EasyPIM is a PowerShell module created to help you manage Microsof Entra Privileged Identity Management (PIM). Packed with more than 30 cmdlets, EasyPIM leverages the ARM and Graph APIs to let you configure PIM Azure Resources, Entra Roles and groups settings and assignments in a simple way . | [kayasax/EasyPIM](https://github.com/kayasax/EasyPIM) | |
| Fortigi ConditionalAccess | This solution consists of powershell functions, bundled in a module to help automate and regulate Conditional Access deployment and maintance. | [Fortigi/ConditionalAccess](https://github.com/Fortigi/ConditionalAccess) |  |
| Maester | Monitor your Microsoft 365 tenant's security configuration using Maester! Maester is a PowerShell-based test automation framework designed to help you monitor and maintain the security configuration of your Microsoft 365 environment. | [maester365/maester](https://github.com/maester365/maester) | [Get started - Maester.dev](https://maester.dev/docs/intro) Videos: [Microsoft365DSC YouTube Channel](https://www.youtube.com/channel/UCveScabVT6pxzqYgGRu17iw?cbrd=1) Video: [Introducing Maester: Your Microsoft 365 test automation framework by Merill Fernando](https://www.youtube.com/watch?v=xfs02tjSU24) |
| IdentityProtectionTools | The Identity Protection Tools PowerShell module contains sample functions for enumerating Risky Users by RiskLevel and date when their risk was last updated, Dismissing Risk for selected users for bulk operations, confirming Compromise for selected users for bulk operations. | [AzureAD/IdentityProtectionTools](https://github.com/AzureAD/IdentityProtectionTools) |  |
| Microsoft365DSC | This module allows organizations to automate the deployment, configuration, reporting and monitoring of Microsoft 365 Tenants via PowerShell Desired State Configuration. The compiled configuration needs to be executed from an agent's Local Configuration Manager (LCM) (machine or container) which can communicate back remotely to Microsoft 365 via remote API calls (therefore requires internet connectivity). | [microsoft/Microsoft365DSC](https://github.com/microsoft/Microsoft365DSC) | [Introduction - M365DSC.com](https://microsoft365dsc.com/) Videos: [Microsoft365DSC YouTube Channel](https://www.youtube.com/channel/UCveScabVT6pxzqYgGRu17iw?cbrd=1) |
| Microsoft Graph SDK | The Microsoft Graph PowerShell SDK is a collection of PowerShell modules that contain commands for calling Microsoft Graph service. | [microsoftgraph/msgraph-sdk-powershell](https://github.com/microsoftgraph/msgraph-sdk-powershell) | [Microsoft Graph PowerShell SDK overview](https://github.com/microsoftgraph/msgraph-sdk-powershell) Samples: [Graph PowerShell Samples Community](https://github.com/orgs/msgraph/discussions/2) |
| Microsoft Graph Developer Proxy | Microsoft Graph Developer Proxy is a command line tool for testing Microsoft Graph and other APIs. | [microsoftgraph/msgraph-developer-proxy](https://github.com/microsoftgraph/msgraph-developer-proxy) | [Introducing the Microsoft Graph Developer Proxy community preview](https://devblogs.microsoft.com/microsoft365dev/introducing-the-microsoft-graph-developer-proxy-community-preview) |
| Microsoft Cloud Group Analyzer | For Microsoft Cloud admins who struggle to keep track of where Entra ID groups are used, Group Analyzer is an opensource script that provides instant insights in what services/policies/... a given group or user is scoped to. | [asperbaes/Microsoft-Cloud-Group-Analyzer](https://github.com/jasperbaes/Microsoft-Cloud-Group-Analyzer) | |
| Microsoft Identity Tools PowerShell Module | The Microsoft Identity Tools PowerShell module provides various tools for performing enhanced Identity administration activities. It is intended to address more complex business scenarios that can't be met solely with the use of MS Graph PowerShell SDK module. | [AzureAD/MSIdentityTools](https://github.com/AzureAD/MSIdentityTools) |  |
| Microsoft Identity DotNet Analyzers | Contains static analyzers to detect bad practices in the usage of .NET authentication libraries | [AzureAD/microsoft-identity-dotnet-analyzers](https://github.com/AzureAD/microsoft-identity-dotnet-analyzers) |  |
| MSAL.PS | The MSAL.PS PowerShell module wraps MSAL.NET functionality into PowerShell-friendly cmdlets and is not supported by Microsoft. Microsoft support does not extend beyond the underlying MSAL.NET library. | [AzureAD/MSAL.PS](https://github.com/AzureAD/MSAL.PS) | [Microsoft Graph using MSAL with PowerShell - darrenjrobinson](https://blog.darrenjrobinson.com/microsoft-graph-using-msal-with-powershell/) |
| PIMScan | Tool for creating reports on Entra ID Role Assignments | [canix1/PIMSCAN](https://github.com/canix1/PIMSCAN) | |
| PSMSGraphBatchRequest | The MSGraphBatchRequest PowerShell module provides a convenient way to transform data into Microsoft Graph Batch Requests by converting PowerShell objects to JSON with proper schema validation. | [PSMSGraphBatchRequest](https://github.com/HCRitter/PSMSGraphBatchRequest) | |
| SCuBA M365 Security Baseline Assessment Tool | Developed by CISA, this assessment tool verifies that an M365 tenant’s configuration conforms to the policies described in the SCuBA Minimum Viable Secure Configuration Baseline documents. | [cisagov/ScubaGear](https://github.com/cisagov/ScubaGear) |  |
| Terraform Provider for Azure Active Directory | The Azure Provider can be used to configure infrastructure in Azure Active Directory using the Microsoft Graph API. | [hashicorp/azuread - Terraform Registry](https://registry.terraform.io/providers/hashicorp/azuread/latest) | [Docs overview](https://registry.terraform.io/providers/hashicorp/azuread/latest/docs) |



## 🛡️ Security Research Tools

| Name | Description from Project/Repo page  | Repository | Project page/Blog |
| --- | --- | --- | --- |
| AADInternals | AADInternals is PowerShell module for administering Azure AD and Office 365 | [Gerenios/AADInternals: AADInternals](https://github.com/Gerenios/AADInternals)  | [AAD Internals (aadinternals.com)](https://aadinternals.com/aadinternals/) |
| Azure AD Incident Response PowerShell Module | The Azure Active Directory Incident Response PowerShell module provides a number of tools, developed by the Azure Active Directory Product Group in conjunction with the Microsoft Detection and Response Team (DART), to assist in compromise response. | [AzureAD/Azure-AD-Incident-Response-PowerShell-Module](https://github.com/AzureAD/Azure-AD-Incident-Response-PowerShell-Module) |  |
| Entra ID Security Config Analyzer (EIDSCA) | Logic App solution to ingest configuration data of Azure AD to Log Analytics for monitoring and strengthen identity security posture. | [Cloud-Architekt/AzureAD-Attack-Defense](https://github.com/Cloud-Architekt/AzureAD-Attack-Defense/blob/main/AADSecurityConfigAnalyzer.md) |  |
| azbelt | Standalone DLL and sliver extension for enumerating Azure related credentials, primarily on AAD joined machines | [daddycocoaman/azbelt](https://github.com/daddycocoaman/azbelt) |  |
| AppTotal | Analyze suspicious OAuth apps, browser extensions and SaaS add-ons to detect harmful apps, risky permissions and other security issues. | [AppTotal.io](https://apptotal.io) |  |
| AzureHound | The BloodHound data collector for Microsoft Azure | [BloodHoundAD/AzureHound](https://github.com/BloodHoundAD/AzureHound) | [Automating Things 0x01 – AzureHound for blue teams](https://falconforce.nl/automating-things-0x01-azurehound-for-blue-teams/) |
| AzTokenFinder | Is a small tool to extract JWT (or JWT like looking data) from different processes, like PowerShell, Excel, Word or others. | [HackmichNet/AzTokenFinder](https://github.com/HackmichNet/AzTokenFinder) |  |
| AzureRT | Helpful utilities dealing with access token based authentication, switching from Az to AzureAD  and az cli interfaces, easy to use pre-made attacks such as Runbook-based command execution and more. | [mgeeky/AzureRT: AzureRT](https://github.com/mgeeky/AzureRT) |  |
| BadZure | BadZure is a PowerShell script that leverages the Microsoft Graph SDK to orchestrate the setup of Azure Active Directory tenants, populating them with diverse entities while also introducing common security misconfigurations to create vulnerable tenants with multiple attack paths. | [mvelazc0/BadZure](https://github.com/mvelazc0/BadZure/) |  |
| Bloodhound | BloodHound uses graph theory to reveal the hidden and often unintended relationships within an Active Directory or Azure environment. Attackers can use BloodHound to easily identify highly complex attack paths that would otherwise be impossible to quickly identify. Defenders can use BloodHound to identify and eliminate those same attack paths. Both blue and red teams can use BloodHound to easily gain a deeper understanding of privilege relationships in an Active Directory or Azure environment. | [BloodHoundAD/BloodHound](https://github.com/BloodHoundAD/BloodHound) | [BloodHound: Six Degrees of Domain Admin](https://bloodhound.readthedocs.io/en/latest/) |
| BloodHound Attack Research Kit /BARK) | BARK stands for BloodHound Attack Research Kit. It is a PowerShell script built to assist the BloodHound Enterprise team with researching and continuously validating abuse primitives. BARK currently focuses on Microsoft's Azure suite of products and services. | [BloodHoundAD/BARK: BloodHound](https://github.com/BloodHoundAD/BARK) |  |
| CrowdStrike Reporting Tool for Azure (CRT) | This tool queries the following configurations in the Azure AD/O365 tenant which can shed light on hard-to-find permissions and configuration settings in order to assist organizations in securing these environments. | [CrowdStrike/CRT/CRT](https://github.com/CrowdStrike/CRT) |  |
| Forest Druid | Free Tier 0 attack path discovery tool for Active Directory environments by Semperis | [Forest Druid](https://www.purple-knight.com/forest-druid/) | [Closing Attack Paths to Tier 0 Assets with Forest Druid](https://www.semperis.com/blog/closing-attack-paths-to-tier-0-assets-with-forest-druid/) |
| GraphRunner | Post-exploitation toolset for interacting with the Microsoft Graph API. It provides various tools for performing reconnaissance, persistence, and pillaging of data from a Microsoft Entra ID (Azure AD) account. | [dafthack/GraphRunner](https://github.com/dafthack/GraphRunner) | [Introducing GraphRunner: A Post-Exploitation Toolset for Microsoft 365](https://www.blackhillsinfosec.com/introducing-graphrunner/) |
| GraphSpy | Initial Access and Post-Exploitation Tool for AAD and O365 with a browser-based GUI | [RedByte1337/GraphSpy](https://github.com/RedByte1337/GraphSpy) | [GraphSpy – The swiss army knife for attacking M365 & Entra](https://insights.spotit.be/2024/04/05/graphspy-the-swiss-army-knife-for-attacking-m365-entra/#Access-&-Refresh-Tokens) |
| MAAD Attack Framework | MAAD-AF is an open-source cloud attack tool developed for testing security of Microsoft 365 & Azure AD environments through adversary emulation. MAAD-AF provides security practitioners easy to use attack modules to exploit configurations across different M365/AzureAD cloud-based tools & services. | [vectra-ai-research/MAAD-AF](https://github.com/vectra-ai-research/MAAD-AF) |  |
| Mandiant Azure AD Investigator | This repository contains a PowerShell module for detecting artifacts that may be indicators of UNC2452 and other threat actor activity. Some indicators are "high-fidelity" indicators of compromise, while other artifacts are so called "dual-use" artifacts. Dual-use artifacts may be related to threat actor activity, but also may be related to legitimate functionality. | [mandiant/Mandiant-Azure-AD-Investigator](https://github.com/mandiant/Mandiant-Azure-AD-Investigator) |  |
| MicroBurst | MicroBurst includes functions and scripts that support Azure Services discovery, weak configuration auditing, and post exploitation actions such as credential dumping. It is intended to be used during penetration tests where Azure is in use. | [NetSPI/MicroBurst](https://github.com/NetSPI/MicroBurst) | Various blog posts on: https://www.netspi.com/blog/ |
| Monkey365 | Monkey365 is an Open Source security tool that can be used to easily conduct not only Microsoft 365, but also Azure subscriptions and Azure Active Directory security configuration reviews without the significant overhead of learning tool APIs or complex admin panels from the start. To help with this effort, Monkey365 also provides several ways to identify security gaps in the desired tenant setup and configuration. Monkey365 provides valuable recommendations on how to best configure those settings to get the most out of your Microsoft 365 tenant or Azure subscription. | [silverhack/monkey365](https://github.com/silverhack/monkey365) |  |
| ROADtools | ROADtools is a framework to interact with Azure AD. It currently consists of a library (roadlib) and the ROADrecon Azure AD exploration tool. | [dirkjanm/ROADtools](https://github.com/dirkjanm/ROADtools) | [Introducing ROADtools - The Azure AD exploration framework - dirkjanm.io](https://dirkjanm.io/introducing-roadtools-and-roadrecon-azure-ad-exploration-framework/) |
| PurpleKnight | Semperis built Purple Knight—a free AD and Azure AD security assessment tool—to help you discover indicators of exposure (IoEs) and indicators of compromise (IoCs) in your hybrid AD environment. | [PurpleKnight Community](https://www.purple-knight.com/) | [Purple Knight Introduces Azure AD Security Indicators](https://www.semperis.com/blog/purple-knight-azure-security-indicators/) |
| RedCloud OS | RedCloud OS is a Debian based Cloud Adversary Simulation Operating System for Red Teams to assess the security of leading Cloud Service Providers (CSPs). It includes tools optimized for adversary simulation tasks within AWS, Azure and GCP. | [RedTeamOperations/RedCloud-OS](https://github.com/RedTeamOperations/RedCloud-OS) | |
| onedrive_user_enum | Python script to enumerate valid OneDrive users | [nyxgeek/onedrive_user_enum](https://github.com/nyxgeek/onedrive_user_enum) | [TrustedSec - OneDrive to enum them all](https://www.trustedsec.com/blog/onedrive-to-enum-them-all/) |
| SimuLand | SimuLand is an open-source initiative by Microsoft to help security researchers around the world deploy lab environments that reproduce well-known techniques used in real attack scenarios, actively test and verify effectiveness of related Microsoft 365 Defender, Azure Defender and Microsoft Sentinel detections, and extend threat research using telemetry and forensic artifacts generated after each simulation exercise. | [Azure/SimuLand](https://github.com/Azure/SimuLand) | [SimuLand: Understand adversary tradecraft and improve detection strategies - Microsoft Security Blog](https://www.microsoft.com/security/blog/2021/05/20/simuland-understand-adversary-tradecraft-and-improve-detection-strategies/) |
| Stormspotter | Stormspotter creates an “attack graph” of the resources in an Azure subscription. It enables red teams and pentesters to visualize the attack surface and pivot opportunities within a tenant, and supercharges your defenders to quickly orient and prioritize incident response work. | [Azure/Stormspotter](https://github.com/Azure/Stormspotter) |  |
| SkyArk | SkyArk currently focuses on mitigating the new threat of Cloud Shadow Admins, and helps organizations to discover, assess and protect cloud privileged entities. Stealthy and undercover cloud admins may reside in every public cloud platform and SkyArk helps mitigating the risk in AWS and Azure. | [cyberark/SkyArk](https://github.com/cyberark/SkyArk) |  |
| TeamFiltration | TeamFiltration is a cross-platform framework for enumerating, spraying, exfiltrating, and backdooring O365 AAD accounts. | [Flangvik/TeamFiltration](https://github.com/Flangvik/TeamFiltration) |  |
| TokenMan | Token Man is a tool for supporting post-exploitation activities using AAD access and/or refresh tokens. | [secureworks/TokenMan](https://github.com/secureworks/TokenMan) |  |
| TokenTactics | Azure access tokens allow you to authenticate to certain endpoints as a user who signs in with a device code. Even if they used multi-factor authentication. Once you have a user's access token, it may be possible to access certain apps such as Outlook, SharePoint, OneDrive, MSTeams and more. For instance, if you have a Graph or MSGraph token, you can then connect to Azure and dump users, groups, etc. You could then, depending on conditional access policies, switch to an Azure Core Management token and run AzureHound. Then, switch to an Outlook token and read/send emails or MS Teams and read/send teams messages! | [rvrsh3ll/TokenTactics](https://github.com/rvrsh3ll/TokenTactics) |  |
| TokenTactics v2 | A fork of TokenTactics with support for CAE and token endpoint v2. Detailed output for `Parse-JWTtoken` to display related information for longer-lived (CAE-capable) tokens. | [f-bader/TokenTacticsV2](https://github.com/f-bader/TokenTacticsV2) | [Continuous access evaluation - CloudBrothers.info](https://cloudbrothers.info/en/continuous-access-evaluation/) |
| Vajra | Vajra is a UI based tool with multiple techniques for attacking and enumerating in target's Azure environment. Vajra presently supports Azure and AWS Cloud environments, with plans to add support for Google Cloud Platform and certain OSINT in the future. | [TROUBLE-1/Vajra](https://github.com/TROUBLE-1/Vajra) |


## 🪄 Postman Collections

| Collection Name | Link to Collection/Fork | Documentation |
| --- | --- | --- |
| Azure AD v2.0 Protocols  | [Collection for Authentication Flows](https://app.getpostman.com/run-collection/f77994d794bab767596d) | [Microsoft identity platform and OAuth 2.0](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)  |
| Microsoft Graph API | [Microsoft Graph Collection](https://www.postman.com/microsoftgraph/workspace/microsoft-graph/collection/455214-085f7047-1bec-4570-9ed0-3a7253be148c/fork) | [Use Postman with the Microsoft Graph API](https://learn.microsoft.com/en-us/graph/use-postman) |
| Microsoft Threat Protection | [Microsoft-Threat-Protection/Postman at master · richlilly2004](https://github.com/richlilly2004/Microsoft-Threat-Protection/tree/master/Postman) |  |
| Verified ID | [VerifiedID Request API](https://www.postman.com/aadverifiablecredentials/workspace/ms-entra-verifiedid-api/collection/18012404-fc35776e-afb7-4795-83d8-713701882c07/fork), [VerifiedID Admin API](https://www.postman.com/aadverifiablecredentials/workspace/ms-entra-verifiedid-api/collection/18012592-bcfa1b7a-b449-4d70-98eb-96b69f32c877/fork) | [active-directory-verifiable-credentials/Postman](https://github.com/Azure-Samples/active-directory-verifiable-credentials/tree/main/Postman) |

## 🧑‍💻 Visual Studio Code Extensions

| Extension Name | Description from Project/Repo page  | Project repository | Marketplace |
| --- | --- | --- | --- |
| Azure AD B2C | The Azure AD B2C extension for VS Code lets you quickly navigate through Azure AD B2C custom policies. Create elements like technical profiles and claim definitions. For more information, see Get started with custom policies. | [azure-ad-b2c/vscode-extension](https://github.com/azure-ad-b2c/vscode-extension) | [Azure AD B2C ](https://marketplace.visualstudio.com/items?itemName=AzureADB2CTools.aadb2c)|
| MS Graph Completion | This VSCode extension allows you to auto-complete the Microsoft Graph API URLs you are writing. You get the most useful Microsoft Graph Explorer functionality in your favorite editor. | [estruyf/vscode-msgraph-autocomplete](https://github.com/estruyf/vscode-msgraph-autocomplete) | [MS Graph Completion](https://marketplace.visualstudio.com/items?itemName=eliostruyf.vscode-msgraph-autocomplete) |

<br>
<br>
<br>

Image by <a href="https://pixabay.com/users/stocksnap-894430/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2596809">StockSnap</a> from <a href="https://pixabay.com//?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2596809">Pixabay</a>