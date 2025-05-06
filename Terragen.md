
**[🡄 back](https://github.com/Brennian/Arceon-1.14/wiki)**

**Permission:** `arceon.tool.terragen`

**`//terragen [noiseType] [pattern] [height] [zoom] [wave]`**

Uses cuboid, sphere, cylinder and poly selections.

Use any slab or snow patterns for the system to use slabs or snow layers for more detailing.

**`//tgseed [seed]`**

Allows you to set the seed of the next Terragen, make sure to use the **-s flag** or it won't work.

***

**Noise types:**
> **Simplex**, **Fractal**, **Billowy**, **Ridged**, **Turbulence**, **Electric**, **Euclidean**, **Natural** and **Poly**

**Zoom =** Scaling of the terrain, higher is more stretched out.

**Wave =** Adds a wavy effect to the terrain, default = 0. 

***

**Flags:**

* **-s flag** keep the seed the same as before.

* **-v flag** adds a vignette mask over the terragen which smooths out the edges.

* **-e flag** layers it on top of existing terrain. 
   
> **Euclidean**, **Manhattan** and **Natural**
    
* **-r flag** randomizes the cellular noises. 
 
> **Fractal**, **Billowy**, **Ridged**, **Turbulence** and **Electric**
    
* **-n flag** adds more noise.

***

## **Examples:**

> **//terragen simplex**

![](https://i.imgur.com/fxYgvCN.png)

> **//terragen fractal 60 5 -v**

![](https://i.imgur.com/8AefKrZ.png)

> **//terragen euclidean 100**

![](https://i.imgur.com/SLjAjnD.png)

> **//terragen poly -v**  (Sphere selection)

![](https://i.imgur.com/QknsCiS.png)
