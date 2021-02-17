# Change Log
All notable changes to the "unity-vscode-snippets" extension are be documented in this file.

## [Unreleased]
### Added
- UnityEngine.CoreModule.AddComponentMenu attribute `[AddComponentMenu("${1:path}")]`
- UnityEngine.CoreModule.AddComponentMenu constructors `AddComponentMenu(${1:string menuName})`, `AddComponentMenu(${1:string menuName}, ${2:int order})`
- UnityEngine.CoreModule.AlwaysLinkAssemblyAttribute attribute `[assembly : AlwaysLinkAssembly]`
- UnityEngine.CoreModule.AndroidDevice.SetSustainedPerformanceMode method `.SetSustainedPerformanceMode(${1:bool enabled})`
- UnityEngine.CoreModule.AnimationCurve.keys property `.keys`
- UnityEngine.CoreModule.AnimationCurve.length property `.length`
- UnityEngine.CoreModule.AnimationCurve.postWrapMode property `.postWrapMode`
- UnityEngine.CoreModule.AnimationCurve.preWrapMode property `.preWrapMode`
- UnityEngine.CoreModule.AnimationCurve.this[int] property `.this[${1:int}]`
- UnityEngine.CoreModule.AnimationCurve constructors `AnimationCurve(${1:Keyframe[] keys})`, `AnimationCurve()`
- UnityEngine.CoreModule.AnimationCurve.AddKey methods `.AddKey(${1:float time}, ${2:float value})`, `.AddKey(${1:Keyframe key})`
- UnityEngine.CoreModule.AnimationCurve.Evaluate method `.Evaluate(${1:float time})`
- UnityEngine.CoreModule.AnimationCurve.MoveKey method `.MoveKey(${1:int index}, ${2:Keyframe key})`
- UnityEngine.CoreModule.AnimationCurve.RemoveKey method `.RemoveKey(${1:int index})`
- UnityEngine.CoreModule.AnimationCurve.SmoothTangents method `.SmoothTangents(${1:int index}, ${2:float weight})`

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
