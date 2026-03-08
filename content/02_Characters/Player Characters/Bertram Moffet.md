---
type: character
role: PC
house: [[House Moffet]]
rank: Knight-Marshal
status: Alive
affiliation: Gorundia
tags: [character, pc]
---

# Bertram Moffet

![[90_Assets/portraits/Bertram Moffet.png|250]]

## Character Information

```dataview
table without id
  house as House,
  rank as Rank,
  affiliation as Affiliation,
  status as Status
from ""
where file.path = this.file.path
```

---

## Overview

Brief description of the character.

---

## Background

History and reputation.

---

## Relationships

- 

---

## Notable Events

- 

---

## Session Appearances

```dataview
list
from "01_Session_Logs"
where characters and contains(characters, this.file.link)
sort session asc
```

---

## Notes

Miscellaneous information.