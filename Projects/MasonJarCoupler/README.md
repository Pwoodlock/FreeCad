# Mason Jar Coupler  ALPHA 0.0.1

- Designed in[ FreeCad 1.0.0](https://www.freecad.org/)
- Python 3.11 included with [AppImage](https://www.freecad.org/downloads.php)




Contributors:
---
- Patrick Woodlock
- Weblix
---

> [!NOTE]
> Currently under ALPHA Development and this is just committed recently to inform  members in "Plants In Jars" on discord.





> Main goals for this project are as follows
- [x] Parametric Input via SpreadSheet
- [x] Breakpoint and debugging options.
- [ ] Flat surface to both be used with a Rotating Jar Tilting Machine & to house the synthetic filter that's also parametric to suit peoples needs.
- [ ] Mason Wide Mouth Threads
- [ ] Mason Standard Mouth Threads
- [ ] Various Other Standard Autoclave Resistant Jars Threads
- [ ] Documentation for Editing & Exporting the files for printing
- [ ] Group Production for 3D Printing for EU Based Members or US etc. 
	- [ ] [PCBWay](https://www.pcbway.com/rapid-prototyping/manufacture/?type=2&reffercode=TOP0)
	- [ ] [JLC3DP](https://jlc3dp.com/3d-printing-quote)














---

> [!NOTE]
> 
> Using the following Code in the FreeCad Macro Editor or via the spreadsheet function for parametric editing.





```python
doc = App.newDocument('MJC')

# Create spreadsheet

sheet = doc.addObject('Spreadsheet::Sheet', 'Parameters')

# Set up parameters

sheet.set('A1', 'Diameter')

sheet.set('B1', '80')

sheet.set('C1', 'Outer diameter of the coupler')

sheet.set('A2', 'Height')

sheet.set('B2', '50')

sheet.set('C2', 'Total height of the coupler')

sheet.set('A3', 'WallThickness')

sheet.set('B3', '10')

sheet.set('C3', 'Thickness of the walls')

sheet.set('A4', 'FluteCount')

sheet.set('B4', '18')

sheet.set('C4', 'Number of flutes around the circumference')

sheet.set('A5', 'FluteDepth')

sheet.set('B5', '3')

sheet.set('C5', 'Maximum depth of flute cuts')

sheet.set('A6', 'FluteWidth')

sheet.set('B6', '16')

sheet.set('C6', 'Width of each flute')

# Set aliases for parameters

sheet.setAlias('B1', 'Diameter')

sheet.setAlias('B2', 'Height')

sheet.setAlias('B3', 'WallThickness')

sheet.setAlias('B4', 'FluteCount')

sheet.setAlias('B5', 'FluteDepth')

sheet.setAlias('B6', 'FluteWidth')

doc.recompute()
```





---





> [!NOTE]
> SpreadSheet Example


---

![[Screenshot_20241125_182536.png]]








