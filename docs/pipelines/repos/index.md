---
title: Build source repositories
description: Build source repositories using Azure Pipelines
ms.topic: reference
ms.assetid: 6DFCFEB4-05EC-4A73-9382-A20D161A53D4
ms.date: 01/25/2023
monikerRange: '<= azure-devops'
---

# Supported source repositories

[!INCLUDE [version-lt-eq-azure-devops](../../includes/version-lt-eq-azure-devops.md)]

Azure Pipelines and Azure DevOps Server integrate with a number of version control systems. When you use any of these version control systems, you can configure a pipeline to build, test, and deploy your application.

YAML pipelines only work with certain version control systems. The following table shows all the supported version control systems and the ones that support YAML pipelines.

| Repository type | Azure Pipelines (YAML) | Azure Pipelines (classic editor) | Azure DevOps Server 2022, 2020, 2019 |
|---|---|---|---|
| [Azure Repos Git](azure-repos-git.md) | Yes | Yes | Yes |
| [Azure Repos TFVC](tfvc.md) | No | Yes | Yes |
| [GitHub](github.md) | Yes | Yes | No |
| [GitHub Enterprise Server](github-enterprise.md) | Yes | Yes | Yes |
| [Bitbucket Cloud](bitbucket.md) | Yes | Yes | No |
| [Bitbucket Server](on-premises-bitbucket.md) | No | Yes | Yes |
| Subversion | No | Yes | Yes |
