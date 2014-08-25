Pluralsight-CC-Angular-Breeze-Extra
===================================

Supporting files for the Pluralsight "SPA with Angular and Breeze" course by John Papa. 

The files included in this repository are intended to help streamline the learning process of the Pluralsight course SPA with Angular and Breeze. During the course you will create the Web project from scratch
and create the app logic using JavaScript. The course will ask you to add supporting files (found here) to jump-start the process and keep you focused on the core material of Angular and Breeze.

> Tip: If you are taking my course and you encounter an error when building the project after installing HotTowel.Angular.Breeze related to dll versions, you may want to try the latest package versions. Run these updates using the NuGet Package Manager

```
Update-Package Breeze.Server.ContextProvider.EF6

Update-Package Breeze.Server.WebApi2

Update-Package Breeze.Client

Update-Package Newtonsoft.Json
```

## Scratch
 - Data layer written in C# and .NET
 - Model library written in C# and .NET
 - Content folder with assets including CSS and Images
 
## Litmus Test
 - This is just to help folks along
 - Contains a running solution after using the contents in the scratch folder and running the 2 NuGet commands below:

 ```
  install-package EntityFramework.SqlServerCompact
  install-package HotTowel.Angular.Breeze
 ```

