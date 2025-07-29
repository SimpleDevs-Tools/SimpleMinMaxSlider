# SimpleMinMaxSlider for Unity

![](Demonstration.gif)

# Installation

There are three ways to install this package:

## Original, Unity Package Manager method

  1. Open package manager
  2. Add package from git URL
  3. Paste: https://github.com/GucioDevs/SimpleMinMaxSlider.git#upm (remember the #upm at the end)
  4. Let Unity do its thing
  5. Done.

## Unity Custom Package method

  1. Download the custom `.unitypackage` version from the available releases.
  2. `Assets` -> `Import Package` -> `Custom Package` -> select the package you just downloaded.

# Usage

Include namespace at the top of your script:
```C#
using GD.MinMaxSlider;
```

Code for the demonstration above:
```C#
[MinMaxSlider(0,10)] 
public Vector2 floatTest = new Vector2(2f, 8f);

[MinMaxSlider(0,10)]
public Vector2Int intTest;
```

Very simple and very handy!
