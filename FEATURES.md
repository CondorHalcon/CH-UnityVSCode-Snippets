# Features

- [Assemblies](#assemblies)
- [UnityEngine.CoreModule](#unityenginecoremodule)
  - [Attributes](#attributes)
  - [Component Class](#component-class)
  - [GameObject Class](#gameobject-class)
  - [Object class](#object-class)

## Assemblies
Name | Prefix
-----|-------
UnityEditor | `using UnityEditor;`
UnityEngine.CoreModule | `using UnityEngine;`
UnityEngine.UIModule | `using UnityEngine.UI;`

## UnityEngine.CoreModule

### Attributes
Name | Prefix
-----|-------
HeaderAttribute | `[Header("header")]`
HideInInspector  | `[HideInInspector]`
RangeAttribute | `[Range(x,y)]`
SerializeField | `[SerializeField]`
TooltipAttribute | `[Tooltip("tooltip")]`

### Component class
Name | Prefix
-----|-------
Component.gameObject | `gameObject`
Component.tag | `tag`
Component.transform | `transform`
Component.BroadcastMessage | `BrodacastMessage(string methodName, object parameter, SendMessageOptions options)`, `BrodacastMessage(string methodName,SendMessageOptions options)`
Component.CompareTag | `CompareTag(string tag)`
Component.GetComponent | `GetComponent(Type type)`, `GetComponent<Type type>()`, `GetComponent(string type)`
Component.GetComponentInChildren | `GetComponentInChildren(Type type)`, `GetComponentInChildren<Type type>()`
Component.GetComponentInParent | `GetComponentInParent(Type type)`, `GetComponentInParent<Type type>()`
Component.GetComponents | `GetComponents(Type type)`, `GetComponents<Type type>()`
Component.GetComponentsInChildren | `GetComponentsInChildren(Type type, bool includeInactive)`, `GetComponentsInChildren<${1:Type type}>(${1:bool includeInactive})`
Component.GetComponentsInParent | `GetComponentsInParent(Type t, bool includeInactive)`, `GetComponentsInParent<Type type>()`, `GetComponentsInParent<Type type>(bool includeInactive)`
Component.SendMessage | `SendMessage(string methodName)`, `SendMessage(string methodName, object value)`, `SendMessage(string methodName, object value, SendMessageOptions options)`, `SendMessage(string methodName,SendMessageOptions options)`
Component.SendMessageUpwards | `SendMessageUpwards(string methodName, SendMessageOptions options)`, `SendMessageUpwards(string methodName, object value, SendMessageOptions options)`
Component.TryGetComponent | `TryGetComponent(Type type, out Component component)`, `TryGetComponent(out Component component)`

### GameObject class
Name | Prefix
-----|-------
GameObject.activeInHierarchy | `activeInHeirachy`
GameObject.activeSelf | `activeSelf`
GameObject.isStatic | `isStatic`
GameObject.layer | `layer`
GameObject.scene | `scene`
GameObject.sceneCullingMask | `sceneCullingMask`
GameObject.tag | `tag`
GameObject.transform | `transform`
GameObject Constructor | `new GameObject()`, `new GameObject(string name)`, `new GameObject(string name, params Type[] components)`
GameObject.AddComponent | `AddComponent(string className)`, `AddComponent(Type componentType)`, `AddComponent<Type componentType>()`
GameObject.BroadcastMessage | `BroadcastMessage(string methodName, object parameter = null, SendMessageOptions options = SendMessageOptions.RequireReceiver)`, `BroadcastMessage(string methodName)`, `BroadcastMessage(string methodName, object parameter = null)`
GameObject.CompareTag | `CompareTag(string tag)`
GameObject.GetComponent | `GetComponent(Type type)`, `GetComponent<Type type>()`, `GetComponent(string type)`
GameObject.GetComponentInChildren |  `GetComponentInChildren(Type type)`, `GetComponentInChildren(Type type, bool includeInactive = false)`, `GetComponentInChildren<Type type>()`, `GetComponentInChildren<Type type>(bool includeInactive = false)`
GameObject.GetComponentInParent | `GetComponentInParent(Type type)`, `GetComponentInParent<Type type>()`
GameObject.GetComponents | `GetComponents(Type type)`, `GetCompomenents<Type type>()`, `GetComponents(Type type, List<Component> results)`, `GetComponents(List<T> results)`
GameObject.GetComponentsInChildren | `GetComponentsInChildren(Type type, bool includeInactive = false)`, `GetComponentsInChildren<Type type>(bool includeInactive)`, `GetComponentsInChildren(List<T> results)`, `GetComponentsInChildren<Type type>(List<T> results)`, `GetComponentsInChildren(bool includeInactive, List<T> results)`, `GetComponentsInChildren<Type type>(bool includeInactive, List<T> results)`
GameObject.GetComponentsInParent | `GetComponentsInParent(Type type, bool includeInactive = false)`, `GetComponentsInParent<Type type>(bool includeInactive = false)`, `GetComponentsInParent(bool includeInactive, List<T> results)`, `GetComponentsInParent<Type type>(bool includeInactive, List<T> results)`
GameObject.SendMessage | `SendMessage(string methodName, object value = null, SendMessageOptions options = SendMessageOptions.RequireReceiver)`
GameObject.SendMessageUpwards | `SendMessageUpwards(string methodName, object value = null, SendMessageOptions options = SendMessageOptions.RequireReceiver)`
GameObject.SetActive | `SetActive(bool value)`
GameObject.TryGetComponent | `TryGetComponent(Type type, out Component component)`, `TryGetComponent(out T component)`
GameObject.FindWithTag | `FindWithTag(string tag)`

### Object class
Name | Prefix
-----|-------
Object.hideFlags | `hideFlags`
Object.name | `name`
Object child class | `class Object`
Object.GetInstanceID | `GetInstanceID()`
Object.ToString | `ToString()`
Object.Destroy | `Object.Destroy`
Object.DestroyImmediate | `DestroyImmediate(Object obj, bool allowDestroyingAssets = false);`
Object.DontDestroyOnLoad | `DontDestroyOnLoad(Object target);`
Object.FindObjectOfType | `FindObjectOfType(Type type)`, `FindObjectOfType<type>()`
Object.FindObjectsOfType | `FindObjectsOfType(Type type)`, `FindObjectsOfType<Type type>()`
Object.Instantiate | `Instantiate(Object original);`, `Instantiate(Object original, Transform parent);`, `Instantiate(Object original, Transform parent, bool instantiateInWorldSpace);`, `Instantiate(Object original, Vector3 position, Quaternion rotation);`, `Instantiate(Object original, Vector3 position, Quaternion rotation, Transform parent);`