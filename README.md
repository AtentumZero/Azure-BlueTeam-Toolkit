# Azure-BlueTeam-Toolkit
This repository is a collection of custom Kusto Query Language (KQL) queries for running security monitoring in Microsoft's Azure cloud hosting platform. Some require some customisation before use, there are comments next to variables that require customisation detailing what steps to take. 

These queries are primarily designed for use in the Azure Sentinel and 365 Defender, although they could also form the basis of queries for use in other tools that accept KQL like Microsoft Advanced Threat Protection (ATP).

### Microsoft Sentinel queries
* [General](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Sentinel/General)
* [Active Directory](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Sentinel/Active-Directory)
* [Azure Active Directory](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Sentinel/Azure-Entra-ID)
* [Azure Key Vault](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Sentinel/Azure-Key-Vault)
* [Defender for Endpoint](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Sentinel/Defender-for-Endpoint)
* [Office 365](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Sentinel/Office-365)
* [AWS CloudTrail](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Sentinel/AWS-CloudTrail)

### Defender 365 Advanced Hunting queries
* [Email](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Defender-365/Email)
* [Networking](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Defender-365/Networking)
* [Post-compromise](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Defender-365/Post-compromise)
* [Ransomware](https://github.com/AtentumZero/Azure-BlueTeam-Toolkit/tree/main/Defender-365/Ransomware)

### Attribution
Queries in this repo are a mixture of self-written Kusto and code originally obtained from [reprise99](https://github.com/reprise99/Sentinel-Queries) and [lawndoc](https://github.com/lawndoc/AdvancedHuntingQueries).