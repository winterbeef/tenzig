

```dataview
TABLE WITHOUT ID link(file.name) as "Faction"
WHERE contains(file.tags, "#game/faction")
AND sector="Tenzig"
SORT file.name
```
