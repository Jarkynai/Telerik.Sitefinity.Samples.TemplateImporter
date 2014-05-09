Telerik.Sitefinity.Samples.TemplateImporter
===========================================

[![Build Status](http://sdk-jenkins-ci.cloudapp.net/buildStatus/icon?job=Telerik.Sitefinity.Samples.TemplateImporter.CI)](http://sdk-jenkins-ci.cloudapp.net/job/Telerik.Sitefinity.Samples.TemplateImporter.CI/)

The Template Importer sample project comes together with the Template Importer Module that enables you to import in your Sitefinity site any website template created through the Sitefinity Template Builder.

Using the Template Importer sample, you can:

* Create page templates 
* Create layout widgets 
* Add content items 


### Requirements

* Sitefinity license

* .NET Framework 4

* Visual Studio 2012

* Microsoft SQL Server 2008R2 or later versions

### Prerequisites

Clear the NuGet cache files. To do this:

1. In Windows Explorer, open the **%localappdata%\NuGet\Cache** folder.
2. Select all files and delete them.


### Installation instructions: SDK Samples from GitHub


1. In Solution Explorer, navigate to _SitefinityWebApp_ -> *App_Data* -> _Sitefinity_ -> _Configuration_ and select the **DataConfig.config** file. 
2. Modify the **connectionString** value to match your server address.
3. Build the solution.


The project refers to the following NuGet packages:

**SitefinityWebApp** library

* Telerik.Sitefinity.All.nupkg


**TemplateImporter** library

* Telerik.Sitefinity.Content.nupkg

* Telerik.Web.UI.nupkg

* Telerik.Sitefinity.Core.nupkg

* Telerik.DataAccess.Core.nupkg



**Telerik.Sitefinity.Samples.Common** library


* Telerik.Sitefinity.Core.nupkg

* Telerik.DataAccess.Core.nupkg

* Telerik.Sitefinity.Content.nupkg
 
You can find the packages in the official [Sitefinity Nuget Server](http://nuget.sitefinity.com).

### Login

To login to Sitefinity backend, use the following credentials: 

**Username:** admin

**Password:** password


### Additional resources

[Developers Guide](http://www.sitefinity.com/documentation/documentationarticles/developers-guide)

[Template Builder](http://www.sitefinity.com/documentation/documentationarticles/template-builder)
