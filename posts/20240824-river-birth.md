---
layout: post
title: 过河 (River crossing)、猜生日（Birthday problem）
date: 2024-08-24
tags: quant
---

[[BACK to BLOG]](../another-page.html) [[BACK to HOME]](../)

### River crossing

黑夜，ABCD四个人要过桥，桥同时只能上2人，手电只有一个，没有手电不能动，因此为了打手电走得快的和走得慢的要同速。单程过桥，A需10分钟，B需5分钟，C需2分钟，D需1分钟。最快多长时间过桥？

思路是：
1. 需要尽可能减少损耗：组队过桥时，AB损耗5分钟，AC损8min，AD损9min；BC损3min，BD损4min，CD损1min。
2. 在不需要手电的情况，不需要有人回来送手电。
3. 对岸要派最快的人送手电回来：因为对岸的人需要折返才能再回对岸。

根据1和2，不需要手电时，损耗最小的选择是：AB+CD=损耗6min（其余可能AC+BD=12，AD+BC=12，均大于6min）。因为要让四个人都过桥至少要去两趟，因此黑夜时至少有一个人从对岸回来送手电。因为多回来一个人，所以多了一趟，因此又需要多送一次手电。送两次手电需要两个不同的人从对岸回来。根据3，这两个人需要是最快的CD，因此CD要先去对岸，两个人分别用2min和1min送手电，再用2min结伴回对岸。总共花掉17分钟。

### Birthday problem


[[BACK to BLOG]](../another-page.html) [[BACK to HOME]](../)