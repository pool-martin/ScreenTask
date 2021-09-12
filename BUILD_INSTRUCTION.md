# ScreenTask Build Insctruction Using Command Line

In order to Build you will need MSBuild

The procedure to install the msbuild tool and understand the parameters is in this [MS Page](https://docs.microsoft.com/en-us/visualstudio/msbuild/walkthrough-using-msbuild?view=vs-2019)


For example, the command line to build Release is:

- cd ScreenTask # To stay at csproj folder
- msbuild .\ScreenTask.csproj -p:Configuration=Release