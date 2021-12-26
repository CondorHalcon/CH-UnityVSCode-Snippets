# CH UnityVSCode Snippets

Unity VSCode Snippets is a Unity C# snippet extention built for VSCode.

Author: [@CondorHalcon](https://github.com/CondorHalcon)

### Contents
- [Features](#features)
- [Requirments](#requirements)
- [Known Issues](#known-issues)
- [Release Notes](#release-notes-v100-alpha1---2021-02-13)

## Features
> Full [features](https://github.com/CondorHalcon/CH-UnityVSCode-Snippets/FEATURES.md).

### Snippets
- UnityEngine.CoreModule
  - Component class
  - Object class

## Requirements
item | Minimum | Recomended
-------|---------|-----------
VSCode | 1.53.0  | 1.53.0
Unity  | -       | 2019.4LTS

## Known Issues
None

## Release Notes [v1.3.0-alpha]
> Full [CHANGELOGS](https://github.com/CondorHalcon/CH-UnityVSCode-Snippets/CHANGELOG.md).

### Added
- GameObject class
  - GameObject.activeInHierarchy `activeInHeirachy`
  - GameObject.activeSelf `activeSelf`
  - GameObject.isStatic `isStatic`
  - GameObject.layer `layer`
  - GameObject.scene `scene`
  - GameObject.sceneCullingMask `sceneCullingMask`
  - GameObject.tag `tag`
  - GameObject.transform `transform`
  - GameObject Constructor
    - `new GameObject()`
    - `new GameObject(string name)`
    - `new GameObject(string name, params Type[] components)`
  - GameObject.AddComponent
    - `AddComponent(string className)`
    - `AddComponent(Type componentType)`
    - `AddComponent<Type componentType>()`
  - GameObject.BroadcastMessage
    - `BroadcastMessage(string methodName, object parameter = null, SendMessageOptions options = SendMessageOptions.RequireReceiver)`
    - `BroadcastMessage(string methodName)`
    - `BroadcastMessage(string methodName, object parameter = null)`
  - GameObject.CompareTag `CompareTag(string tag)`
  - GameObject.GetComponent
    - `GetComponent(Type type)`
    - `GetComponent<Type type>()`
    - `GetComponent(string type)`
  - GameObject.GetComponentInChildren
    - `GetComponentInChildren(Type type)`
    - `GetComponentInChildren(Type type, bool includeInactive = false)`
    - `GetComponentInChildren<Type type>()`
    - `GetComponentInChildren<Type type>(bool includeInactive = false)`
  - GameObject.GetComponentInParent
    - `GetComponentInParent(Type type)`
    - `GetComponentInParent<Type type>()`
  - GameObject.GetComponents
    - `GetComponents(Type type)`
    - `GetCompomenents<Type type>()`
    - `GetComponents(Type type, List<Component> results)`
    - `GetComponents(List<T> results)`
  - GameObject.GetComponentsInChildren
    - `GetComponentsInChildren(Type type, bool includeInactive = false)`
    - `GetComponentsInChildren<Type type>(bool includeInactive)`
    - `GetComponentsInChildren(List<T> results)`
    - `GetComponentsInChildren<Type type>(List<T> results)`
    - `GetComponentsInChildren(bool includeInactive, List<T> results)`
    - `GetComponentsInChildren<Type type>(bool includeInactive, List<T> results)`
  - GameObject.GetComponentsInParent
    - `GetComponentsInParent(Type type, bool includeInactive = false)`
    - `GetComponentsInParent<Type type>(bool includeInactive = false)`
    - `GetComponentsInParent(bool includeInactive, List<T> results)`
    - `GetComponentsInParent<Type type>(bool includeInactive, List<T> results)`
  - GameObject.SendMessage `SendMessage(string methodName, object value = null, SendMessageOptions options = SendMessageOptions.RequireReceiver)`
  - GameObject.SendMessageUpwards `SendMessageUpwards(string methodName, object value = null, SendMessageOptions options = SendMessageOptions.RequireReceiver)`
  - GameObject.SetActive `SetActive(bool value)`
  - GameObject.TryGetComponent
    - `TryGetComponent(Type type, out Component component)`
    - `TryGetComponent(out T component)`
  - GameObject.CreatePrimitive `CreatePrimitive(PrimitiveType type)`
  - GameObject.Find `Find(string name)`
  - GameObject.FindGameObjectsWithTag `FindGameObjectsWithTag(string tag)`
  - GameObject.FindWithTag `FindWithTag(string tag)`

### Changed
- Attributes
  - HeaderAttribute `[Header(header)], []` to `[Header(header)]`
  - HideInInspector `[HideInInspector], []` to `[HideInInspector]`
  - RangeAttribute `[Range(x,y)], []` to `[Range(x,y)]`
  - SerializeField `[SerializeField], []` to `[SerializeField]`
  - TooltipAttribute `[Tooltip(tooltip)], []` to `[Tooltip(tooltip)]`
- Fixed typo : Attributes HideInspector `[HideInInpector]` to `[HideInInspector]`
