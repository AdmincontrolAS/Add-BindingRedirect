## !!!Deprecated!!!! Do not use

# Add-BindingRedirect

A command-line equivalent for the NuGet Add-BindingRedirect PowerShell command.

Credits goes to [Andrew Harcourt](https://github.com/uglybugger). This project has been forked from [Add-BindingRedirect](https://github.com/uglybugger/Add-BindingRedirect)

Publish for windows

    dotnet publish -c release -r win-x64 --self-contained  /p:platform=AnyCPU /p:PublishSingleFile=true /p:IncludeNativeLibrariesForSelfExtract=true

Publish for ubuntu

    dotnet publish -c release -r ubuntu.20.04-x64 --self-contained /p:platform=AnyCPU /p:PublishSingleFile=true /p:IncludeNativeLibrariesForSelfExtract=true
