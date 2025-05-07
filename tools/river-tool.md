# River-Tool

**Permission:** `arceon.tool.river`

**`//river <block> <start> <end> [decline]`**

Uses convex selection.

**Start and end =** Depth of the river.

**Decline =** Steepness of the edges of the river (default = 1).

**Flags:**

* **-s flag** smooths out the liquid or snow layers.
* **-n flag** adds noise to the river shape.

***

### **Examples:**

> **//river water 5 10**

![](https://i.imgur.com/q19wxdl.png)

> **//river water 5 10 -n**

![](https://i.imgur.com/aopcmrQ.png)

> **//river water 5 10 -s**

![](https://i.imgur.com/vrJ9ga0.png)

> **//river snow\_layer 10 20 -sn**

![](https://i.imgur.com/KOXjxsu.png)
