---
sector: Tenzig
---
[[Gm Notes]]
# Sessions

```dataview
TABLE WITHOUT ID link(file.name) as "Session"
WHERE contains(file.path, this.file.folder) AND file.name != this.file.name AND contains(file.tags, "#game/session")
AND sector="Tenzig"
SORT file.name
```
^sessions