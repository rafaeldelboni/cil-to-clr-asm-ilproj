# Compiling directly CIL to CLR Code using ILProj POC
POC to create binaries direcly using [Intermediate Language (IL) or Common Intermediate Language (CIL) or Microsoft Intermediate Language (MSIL)](https://ecma-international.org/publications-and-standards/standards/ecma-335/)
to run on the [Common Language Runtime (CLR)](https://learn.microsoft.com/en-us/dotnet/standard/clr) using ILProj tooling.  

# Requirements

## Instal Dotnet SDK
https://dotnet.microsoft.com/en-us/download


## Prerequisites
* Linux, macOS or Windows
* [.NET Core](https://dotnet.microsoft.com/download) 8.0.0 or above

## Build
```bash
dotnet build -c Release
# You can run the released version
./ILProj/bin/Release/net8.0/ILProj`
```

## Run 
```bash
dotnet run --project ILProj
```

# References 
Based on [Konard/ILProj](https://github.com/Konard/ILProj) and [rafaeldelboni/cil-to-clr-asm](https://github.com/rafaeldelboni/cil-to-clr-asm).

- https://apisuckage.wordpress.com/2010/01/04/learning-il-hello-world-in-cil  
- https://community.ibm.com/community/user/powerdeveloper/blogs/vikas-gupta/2023/02/22/debugging-with-ilasm-and-ildasm  
- https://www.codeproject.com/Articles/3778/Introduction-to-IL-Assembly-Language  
- https://natemcmaster.com/blog/2017/12/21/netcore-primitives  
- https://ecma-international.org/wp-content/uploads/ECMA-335_6th_edition_june_2012.pdf
