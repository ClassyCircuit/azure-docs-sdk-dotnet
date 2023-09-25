---
title: 
keywords: Azure, dotnet, SDK, API, Azure.ResourceManager.DefenderEasm, defendereasm
author: pallavit
ms.author: pallavit
ms.date: 09/15/2023
ms.topic: reference
ms.devlang: dotnet
ms.service: defendereasm
---
# Microsoft Azure DefenderEasm management client library for .NET

Microsoft Defender External Attack Surface Management (Defender EASM) continuously discovers and maps your digital attack surface to provide an external view of your online infrastructure. This visibility enables security and IT teams to identify unknowns, prioritize risk, eliminate threats, and extend vulnerability and exposure control beyond the firewall.

This library follows the [new Azure SDK guidelines](https://azure.github.io/azure-sdk/general_introduction.html), and provides many core capabilities:

    - Support MSAL.NET, Azure.Identity is out of box for supporting MSAL.NET.
    - Support [OpenTelemetry](https://opentelemetry.io/) for distributed tracing.
    - HTTP pipeline with custom policies.
    - Better error-handling.
    - Support uniform telemetry across all languages.

## Getting started 

### Install the package

Install the Microsoft Azure DefenderEasm management library for .NET with [NuGet](https://www.nuget.org/):

```dotnetcli
dotnet add package Azure.ResourceManager.DefenderEasm --prerelease
```

### Prerequisites

* You must have an [Microsoft Azure subscription](https://azure.microsoft.com/free/dotnet/).

### Authenticate the Client

To create an authenticated client and start interacting with Microsoft Azure resources, see the [quickstart guide here](https://github.com/Azure/azure-sdk-for-net/blob/Azure.ResourceManager.DefenderEasm_1.0.0-beta.1/doc/dev/mgmt_quickstart.md).

## Key concepts

Key concepts of the Microsoft Azure SDK for .NET can be found [here](https://azure.github.io/azure-sdk/dotnet_introduction.html)

## Documentation

Documentation is available to help you learn how to use this package:

- [Quickstart](https://github.com/Azure/azure-sdk-for-net/blob/Azure.ResourceManager.DefenderEasm_1.0.0-beta.1/doc/dev/mgmt_quickstart.md).
- [API References](/dotnet/api/?view=azure-dotnet).
- [Authentication](https://github.com/Azure/azure-sdk-for-net/blob/Azure.ResourceManager.DefenderEasm_1.0.0-beta.1/sdk/identity/Azure.Identity/README.md).

## Examples

Code samples for using the management library for .NET can be found in the following locations
- [.NET Management Library Code Samples](https://aka.ms/azuresdk-net-mgmt-samples)

## Troubleshooting

-   File an issue via [GitHub Issues](https://github.com/Azure/azure-sdk-for-net/issues).
-   Check [previous questions](https://stackoverflow.com/questions/tagged/azure+.net) or ask new ones on Stack Overflow using Azure and .NET tags.

## Next steps

For more information about Microsoft Azure SDK, see [this website](https://azure.github.io/azure-sdk/).

## Contributing

For details on contributing to this repository, see the [contributing
guide][cg].

This project welcomes contributions and suggestions. Most contributions
require you to agree to a Contributor License Agreement (CLA) declaring
that you have the right to, and actually do, grant us the rights to use
your contribution. For details, visit <https://cla.microsoft.com>.

When you submit a pull request, a CLA-bot will automatically determine
whether you need to provide a CLA and decorate the PR appropriately
(for example, label, comment). Follow the instructions provided by the
bot. You'll only need to do this action once across all repositories
using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct][coc]. For
more information, see the [Code of Conduct FAQ][coc_faq] or contact
<opencode@microsoft.com> with any other questions or comments.

<!-- LINKS -->
[cg]: https://github.com/Azure/azure-sdk-for-net/blob/Azure.ResourceManager.DefenderEasm_1.0.0-beta.1/sdk/resourcemanager/Azure.ResourceManager/docs/CONTRIBUTING.md
[coc]: https://opensource.microsoft.com/codeofconduct/
[coc_faq]: https://opensource.microsoft.com/codeofconduct/faq/