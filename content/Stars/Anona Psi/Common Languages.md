

```dataview
TABLE WITHOUT ID 
file.link AS "Planet", language as Lang
FROM #game/planet and "Stars/Anona Psi"
FLATTEN language
WHERE length(language)
```

