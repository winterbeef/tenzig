

```dataview
TABLE WITHOUT ID link(file.name) as "PC", 
Player, 
class,
AC,
hp,
excerpt as "Description"
WHERE contains(file.tags, "#game/pc")
AND sector="Tenzig"
SORT file.name
```
