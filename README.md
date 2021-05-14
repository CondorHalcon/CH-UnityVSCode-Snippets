# unity-vscode-snippets README

Unity VSCode Snippets is a Unity C# snippet extention built for VSCode.

Author: [@CondorHalcon](https://github.com/CondorHalcon)

[Wiki](https://github.com/CondorHalcon/unity-vscode-snippets/wiki)

### Contents
- [Features](#features)
- [Requirments](#requirements)
- [Known Issues](#known-issues)
- [Release Notes](#release-notes-v100-alpha1---2021-02-13)

## Features

- Unity C# snippets

## Requirements
### Minimum
- VSCode 1.53.0

### Recomended
- VSCode 1.53.0
- Unity 2019.4LTS

## Known Issues
None

## Release Notes [v1.1.0-alpha] - 2021-05-14
> All [changelogs](https://github.com/CondorHalcon/unity-vscode-snippets/wiki/CHANGELOGS) page.

### Added
- Object class
  - Object.hideFlags `hideFlags`
  - Object.name `name`
  - Object `class Object`
  - Object.GetInstanceID `GetInstanceID()`
  - Object.ToString `ToString()`
  - Object.Destroy `Object.Destroy`
  - Object.DestroyImmediate `DestroyImmediate(Object obj, bool allowDestroyingAssets = false);`
  - Object.DontDestroyOnLoad `DontDestroyOnLoad(Object target);`
  - Object.FindObjectOfType
    - `FindObjectOfType(Type type)`
    - `FindObjectOfType<type>()`
  - Object.FindObjectsOfType
    - `FindObjectsOfType(Type type)`
    - `FindObjectsOfType<Type type>()`
  - Object.Instantiate
    - `Instantiate(Object original);`
    - `Instantiate(Object original, Transform parent);`
    - `Instantiate(Object original, Transform parent, bool instantiateInWorldSpace);`
    - `Instantiate(Object original, Vector3 position, Quaternion rotation);`
    - `Instantiate(Object original, Vector3 position, Quaternion rotation, Transform parent);`
    