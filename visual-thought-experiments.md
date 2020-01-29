

Visual Thought Experiments
==========================

Copyright (c) 2020 Martin Brösamle

based on a presentation/demo given at the [13th SIG Design Theory Paris Workshop](https://designtheory.sciencesconf.org/)

[clip_8](https://github.com/broesamle/clip_8)
can be described as an experimental *visual, shape-based programming language* whose main purpose is to rethink the principles of information technology.

`clip_8` combines established computational approaches with more visual, media-centred [designerly](https://doi.org/10.1016%2F0142-694X%2882%2990040-0) work practices.

The activity of designing `clip_8` can be characterised as a dialogue with a visible form aiming for a tangible materialisation of computation.

The cycle of inventions, revisions, and refinements made to the graphical notation system provides a link to an [earlier
research project](https://doi.org/10.1016/j.destud.2018.01.002). Based on video recordings of architectural design sessions we transcribed sketching activity in architectural design, relying on a graphical notation system.


Gestures and sketches in early design
-------------------------------------

From a cognitive scientist POV (without experience in a design-related field) one of the most striking observations about architectural design practice is the predominance of visual techniques and different (mostly graphical) media.

You can literally see the designer's thoughts on the sketchpad or
*in  dialogue  with  their  sketches*
(Goldschmidt, the designer as a team of one; cf. also Paul Laseau, Graphic thinking for architects and designers).


Invisibility
------------

Information processing technologies can be described as the exact opposite:
Everything that is too complex or boring for people disappears in the black box.
Invisibility is the essence of information technology.

Computers are symbol processing machines, formal decision automation devices.
They don't need to know what the symbols mean.
0, 1, Yes, No

```
>>> x = [x*2 for x in range(1000)]
>>> x[2]
4
>>> x[3]
6
>>> x[4]
8
>>> x[0]
0
>>> x[1]
2
>>> x
[0, 2, 4, 6, 8, 10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42, 44, 46, 48, 50, 52, 54, 56, 58, 60, 62, 64, 66, 68, 70, 72, 74, 76, 78, 80, 82, 84, 86, 88, 90, 92, 94, 96, 98, 100, 102, 104, 106, 108, 110, 112, 114, 116, 118, 120, 122, 124, 126, 128, 130, 132, 134, 136, 138, 140, 142, 144, 146, 148, 150, 152, 154, 156, 158, 160, 162, 164, 166, 168, 170, 172, 174, 176, 178, 180, 182, 184, 186, 188, 190, 192, 194, 196, 198, 200, 202, 204, 206, 208, 210, 212, 214, 216, 218, 220, 222, 224, 226, 228, 230, 232, 234, 236, 238, 240, 242, 244, 246, 248, 250, 252, 254, 256, 258, 260, 262, 264, 266, 268, 270, 272, 274, 276, 278, 280, 282, 284, 286, 288, 290, 292, 294, 296, 298, 300, 302, 304, 306, 308, 310, 312, 314, 316, 318, 320, 322, 324, 326, 328, 330, 332, 334, 336, 338, 340, 342, 344, 346, 348, 350, 352, 354, 356, 358, 360, 362, 364, 366, 368, 370, 372, 374, 376, 378, 380, 382, 384, 386, 388, 390, 392, 394, 396, 398, 400, 402, 404, 406, 408, 410, 412, 414, 416, 418, 420, 422, 424, 426, 428, 430, 432, 434, 436, 438, 440, 442, 444, 446, 448, 450, 452, 454, 456, 458, 460, 462, 464, 466, 468, 470, 472, 474, 476, 478, 480, 482, 484, 486, 488, 490, 492, 494, 496, 498, 500, 502, 504, 506, 508, 510, 512, 514, 516, 518, 520, 522, 524, 526, 528, 530, 532, 534, 536, 538, 540, 542, 544, 546, 548, 550, 552, 554, 556, 558, 560, 562, 564, 566, 568, 570, 572, 574, 576, 578, 580, 582, 584, 586, 588, 590, 592, 594, 596, 598, 600, 602, 604, 606, 608, 610, 612, 614, 616, 618, 620, 622, 624, 626, 628, 630, 632, 634, 636, 638, 640, 642, 644, 646, 648, 650, 652, 654, 656, 658, 660, 662, 664, 666, 668, 670, 672, 674, 676, 678, 680, 682, 684, 686, 688, 690, 692, 694, 696, 698, 700, 702, 704, 706, 708, 710, 712, 714, 716, 718, 720, 722, 724, 726, 728, 730, 732, 734, 736, 738, 740, 742, 744, 746, 748, 750, 752, 754, 756, 758, 760, 762, 764, 766, 768, 770, 772, 774, 776, 778, 780, 782, 784, 786, 788, 790, 792, 794, 796, 798, 800, 802, 804, 806, 808, 810, 812, 814, 816, 818, 820, 822, 824, 826, 828, 830, 832, 834, 836, 838, 840, 842, 844, 846, 848, 850, 852, 854, 856, 858, 860, 862, 864, 866, 868, 870, 872, 874, 876, 878, 880, 882, 884, 886, 888, 890, 892, 894, 896, 898, 900, 902, 904, 906, 908, 910, 912, 914, 916, 918, 920, 922, 924, 926, 928, 930, 932, 934, 936, 938, 940, 942, 944, 946, 948, 950, 952, 954, 956, 958, 960, 962, 964, 966, 968, 970, 972, 974, 976, 978, 980, 982, 984, 986, 988, 990, 992, 994, 996, 998, 1000, 1002, 1004, 1006, 1008, 1010, 1012, 1014, 1016, 1018, 1020, 1022, 1024, 1026, 1028, 1030, 1032, 1034, 1036, 1038, 1040, 1042, 1044, 1046, 1048, 1050, 1052, 1054, 1056, 1058, 1060, 1062, 1064, 1066, 1068, 1070, 1072, 1074, 1076, 1078, 1080, 1082, 1084, 1086, 1088, 1090, 1092, 1094, 1096, 1098, 1100, 1102, 1104, 1106, 1108, 1110, 1112, 1114, 1116, 1118, 1120, 1122, 1124, 1126, 1128, 1130, 1132, 1134, 1136, 1138, 1140, 1142, 1144, 1146, 1148, 1150, 1152, 1154, 1156, 1158, 1160, 1162, 1164, 1166, 1168, 1170, 1172, 1174, 1176, 1178, 1180, 1182, 1184, 1186, 1188, 1190, 1192, 1194, 1196, 1198, 1200, 1202, 1204, 1206, 1208, 1210, 1212, 1214, 1216, 1218, 1220, 1222, 1224, 1226, 1228, 1230, 1232, 1234, 1236, 1238, 1240, 1242, 1244, 1246, 1248, 1250, 1252, 1254, 1256, 1258, 1260, 1262, 1264, 1266, 1268, 1270, 1272, 1274, 1276, 1278, 1280, 1282, 1284, 1286, 1288, 1290, 1292, 1294, 1296, 1298, 1300, 1302, 1304, 1306, 1308, 1310, 1312, 1314, 1316, 1318, 1320, 1322, 1324, 1326, 1328, 1330, 1332, 1334, 1336, 1338, 1340, 1342, 1344, 1346, 1348, 1350, 1352, 1354, 1356, 1358, 1360, 1362, 1364, 1366, 1368, 1370, 1372, 1374, 1376, 1378, 1380, 1382, 1384, 1386, 1388, 1390, 1392, 1394, 1396, 1398, 1400, 1402, 1404, 1406, 1408, 1410, 1412, 1414, 1416, 1418, 1420, 1422, 1424, 1426, 1428, 1430, 1432, 1434, 1436, 1438, 1440, 1442, 1444, 1446, 1448, 1450, 1452, 1454, 1456, 1458, 1460, 1462, 1464, 1466, 1468, 1470, 1472, 1474, 1476, 1478, 1480, 1482, 1484, 1486, 1488, 1490, 1492, 1494, 1496, 1498, 1500, 1502, 1504, 1506, 1508, 1510, 1512, 1514, 1516, 1518, 1520, 1522, 1524, 1526, 1528, 1530, 1532, 1534, 1536, 1538, 1540, 1542, 1544, 1546, 1548, 1550, 1552, 1554, 1556, 1558, 1560, 1562, 1564, 1566, 1568, 1570, 1572, 1574, 1576, 1578, 1580, 1582, 1584, 1586, 1588, 1590, 1592, 1594, 1596, 1598, 1600, 1602, 1604, 1606, 1608, 1610, 1612, 1614, 1616, 1618, 1620, 1622, 1624, 1626, 1628, 1630, 1632, 1634, 1636, 1638, 1640, 1642, 1644, 1646, 1648, 1650, 1652, 1654, 1656, 1658, 1660, 1662, 1664, 1666, 1668, 1670, 1672, 1674, 1676, 1678, 1680, 1682, 1684, 1686, 1688, 1690, 1692, 1694, 1696, 1698, 1700, 1702, 1704, 1706, 1708, 1710, 1712, 1714, 1716, 1718, 1720, 1722, 1724, 1726, 1728, 1730, 1732, 1734, 1736, 1738, 1740, 1742, 1744, 1746, 1748, 1750, 1752, 1754, 1756, 1758, 1760, 1762, 1764, 1766, 1768, 1770, 1772, 1774, 1776, 1778, 1780, 1782, 1784, 1786, 1788, 1790, 1792, 1794, 1796, 1798, 1800, 1802, 1804, 1806, 1808, 1810, 1812, 1814, 1816, 1818, 1820, 1822, 1824, 1826, 1828, 1830, 1832, 1834, 1836, 1838, 1840, 1842, 1844, 1846, 1848, 1850, 1852, 1854, 1856, 1858, 1860, 1862, 1864, 1866, 1868, 1870, 1872, 1874, 1876, 1878, 1880, 1882, 1884, 1886, 1888, 1890, 1892, 1894, 1896, 1898, 1900, 1902, 1904, 1906, 1908, 1910, 1912, 1914, 1916, 1918, 1920, 1922, 1924, 1926, 1928, 1930, 1932, 1934, 1936, 1938, 1940, 1942, 1944, 1946, 1948, 1950, 1952, 1954, 1956, 1958, 1960, 1962, 1964, 1966, 1968, 1970, 1972, 1974, 1976, 1978, 1980, 1982, 1984, 1986, 1988, 1990, 1992, 1994, 1996, 1998]
```

The underlying logic:
```
X       -> Y
visible    invisible
```
Blackbox.

Every symbol can stand for any content.


about-ness
----------

The computational theory of the mind is implicitly underlying most cognitive approaches.
The human mind thinks *about* the world.
It is conceptualised as a separate entity outside the world:
A long way between thought and experience, data and display, interface and user, mind and world.

The mind works like a computer.

*****

What a contrast to the dense, fluent, and tangible experience of watching somebody who is engaged in conceptual sketching!

What a lack of material qualities!

Human cogntion in the design activity requires two kinds of understanding: theoretical and tangible.

Would it be possible to incorporate the perfectly opposed requirements into an existing (physical) thing/system and then work with the resulting paradox?

*****

What if there was no about-ness?

Would it be possible, not to formulate theories _about_ the visual/graphical nature of the design practice, but -- more fundamental --
to formulate the theories themselves _in_ a graphical way?

*****

Examples
--------

Both presented examples are centred around some visual notation system which gets developped step-by-step `on site`.


### Example 1: Graphical transcription of design activity

Objective: Develop a set of rules that would make it possible to  reproduce the architectural design process in the computer.

+ Video staccato

+
+ Repetetive revisions of the (graphical) notation scheme (in response how the researcher changes her/his view on the domain under investigation).

+ Embedding in an activity, namely observing and recording/drawing.


### Example 2: `clip_8`

Would it be possible to formulate theories _in_ a graphical way?

Would it be possible to do programming work by drawing the programs in a CAD software?


A fully visual, shape-based programming language:
    + subvert the blackbox principle
    + Every step of program execution can be watched.
    + What I see was what I compute.
    + Poetic and completely useless


Closing time
------------

Visual thought experiment.

Combine the incombinable.

Give computation a form:
    + De-abstract/rematerialise it.
    + Subvert arbitrarity by radical visualisation.
    + Everything can be seen, the data, the instructions.
    + No black box.
    + The process becomes terribly cumbersome
    + Which, in turn, is the foundation of its aesthetics

Video Staccato: Repetetive changes in temporal dynamics.
    + fluent, volatile process
    + static, eternal records

Experimental system:

```
        Something that creates more questions than it answers

                (Hans-Jörg Rheinberger,
                 who could be considered the German Bruno Latour,
                 at least for the German Social Studies of Science
                 community)
```

```
        Transforming mediation of the sketches, plans, renderings
                (Farias 2009)
```


Visual languages as rethinking devices.

Develop a visual languages as a conceptual projector: *Design of your future way of thinking!*
