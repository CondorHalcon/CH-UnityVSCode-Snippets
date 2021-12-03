# Features

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