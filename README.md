# Avalonia-NativeAOT-SingleFile

Avalonia NativeAOT SingleFile

* Recreated from template project with minimal changes
* XAML previews work
* dotnet 10
* see original project for more complex app with views, sourcegen, etc

## Build

local publish: `dotnet publish ExampleApp -c Release -r win-x64 -o _publish` ~ 31MB

upx: `upx --ultra-brute --overlay=strip ExampleApp.exe -o ExampleApp.upx.exe` ~ 9MB
