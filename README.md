# Add-BindingRedirect

A command-line equivalent for the NuGet Add-BindingRedirect PowerShell command.

Publish for windows

    dotnet publish -c release -r win-x64 --self-contained  /p:platform=AnyCPU /p:PublishSingleFile=true /p:IncludeNativeLibrariesForSelfExtract=true

Publish for ubuntu

    dotnet publish -c release -r ubuntu.20.04-x64 --self-contained /p:platform=AnyCPU /p:PublishSingleFile=true /p:IncludeNativeLibrariesForSelfExtract=true
