# Blog-Blazor-Example-Project
This is an example project that serves as a reference for my blog (https://blog.developbyter.com)

## Project Information

### Start debugging with Hot Reloading
 - Start Developer-PowerShell in Visual Studio
 - Start 'ServerApi' project
  ```
 dotnet watch run --project src\Presentation\Server
 ```
 - Open https://localhost:7144 in your browser (most of the time the browser opens by itself)
 - On the first change i have to confirm the rebuild of the application with a (always) in the console.

### Code formatting
 - Open Developer-PowerShell (strg + )
 - Run command:
 ```dotnet format -v diag```
 or
 ```dotnet format --verbosity diagnostic```
