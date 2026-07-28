# DSC v3 Resources List

A curated list of Microsoft Desired State Configuration **v3 (DSCv3)** resources, powered by both the **community** and **Microsoft**.

> **Starting point:** New to DSC v3? Begin with the official Microsoft DSC repository — [PowerShell/DSC](https://github.com/PowerShell/DSC). See the [Get Started guide](https://github.com/PowerShell/DSC/blob/main/docs/get-started/index.md) for installation and your first configuration.

| Resource / Project | Hosted by | Maintainer(s) | Type | Short description | GitHub | PS Gallery |
| --- | --- | --- | --- | --- | --- | --- |
| **AzureDevOpsDscv3** | Community | Michal Machniak (`mimachniak`) | Community | Refactored, DSC v3–compatible version of the DSC Community's `AzureDevOpsDsc`. Manages Azure DevOps organizations, projects, users, groups, and project/organization permissions. Published to the PowerShell Gallery. | [GitHub](https://github.com/mimachniak/AzureDevOpsDscv3) | [PS Gallery](https://www.powershellgallery.com/packages/AzureDevOpsDscv3) |
| **AzureConnectedMachineDscV3** | Community | Michal Machniak (`mimachniak`) | Community | DSC v3 resource for managing the state and configuration of the **Azure Arc for Servers** agent (`azcmagent`). Exposes `Microsoft.Azure.Arc/AgentConfiguration`. | [GitHub](https://github.com/mimachniak/AzureConnectedMachineDscV3) | — |
| **GitDsc** | Microsoft | `microsoft/winget-dsc` | Microsoft | PowerShell-based DSC resources for managing **Git** state — cloning repositories, configuring Git settings, and related operations. Part of the WinGet DSC resource collection. | [GitHub](https://github.com/microsoft/winget-dsc/tree/main/resources/GitDsc) | [PS Gallery](https://www.powershellgallery.com/packages/GitDsc/0.1.6-alpha) |
| **OpenDSC** | Community | Thomas Nieto (`ThomasNieto`), Gijs Reijn (`Gijsreyn`) | Community | An open platform for developing, managing, and operating Microsoft DSC environments. Cross-platform (Windows, Linux, macOS) with automatic **drift detection & remediation**, .NET resource libraries, an LCM service, and a centralized pull server. | [GitHub](https://github.com/opendsc/opendsc) ([Website](https://opendsc.dev/)) | — |
| **PSResourceGet (DSC)** | Microsoft | `PowerShell/PSResourceGet` | Microsoft | DSC v3 resources shipped with **PSResourceGet** for managing PowerShell repositories and installed resources (`repository`, `psresourcelist`). | [GitHub](https://github.com/PowerShell/PSResourceGet/tree/master/src/dsc) | — |

## Tools

Utilities and helper modules that make working with DSC v3 easier.

| Tool | Hosted by | Maintainer(s) | Type | Short description | GitHub | PS Gallery |
| --- | --- | --- | --- | --- | --- | --- |
| **DSC-DocsGenerator** | Community | Michal Machniak (`mimachniak`) | Community | Generates Markdown compliance/drift reports from a DSC v3 YAML configuration. Runs `dsc config test`, parses the results, and produces a report with a configuration summary, resource overview, and desired-vs-actual state per resource (`Invoke-DSCDrifftDocs`). | [GitHub](https://github.com/mimachniak/DSC-DocsGenerator) | [PS Gallery](https://www.powershellgallery.com/packages/DSC-DocsGenerator) |
| **PSDSC** | Community | Gijs Reijn (`Gijsreyn`) | Community | PowerShell 7+ module that wraps the `dsc.exe` CLI with idiomatic cmdlets. Adds tab-completion for resources, flexible input types (hashtable/JSON/YAML), conversion of v1/v2 DSC documents, and authoring helpers for JSON/YAML v3 configuration documents. | [GitHub](https://github.com/Gijsreyn/PSDSC) | [PS Gallery](https://www.powershellgallery.com/packages/PSDSC/) |
| **OpenDSC** | Community | Thomas Nieto (`ThomasNieto`), Gijs Reijn (`Gijsreyn`) | Community | Complete platform and tooling for Microsoft DSC — deploy and manage configurations across Windows, Linux, and macOS with automatic drift detection & remediation, .NET resource libraries, an LCM service, and a centralized pull server. | [GitHub](https://github.com/opendsc/opendsc) | — ([Website](https://opendsc.dev/)) |
