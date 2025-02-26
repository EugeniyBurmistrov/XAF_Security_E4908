<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128594809/22.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4908)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Role-based Access Control, Permission Management, and OData / Web / REST API Services for Entity Framework and XPO ORM

For general information, please review [our landing page](https://www.devexpress.com/products/net/application_framework/security.xml), [Backend Web API Service](https://docs.devexpress.com/eXpressAppFramework/403394/backend-web-api-service), and watch [the overview video](https://www.youtube.com/watch?v=sIhWOXRWlOw).

## Demos and Step-By-Step Tutorials for .NET 6 and .NET Framework
Please research the information below, because additional prerequisites may apply to certain platforms. If you cannot compile or run any of these demo apps or have questions about our tutorials or supported functionality, please submit questions in the [Support Center](https://www.devexpress.com/ask) or [the Issues tab above](https://github.com/DevExpress-Examples/XAF_how-to-use-the-integrated-mode-of-the-security-system-in-non-xaf-applications-e4908/issues) - we will be more than happy to help you.

#### DevExpress XPO
 - [DevExtreme + ASP.NET Web API OData App](/XPO/ASP.NetCore/DevExtreme.OData)
 - [WinForms App](/XPO/WinForms)
 - [ASP.NET WebForms App](/XPO/ASP.NET/WebForms)
 - [ASP.NET Core MVC App](/XPO/ASP.NetCore/MVC)
 - [Blazor Server App](/XPO/ASP.NetCore/Blazor.ServerSide)
 - [Xamarin Forms App](/XPO/Xamarin.Forms)
 - [Console App](/XPO/Console)

#### Microsoft Entity Framework Core
- [DevExtreme + ASP.NET Web API OData App](/EFCore/ASP.NetCore/DevExtreme.OData)
- [WinForms App](/EFCore/WinForms)
- [ASP.NET Core MVC App](/EFCore/ASP.NetCore/MVC)
- [Blazor Server App](/EFCore/ASP.NetCore/Blazor.ServerSide)
- [Console App](/EFCore/Console)

We detailed the universal integration steps for any .NET app in [this video](https://www.youtube.com/watch?v=o1q4GqFgSFE).

#### Prerequisites to Run the Demos

- [Visual Studio 2022 v17.0+](https://visualstudio.microsoft.com/vs/) with the following workloads:
  - *.NET desktop development*  |  *ASP.NET and web development*  |  *.NET Core cross-platform development*
- Download and run the [Unified Component Installer](https://www.devexpress.com/Products/Try/) or add [NuGet feed URL](https://docs.devexpress.com/GeneralInformation/116042/installation/install-devexpress-controls-using-nuget-packages/obtain-your-nuget-feed-url) to Visual Studio NuGet feeds.
  - *We recommend that you select all products when you run the DevExpress installer. It will register local NuGet package sources and item / project templates required for these tutorials. You can uninstall unnecessary components later.*
  - For the .NET Framework examples, you need to install DevExpress products with the installer.

> **NOTE** 
>
> As of Sep 17th 2021, our Role-based Access Control, Permission Management, and Web API (powered by Microsoft Entity Framework (EF Core) and DevExpress eXpress  Persistent Objects ORM) is available FREE-of-CHARGE. To register and reserve your free license, simply visit: https://www.devexpress.com/security-api-free.


## Frequently Asked Questions & Online Documentation
- [FAQ: .NET App Security & Web API](https://supportcenter.devexpress.com/ticket/details/t886740/)
- [Security (Access Control & Authentication)](https://docs.devexpress.com/eXpressAppFramework/113366/data-security-and-safety/security-system)
- [Backend Web API Service](https://docs.devexpress.com/eXpressAppFramework/403394/backend-web-api-service)

Feel free to submit additional questions in the [Support Center](https://www.devexpress.com/ask) or [the Issues tab above](https://github.com/DevExpress-Examples/XAF_how-to-use-the-integrated-mode-of-the-security-system-in-non-xaf-applications-e4908/issues) - we will be more than happy to help you.

## Target Audience & Common Usage Scenarios

- XAF developers who create non-XAF .NET apps and want to reuse existing data models and [Security System](https://docs.devexpress.com/eXpressAppFramework/113366/concepts/security-system/security-system-overview) settings (users, roles and permissions) stored in an XAF application database. Based on experience, XAF customers create custom Web and mobile UI clients with ASP.NET MVC, DevExtreme; backend servers with ASP.NET Web API/OData or Console, Windows Service, WCF apps for various administrative tasks (data modifications, report generation, scheduled workflows).

- Non-XAF developers who create standard line-of-business (LOB) apps with login, logout forms and security related functionality for any .NET UI technologies like WinForms, WPF, ASP.NET (WebForms, MVC 5, MVC Core, Razor Pages) and .NET server technologies like ASP.NET Web API/OData, WCF, etc.

Typical .NET App Security & Web API Service scenarios include the following:

- CRUD & Authorization (for instance, check user permissions, if Create, Read, Write, Delete operations are allowed for certain business classes and properties) via EF Core & XPO ORM
- Download PDF from report templates and filtered data in databases using service endpoints (aka Reports)
- Log history of data changes in databases using service endpoints (aka Audit Trail)
- Check state of input data with complex validtion rules using service endpoints (aka Validation)
- Download BLOB data stored in databases using service endpoints (aka File Attachments)
- Obtain localized captions for classes, members, and custom UI elements stored in databases using service endpoints (aka Localization)
