# Change Log
All notable changes to the "unity-vscode-snippets" extension are be documented in this file.

## [v1.4.0-alpha] 2022-11-12
### Added
- Mathf class
- Quaternion class
- Vector2 class
- Vector3 class
- Vector4 class

## [v1.3.0-alpha] 2021-12-26
### Added
- GameObject class

### Changed
- Attributes
  - HeaderAttribute `[Header(header)], []` to `[Header(header)]`
  - HideInInspector `[HideInInspector], []` to `[HideInInspector]`
  - RangeAttribute `[Range(x,y)], []` to `[Range(x,y)]`
  - SerializeField `[SerializeField], []` to `[SerializeField]`
  - TooltipAttribute `[Tooltip(tooltip)], []` to `[Tooltip(tooltip)]`

## [v1.2.0-alpha] - 2021-11-18
### Added
- Attributes
  - HeaderAttribute `[Header(header)], []`
  - HideInInspector `[HideInInspector], []`
  - RangeAttribute `[Range(x,y)], []`
  - SerializeField `[SerializeField], []`
  - TooltipAttribute `[Tooltip(tooltip)], []`
- Component class

### Removed
- Assemblies
  - UnityEngine.AIModule assembly `using UnityEngine.AI;`
  - UnityEngine.AndroidJNIModule assembly `using UnityEngine.AndroidJNI;`
  - UnityEngine.AnimationModule assembly `using UnityEngine.Animation;`
  - UnityEngine.AssetBundleModule assembly `using UnityEngine.AssetBundle;`
  - UnityEngine.AudioModule assembly `using UnityEngine.Audio;`
  - UnityEngine.ClothModule assembly `using UnityEngine.Cloth;`
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
- Object class
  - Object child class `class Object`

## [v1.1.0-alpha] - 2021-05-14
### Added
- Object class

## [v1.0.0-alpha.1] - 2021-02-13
### Added
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
