# Protobuild.vswhere

This repository packages up the [vswhere](https://github.com/Microsoft/vswhere) tool so that Protobuild can automatically install and use it.

When Protobuild is installing VSIX packages, and when the Protobuild Manager wants to launch a Visual Studio IDE, they need to know where Visual Studio is installed.  Prior to VS 2017, this could be done by checking the registry, but newer editions require the use of vswhere in order to support side-by-side installations.
