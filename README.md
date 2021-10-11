# Name

Notepad++ Speech Plugin


## Description

The original plugin was posted here:
https://sourceforge.net/projects/npp-plugins/files/SpeechPlugin/

Uses Windows' Text-To-Speech engine to read Notepad++ documents.


## Compiling

I compiled with MS Visual Studio Community 2019 and this seems to work 
OK.

For 32-bit:
```
  [x86 Native Tools Command Prompt for VS 2017]
  C:\> set Configuration=Release
  C:\> set Platform=x86
  C:\> msbuild
```

For 64-bit:
```
  [x64 Native Tools Command Prompt for VS 2017]
  C:\> set Configuration=Release
  C:\> set Platform=x64
  C:\> msbuild
```

## Installation

Copy the:

+ 32-bit:  ./bin/SpeechPlugin.dll
+ 64-bit:  ./bin64/SpeechPlugin.dll

to the Notepad++ plugins folder:
  - In N++ <7.6, directly in the plugins/ folder
  - In N++ >=7.6, in a directory called SpeechPlugin in the plugins/ folder
    (plugins/SpeechPlugin/)
