# Windows Service Example for .NET 7

Ссылка на исходник.
This is the source code example for an article I wrote called [Building Windows Services in .NET 7](https://consultwithgriff.com/building-window-services-in-dotnet/)


#### добавление в сервисы

> sc create FolderCleaner binPath= "D:\repos\Csharp\WorkerService\WindowsServiceDotNetExample\bin\Release\net8.0\publish\WindowsService.exe"
[SC] CreateService SUCCESS


> sc delete FolderCleaner