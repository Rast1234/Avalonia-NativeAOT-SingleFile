# Avalonia-NativeAOT-SingleFile

Avalonia NativeAOT SingleFile

* Recreated from template project with minimal changes
* XAML previews work
* dotnet 10
* see original project for more complex app with views, sourcegen, etc

Actual diff from template in 1 commit: https://github.com/peaceshi/Avalonia-NativeAOT-SingleFile/commit/c1ec8c737bebbded323ff40a28c71695e6fabe28

## Build

local publish: `dotnet publish ExampleApp -c Release -r win-x64 -o _publish` ~ 31MB

upx: `upx --ultra-brute --overlay=strip ExampleApp.exe -o ExampleApp.upx.exe` ~ 9MB
