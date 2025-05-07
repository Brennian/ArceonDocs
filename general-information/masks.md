# Masks

## **Overview**

> [#angle-mask](masks.md#angle-mask "mention")

> [#proximity-mask](masks.md#proximity-mask "mention")

> [#proximity3d-mask](masks.md#proximity3d-mask "mention")

> [#above-mask](masks.md#above-mask "mention")

> [#below-mask](masks.md#below-mask "mention")

> [#y-mask](masks.md#y-mask "mention")

> [#type-mask](masks.md#type-mask "mention")

> [#ambient-mask](masks.md#ambient-mask "mention")

> [#ygradient-mask](masks.md#ygradient-mask "mention")

> [#color-mask](masks.md#color-mask "mention")

#### Noise masks

> [#noise-mask](masks.md#noise-mask "mention")

> [#turbulence-mask](masks.md#turbulence-mask "mention")

> [#electric-mask](masks.md#electric-mask "mention")

> [#crack-mask](masks.md#crack-mask "mention")

> [#cell-mask](masks.md#cell-mask "mention")

> [#voronoi-mask](masks.md#voronoi-mask "mention")

> [#fractal-mask](masks.md#fractal-mask "mention")

***

### **Color Mask**

**`#cc [color]`**

**Example:** `//replace #color[lime] #color[red]`

***

### **Angle Mask**

**`#arcangle [minAngle] [maxAngle] [range]`**

**Example:** `//replace #arcangle[0][30][2] grass`

Use surface normal angle as the mask.

**minAngle / maxAngle:** 0 to 90 degrees (0 is fully horizontal)

**range:** distance that gets detected to get a smoother coverage (max = 2)

![](https://i.imgur.com/PAzAQzS.png)

***

### **Proximity Mask**

**`#prox [mask] [distance]`**

replace blocks within distance to the mask on the Y-axis.

**Example:** `//replace #prox[wool][5] stone`

***

### **Proximity3D Mask**

**`#prox3D [mask] [distance]`**

replace blocks within distance to the mask.

**Example:** `//replace #prox3D[wool][5] stone`

***

### **Above Mask**

**`#above [mask] [distance]`**

**Example:** `//replace #above[wool][15] stone`

![](https://i.imgur.com/6JHdmMA.png)

***

### **Below Mask**

**`#below [mask] [distance]`**

**Example:** `//replace #below[wool][5] stone`

![](https://i.imgur.com/8UYIGk7.png)

### **Y Mask**

**`y [min] [max]`**

**Example:** `//replace y[45][50] air`

![](https://i.imgur.com/gN84O9K.png)

***

### **Type Mask**

**`#type [block type]`**

**Example:** `#type[oak]` or `#tr[oak]`

![](https://i.imgur.com/kOmrxYe.png)

***

### **Ambient Mask**

**`#ambient [min=2]`**

**Example:** `#ambient`

![](https://i.imgur.com/gIufbF4.png)

***

### **YGradient Mask**

**`#ygradient <min> <max>`**

**Example:** `#ygradient[10][20]`

Min and max values are the Y coordinate.

![](https://i.imgur.com/g8HGi9O.png)

***

### **Turbulence Mask**

**`#turbulence [zoom=1] [coverage=50%]`**

**Example:** `#turbulence[2]` or `#turb[2]`

![](https://i.imgur.com/xsmFCgq.png)

***

### **Noise Mask**

**`#noise [seed] [noiseType] [coverage] [...]`**

**Example:** `#noise[12345][cubic][145][8]`

![](https://i.imgur.com/HavczIK.png)

**Example:** `#noise[12345][perlinfractal][120][fbm][hermite][1][0.03]`

![](https://i.imgur.com/xdFwCTH.png)

**Example:** `#noise[69420][cellular][60][cellvalue][Natural][3][0.06][100]`

![](https://i.imgur.com/07vUmEP.png)

***

### **Electric Mask**

**`#electric [zoom=1] [coverage=50%]`**

**Example:** `#electric[2]` or `#elec[2]`

![](https://i.imgur.com/H6YyWCd.png)

***

### **Crack Mask**

**`#crack [zoom=1] [coverage=50%] [jitter=70%]`**

**Example:** `#crack[2]`

![](https://i.imgur.com/tMo1n2B.png)

***

### **Cell Mask**

**`#cell [zoom=1] [coverage=50%] [jitter=70%]`**

**Example:** `#cell[2]`

![](https://i.imgur.com/zKLtSs8.png)

***

### **Voronoi Mask**

**`#voronoi [zoom=1] [jitter=50%]`**

**Example:** `#voronoi[2]` or `#vor[2]`

![](https://i.imgur.com/uVmethL.png)

***

### **Fractal Mask**

**`#fractal [zoom=1] [coverage=50%]`**

**Example:** `#fractal[2][40]` or `#frac[2][40]`

![](https://i.imgur.com/VXPGhnN.png)
