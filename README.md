# UnityMeshImporter

Runtime mesh importer for Unity using AssimpNet.

## What is Assimp? 

> Open Asset Import Library (Assimp) is a cross-platform 3D model import library which aims to provide a common application programming interface (API) for different 3D asset file formats. 
> Written in C++, it offers interfaces for both C and C++. 
> Bindings to other languages (e.g., BlitzMax, C#, Python) are developed as part of the project or are available elsewhere.
> 
> By Wikipedia
  
This project uses C# .NET wrapper for the Assimp, [AssimpNet](https://bitbucket.org/Starnick/assimpnet/src/master/)

## Quickstart

In the Packages directory of your Unity project, 
```sh
$ git clone https://github.com/eastskykang/UnityMeshImporter.git com.donghok.meshimporter
```

or

Open ```Packages/manifest.json``` and add ```"com.donghok.meshimporter":"https://github.com/eastskykang/UnityMeshImporter.git"``` to the "dependencies" list.

See [UnityMeshImportExample](https://github.com/eastskykang/UnityMeshImportExample) for an example.
