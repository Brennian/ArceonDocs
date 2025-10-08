# Brushes

## **Overview**

**Permission:** `arceon.brushes` `arceon.brush.*`

**Aliases:** `/arcbrush /ab //ab`

> [#erode-blend-brush](brushes.md#erode-blend-brush "mention")

> [#cube-brush](brushes.md#cube-brush "mention")

> [#spike-brush](brushes.md#spike-brush "mention")

> [#vine-brush](brushes.md#vine-brush "mention")

> [#crop-brush](brushes.md#crop-brush "mention")

> [#revolve-brush](brushes.md#revolve-brush "mention")

> [#boulder-brush](brushes.md#boulder-brush "mention")

***

### **Erode Blend Brush**

**Permission:** `arceon.brush.erodeblend`

**`/arcbrush erodeblend <size> [type]`**

Erodes, then blend balls terrain.

**Types:** Fill, Smooth, Lift, Melt and Clear.

![](https://i.imgur.com/WDsoRdv.png)

***

### **Cube Brush**

**Permission:** `arceon.brush.cube`

**`/arcbrush cube <block> [size] [snapeAngle] [height] [width]`**

Creates cuboid shapes,\
you can use \[min],\[max] for each size parameter.

snapeAngle = angle intervals the cubes snap on (has to be a divisor of 360)

**Flags:**

**-h flag** makes it hollow

**-c flag** makes the height centered

**-a flag** makes it angled based on your orientation

![](https://i.imgur.com/m0UJ7vg.png)

***

### **Spike Brush**

**Permission:** `arceon.brush.spike`

**`/arcbrush spike <block> <length> <start> <end>`**

Uses convex selection.

**Start and end =** sphere size of start and end.

**Length =** Length of the spike.

**Flags:**

**-n flag** adds noise to the spike shape.

![](https://i.imgur.com/pqDwXI8.png)

***

### **Vine Brush**

**Permission:** `arceon.brush.vine`

**`/arcbrush vine <block> [size] [chance] [min][,[max]]`**

**Chance =** place chance in percentage.

**Min and Max =** vine length.

![](https://i.imgur.com/xauPaMp.png)

***

### **Crop Brush**

**Permission:** `arceon.brush.crop`

**`/arcbrush crop <size> <min> [max]`**

Min and max data values between 0 and 8.

![](https://i.imgur.com/H6KioDR.png)

***

### **Revolve Brush**

**Permission:** `arceon.brush.revolve`

**`/arcbrush revolve <amount> [start] [end] [heightDiff]`**

> Uses cuboid selection.

**Start and end =** angle of start and end in degrees.

**HeightDiff =** Height difference between start and end.

**Flags:**

**-p flag** makes the rotations regular polygon shapes

**-r flag** makes the rotation reversed

![](https://i.imgur.com/RTONfY0.png)

***

### **Boulder Brush**

**Permission:** `arceon.brush.boulder`

**`/arcbrush boulder <block> [size] [amount] [height] [width]`**

you can use \[min],\[max] for each size parameter.

**Amount =** smoothness from 0 to 5 (0 is low poly)

**Flags:**

**-h flag** makes the rocks hollow

**-f flag** makes the rocks "fall" to the ground

**-a flag** makes the rocks angled based on your orientation

![](https://i.imgur.com/zlV9EY4.png)
