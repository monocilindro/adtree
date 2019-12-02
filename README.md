# AdTree
Accurate, Detailed, and Automatic Modelling of Laser-Scanned Trees

![](AdTree.jpg)
<p align="center">3D Trees reconstructed from point clouds</p>

AdTree implements the tree reconstruction method described in the following paper:
```
Shenglan Du, Roderik Lindenbergh, Hugo Ledoux, Jantien Stoter, and Liangliang Nan.
AdTree: Accurate, Detailed, and Automatic Modelling of Laser-Scanned Trees.
Remote Sensing. 2019, 11(18), 2074.
```
Please consider citing our paper if you use the code/program (or part of it).

# Planed: textured rendering (both leaves and branches)

---

### Build AdTree
You can also build AdTree from the source code. Use CMake to generate project files for your favorite IDEs.
  
---

### Run AdTree
This demo version provides a super user interface. Just click on the menus will do the magic :-)

---

### Data
Some test tree point clouds are provided in the 'data' folder.
**Note:** When testing on your own point clouds, please make sure that:
 - you point cloud represents a single tree (i.e., the tree is segmented from the background);
 - the tree has an upright orientation (i.e., Z-axis point up).

---

### License
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License or (at your option) any later version. The full text of the license can be found in the accompanying LICENSE file.

---

Should you have any questions, comments, or suggestions, please contact us at: liangliang.nan@gmail.com

3D Geoinformation, TU Delft,
https://3d.bk.tudelft.nl
Dec. 1, 2019