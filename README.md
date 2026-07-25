<p align="center" dir="auto"><sup>This extension uses eval() for execution of Javascript, which is a security risk!!</sup></p>

# <p align="center" dir="auto">GDAddon 🤔</p>

<sup>If you're looking for modding (not addons), then use [gdmod](https://github.com/arthuro555/gdmod) instead of this.</sup>

Adds functionality for loading & deleting of addons. Each addon has a `Name` and a `Source` code, these are defined when
the addon is first loaded. To run your addons, just add `Execute (all) addons` action into a separate event.

# Basic example

![Screenshot 2025-04-05 203529](https://github.com/user-attachments/assets/7ca1260a-d176-410f-a6a4-cca0cca2e746)
![Screenshot 2025-04-06 151347](https://github.com/user-attachments/assets/ac3acc5c-e4e8-4afd-9eba-9ef7904d91d6)


# Making addons

Every addon needs a `Name` and a `Source`, the `Name` is being used to access the addon later (for example if you want to remove it). And `Source` is the JavaScript that the extension will execute from this specific addon.

Websites i recommend when writing in Javascript for Gdevelop 5 are the [gdjs documentation](https://docs.gdevelop.io/GDJS%20Runtime%20Documentation/) and the [wiki](https://wiki.gdevelop.io/gdevelop5/events/js-code/) (which has the basics)

# List of features:

## Actions

```
Load addon with name _PARAM1_ and source _PARAM2_
```

```
Remove addon with name _PARAM1_
```

```
Execute (all) addons
```

## Expressions

```
GDA::IndexByName()
```

```
GDA::NameByIndex()
```

```
GDA::ListLength()
```
