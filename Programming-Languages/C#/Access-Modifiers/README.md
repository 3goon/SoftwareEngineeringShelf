# C# Access Modifiers

## Types
- **public** : The type or member can be accessed by __any__ other code in the same assembly or another assembly that references it.
- **private** :  The type or member can be accessed only by code in the __same__ `class` or `struct`
- **protected** : The type or member can be accessed __only by code in the same `class`__, or in a `class` that is __derived__ from that `class`.
- **internal** : The type or member can be accessed by __any__ code in the same __assembly__, but not from another assembly.
- **protected internal** : The type or member can be accessed by __any code in the assembly__ in which it's declared, or from within a __derived `class` in another assembly__.
- **private protected** : The type or member can be accessed by types __derived__ from the `class` that are __declared within its containing assembly__.
- **file** (C# 11): The file modifier restricts a top-level type's scope and visibility to the `file` in which it's declared.