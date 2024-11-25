# Mason Jar Coupler  ALPHA 0.0.1
---

> [!NOTE]
> Currently under ALPHA Development and this is just committed recently to inform our members in "Plants In Jars" on discord.




- Designed in FreeCad 1.0.0
- Python 3.11
---











> Main goals for this project are as follows
- [x] Parametric Input via SpreadSheet
- [x] Breakpoint and debugging options.
- [ ] Various thread sizes for different types of standard Pyrex Jars / Mason etc.
- [ ] Output a STL File for 3D Printing / Upload to PCBWay / JLCPCB etc.. Without Errors 



More information to follow further down the line.




Contributors:
---
<<<<<<< Updated upstream
- Patrick Woodlock
- Webklex
=======
<<<<<<< HEAD

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





=======
- Patrick Woodlock
- Webklex
>>>>>>> 2e0327d11e9fc3d9f75e732b2a729571eb06fee8
>>>>>>> Stashed changes



