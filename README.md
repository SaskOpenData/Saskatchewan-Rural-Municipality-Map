# Saskatchewan-Rural-Municipality-Map

![township.jpg](images/township.jpg)


## Why this map exists:

### Statistics Canada CSD data quality

Stats Canada CSD files are OK, but they follow roads, instead of the actual Dominion Land Survey grid. The centre lines can cut corners and be a bit off in places. The image below shows a typical mis-representation of the CSD where the official version boundaries are in grey and this version is highlighted in black.

![roadline.png](images/roadline.png)

The same is also true for water features. The image below highlights the Outlook, SK Census Subdivision boundary along a waterway. Again, the official version is shown in grey and this version is in black.

![waterway.jpg](images/waterway.jpg)

## Sources

The map was created and updated based on the following sources:

- [Elections Saskatchewan polling places (2012)](https://www.elections.sk.ca/candidates-political-parties/maps/)
- [Township grid](https://hub.arcgis.com/datasets/e7e309c9bae94618807e7733133053d5_8)
- National Topographic Series CanVec water features (50K resolution)

These data sources were combined in QGIS, referencing the Sask government's read-only web layer, as well as CSDs from Statistics Canada and some historic maps (in order to figure out the "imaginary" boundaries that pass through reserves and towns).

## Credits

Alex McPhee - [Web](https://t.co/LYlRw2Kudr?amp=1) / [Twitter](https://twitter.com/ksituan)
