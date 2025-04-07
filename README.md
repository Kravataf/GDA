<p align="center" dir="auto"><sup>This extension uses eval() for execution of Javascript, which is a security risk!!</sup></p>

# <p align="center" dir="auto">GDAddon 🤔</p>

<sup>If you're looking for modding (not addons), then use [gdmod](https://github.com/arthuro555/gdmod) instead of this.</sup>

Adds functionality for loading & deleting of addons. Each addon has a `Name` and a `Source` code, these are defined when
the addon is first loaded. To run your addons, just add `Execute (all) addons` action into a separate event.

# How to use

I'll update this part later...

![Screenshot 2025-04-05 203529](https://github.com/user-attachments/assets/7ca1260a-d176-410f-a6a4-cca0cca2e746)
![Screenshot 2025-04-06 151347](https://github.com/user-attachments/assets/ac3acc5c-e4e8-4afd-9eba-9ef7904d91d6)


# Making addons

1. First of all, you need to have a name for your addon (this doesn't really matter, it's just used for accessing the addon later, for example when deleting)
2. The second thing you need to add when loading the addon is the `Source`, this is basically the code the addon will run. Websites i recommend when writing in Javascript for Gdevelop 5 are the [gdjs documentation](https://docs.gdevelop.io/GDJS%20Runtime%20Documentation/) and the [wiki](https://wiki.gdevelop.io/gdevelop5/events/js-code/) (which has the basics)

# Functions

`Load addon with name _PARAM1_ and source _PARAM2_` -> action

`Remove addon with name _PARAM1_` -> action

`Execute (all) addons` -> action

`GDA::IndexByName()` -> expression

`GDA::NameByIndex()` -> expression

`GDA::ListLength()` -> expression
