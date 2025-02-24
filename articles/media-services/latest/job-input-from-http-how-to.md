---
title: Create a job input from an HTTPS URL
description: This topic demonstrates how to create an Azure Media Services Job input from an HTTPS URL.
services: media-services
documentationcenter: ''
author: IngridAtMicrosoft
manager: femila
editor: ''
ms.service: media-services
ms.workload: 
ms.topic: how-to
ms.date: 08/31/2020
ms.author: inhenkel
---

# Create a job input from an HTTPS URL

[!INCLUDE [media services api v3 logo](./includes/v3-hr.md)]

In Media Services v3, when you submit Jobs to process your videos, you have to tell Media Services where to find the input video. One of the options is to specify an HTTPS URL as a job input (as shown in this example). Note that currently, AMS v3 does not support chunked transfer encoding over HTTPS URLs. For a full example, see this [GitHub sample](https://github.com/Azure-Samples/media-services-v3-dotnet-quickstarts/blob/master/AMSV3Quickstarts/EncodeAndStreamFiles/Program.cs).

> [!TIP]
> Before you start developing, review [Developing with Media Services v3 APIs](media-services-apis-overview.md) (includes information on accessing APIs, naming conventions, etc.)

## Methods

## [.NET](#tab/net/)

## .NET sample

The following code shows how to create a job with an HTTPS URL input.

[!code-csharp[Main](../../../media-services-v3-dotnet-quickstarts/AMSV3Quickstarts/EncodeAndStreamFiles/Program.cs#SubmitJob)]

---
