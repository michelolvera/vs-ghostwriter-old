# This repo is deprecated

The new repo with the latest updates is: [https://github.com/michelolvera/vs-ghostwriter](https://github.com/michelolvera/vs-ghostwriter).

# vs-ghostwriter

Fork of [Ghostwriter](https://github.com/wereturtle/ghostwriter). A beautiful cross-platform markdown editor, however this fork is intended to be compiled into VS 2017 (MSVC) x64 for Windows only.

This repository arises from the need to have a ghostwriter functional Windows version because, as [announced by wereturtle](https://github.com/wereturtle/ghostwriter/issues/367), will no longer provide updates for Windows.

## Changes to the original structure

Each library used by ghostwriter was updated and moved to a separate VS2017 project, making it easier to maintain library updates.

## Download

You can go to the section of [releases](https://github.com/michelolvera/vs-ghostwriter/releases), there you will find the installer for Windows of the most recent version and the previous ones.

> For this program to work properly, you need to install [**Microsoft Visual C++ 2015-2019**](https://support.microsoft.com/help/2977003/the-latest-supported-visual-c-downloads), otherwise you will get an error "**VCRUNTIME140_1.dll not found**"

> Another workaround (if you don't want to install the software) is to download **VCRUNTIME140_1.dll** inside the extracted folder. More informations about this file [here](https://www.dll-files.com/vcruntime140_1.dll.html).

## How to build

First of all, the following is necessary:

- Visual Studio 2019 (Desktop Development with **C++ installed**).
- Qt 5.8 (MSVC 2017 64-bit) or greater.
- Clone the repository or download the source code of the latest released version.

Having all the requirements already mentioned, open the `ghostwriter.sln` project file and compile it in x64 release.

Easy, don't you think?

**If you have problems, you should check the access routes to Qt.**

## Bug Report

This fork will try to be as faithful as possible to the original ghostwriter code, therefore, before reporting any error try to do the following:

1. Make sure the error is not already in the [original repository issues](https://github.com/wereturtle/ghostwriter/issues).
2. If the error can be replicated in Linux ghostwriter, report it [here](https://github.com/wereturtle/ghostwriter/issues).

If none of the above steps apply to you, feel free to create a report [here](https://github.com/michelolvera/vs-ghostwriter/issues)


