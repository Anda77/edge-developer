---
ms.assetid: f3560505-e01f-47e5-9ad6-7a419f060fc2
description: Learn about how you can use native messaging to have your extension communicate with a companion UWP app.
title: Extensions - Packaging
author: abbycar
ms.author: abigailc
ms.date: 02/08/2017
ms.topic: article
ms.prod: microsoft-edge
keywords: edge, web development, html, css, javascript, developer
---

# Packaging Microsoft Edge extensions

So you've finally completed your extension and are ready to package it up. You might be wondering what the next steps are toward getting this in the hands of potential users. This guide is intended to teach you how to do just that.

The extension packaging guide is comprehensive in that it covers everything you'd want to know about packaging, even the finer, nitty gritty details. If you don't want to learn everything there is to know about packaging your extension, you're in luck. We've added support for extensions to ManifoldJS, an open source Node.js tool that takes the majority of your packaging woes away.

> [!NOTE]
> Submitting a Microsoft Edge extension to the Windows Store is currently a restricted capability. [Reach out to us](http://aka.ms/extension-request) with your requests to be a part of the Windows Store, and we’ll consider you for a future update.


Use the process outline below to map out your packaging adventure!


## [Extensions in the Windows Dev Center](./packaging/extensions-in-the-windows-dev-center.md)

No matter which package creation route you choose, manual or ManifoldJS, the first step is registering for a Windows Developer account and reserving the name(s) of your extension.

Once you've done this, you can either move on to [Creating and testing extension packages](./packaging/creating-and-testing-extension-packages.md) to learn how AppXs are created and manually package your extension, or go the easier route and jump to [Using ManifoldJS to package extensions](./packaging/using-ManifoldJS-to-package-extensions.md).

## [Creating and testing extension packages](./packaging/creating-and-testing-extension-packages.md)

This section of the guide walks through manual extension package creation once [you've set up your Windows Developer account and reserved your extension name(s)](./packaging/extensions-in-the-windows-Dev-Center.md). If you're curious about the finer details of packaging an extension, give this a read.

Also included is info on how to [test and unpack a packaged extension](./packaging/creating-and-testing-extension-packages.md#testing-an-appx-package). This info is relevant even if you've gone the ManifoldJS packaging route.

## [Localizing extension packages](./packaging/localizing-extension-packages.md)
The package localization step falls between creating your appxmanifest.xml file and running the final command to package your extension.
This allows you to indicate which languages your extensions supports in your Windows Store listing, and what language your extension's name appears in in Windows.

You can jump to [Localizing name and description for the Windows Store](./packaging/localizing-extension-packages.md#localizing-name-and-description-in-the-windows-store) in this section of the guide if your extension doesn't support multiple languages.

## [Using ManifoldJS to package extensions](./packaging/using-ManifoldJS-to-package-extensions.md)

The tool route for packaging your extension, ManifoldJS will package up your extension in a snap with minimal effort on your end. Provide a few Windows/Windows Store assets after filling out some AppXManifest properties and you're extension will be packaged in no time.

Once your extension is packaged, see the [testing](./packaging/creating-and-testing-extension-packages.md#testing-an-appx-package) section of Creating and testing your Microsoft Edge extension to learn how to sideload or unpack it.
