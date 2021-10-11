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
### Unity C# snippets
- Assemblies
  - UnityEditor assembly `using UnityEditor;`
  - UnityEngine.AIModule assembly `using UnityEngine.AI;`
  - UnityEngine.AndroidJNIModule assembly `using UnityEngine.AndroidJNI;`
  - UnityEngine.AnimationModule assembly `using UnityEngine.Animation;`
  - UnityEngine.AssetBundleModule assembly `using UnityEngine.AssetBundle;`
  - UnityEngine.AudioModule assembly `using UnityEngine.Audio;`
  - UnityEngine.ClothModule assembly `using UnityEngine.Cloth;`
  - UnityEngine.CoreModule assembly `using UnityEngine;`
  - UnityEngine.DirectorModule assembly `using UnityEngine.Director;`
  - UnityEngine.GameCenterModule assembly `using UnityEngine.GameCenter;`
  - UnityEngine.ImageConversionModule assembly `using UnityEngine.ImageConversion;`
  - UnityEngine.IMGUIModule assembly `using UnityEngine.IMGUI;`
  - UnityEngine.InputLegacyModule assembly `using UnityEngine.InputLegacy;`
  - UnityEngine.JSONSerializeModule assembly `using UnityEngine.JSONSerialize;`
  - UnityEngine.ParticleSystemModule assembly `using UnityEngine.ParticleSystem;`
  - UnityEngine.Physics2D assembly `using UnityEngine.Physics2D;`
  - UnityEngine.PhysicsModule assembly `using UnityEngine.Physics;`
  - UnityEngine.ScreenCaptureModule assembly `using UnityEngine.ScreenCapture;`
  - UnityEngine.SharedInternalsModule assembly `using UnityEngine.SharedInternals;`
  - UnityEngine.SubsystemsModule assembly `using UnityEngine.Subsystems;`
  - UnityEngine.TerrainModule assembly `using UnityEngine.Terrain;`
  - UnityEngine.TerrainPhysicsModule assembly `using UnityEngine.TerrainPhysics;`
  - UnityEngine.TextRenderingModule assembly `using UnityEngine.TextRendering;`
  - UnityEngine.TilemapModule assembly `using UnityEngine.Tilemap;`
  - UnityEngine.UIElementsModule assembly `using UnityEngine.UIElements;`
  - UnityEngine.UIModule assembly `using UnityEngine.UI;`
  - UnityEngine.UmbraModule assembly `using UnityEngine.Umbra;`
  - UnityEngine.UnityAnalyticsModule assembly `using UnityEngine.UnityAnalytics;`
  - UnityEngine.UnityWebRequestAssetBundleModule assembly `using UnityEngine.UnityWebRequestAssetBundle;`
  - UnityEngine.UnityWebRequestAudioModule assembly `using UnityEngine.UnityWebRequestAudio;`
  - UnityEngine.UnityWebRequestModule assembly `using UnityEngine.UnityWebRequest;`
  - UnityEngine.UnityWebRequestTextureModule assembly `using UnityEngine.UnityWebRequestTexture;`
  - UnityEngine.UnityWebRequestWWWModule assembly `using UnityEngine.UnityWebRequestWWW;`
  - UnityEngine.VehiclesModule assembly `using UnityEngine.Vehicles;`
  - UnityEngine.VideoModule assembly `using UnityEngine.Video;`
  - UnityEngine.VRModule assembly `using UnityEngine.VR;`
  - UnityEngine.WebGLModule assembly `using UnityEngine.WebGL;`
  - UnityEngine.WindModule assembly `using UnityEngine.Wind;`
  - UnityEngine.XRModule assembly `using UnityEngine.XR;`
- UnityEngine.CoreModule
  - Object class
    - Object.hideFlags `hideFlags`
    - Object.name `name`
    - Object child class `class Object`
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
    