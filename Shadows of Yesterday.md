---
type: adventure
tags:
  - pf2e
  - campaign
  - Shadows
  - of
  - Yesterday
ruleset: Pathfinder Second Edition
world:
---
# [[Temp Folder/Shadows of Yesterday/Shadows of Yesterday|Shadows of Yesterday]]


```ad-important
title: Forge of Tomorrow Hook
***What is this campaign about? What is the goal?***
Summary:: _It begins, as many incidents in the City of Towers do, with a corpse. A warforged assassin, a mysterious blank book, and an offer from a House Cannith heir leads into the depths of Sharn, leading eventually to an ancient ruin dating back to before the creation of the Kingdon of Galifar_

## Welcome to [[Eberron]]

## The Houses of Eberron


## Who Are You?
You may be a follower of the god Procan, neutral god of weather and the sea.

You may be a fisher, born to the sea and providing for the town of Saltmarsh.

You might have come to Khorvaire to seek a better life and make your fortune.

You might be a forgotten soldier trying tio find his way, pushing back the smugglers and slavers of [[Droaam]].

You may be a shipwright, building and repairing the vessels that kept the gold coming to Sharn.

You may be a smuggler, bringing in stolen elven wine under the darkness of a moonless
night or smuggling treasures out of themists of the Mournland.

You might be a veteran of the Crye army who fought in the north but no longer has a home to go to.

Above all, you are companions who, together, seek to stop the forces of darkness from winning. Whoever they may be.
```

```ad-faq
title: Six Truths of the World
***What makes this campaign unique?***
1.
2.
3.
4.
5.
6.
```

```ad-info
title: Campaign Arcs (Spelljammer):
***What are the major moving forces in this campaign?***
---
**Arc 1:**
**Goal:**
The Party is contacted by representatives of the Church of the Platinum Dragon, who have heard of their arrival and wish to offer their assistance. The Church tells the party that they (the Church) are in possession of an ancient artifact that is somehow linked to the Mourning, a cataclysmic event that destroyed the kingdom of Cyre in their own world. They believe that the artifact must be returned to Eberron for safekeeping, and ask the party to help them transport it.

**Three Grim Portents:**
- [ ] The party learns that Kethril, an astral elf despot, has learned of the artifact's existence and is determined to obtain it.
- [ ] The party confronts Kethril and his allies in a final battle, which takes place on Kethril's flagship in the midst of a fleet battle.
During the battle, it is revealed that Kethril's true plan is to use the artifact to power a powerful weapon that can destroy entire worlds, which he plans to use to conquer the universe.
- [ ] The party defeats Kethril and his allies, but the artifact is damaged in the battle and begins to malfunction.
---
**Arc 2:**
**Goal:**
Planebreaker
**Three Grim Portents:**
---
**Arc 3:**
**Goal:**
**Three Grim Portents:**
```

```ad-info
title: Campaign Arcs (Eberron):
***What are the major moving forces in this campaign?***
---
**Arc 1:**
**Goal:**

**Three Grim Portents:**

**Arc 2:**
**Goal:**
Planebreaker
**Three Grim Portents:**
---
**Arc 3:**
**Goal:**
**Three Grim Portents:**
```
````ad-tldr
title: Player Characters in Forge of Tomorrow
```dataview
TABLE
class AS "Character Class",
race AS "Character Race",
organization AS "Affiliation",
ddb_link AS "link:",
details[0].desc AS "AC",
player AS "Player"
FROM "Campaigns/Forge of Tomorrow/Players"
```
````


````ad-tldr
title: NPC's in Forge of Tomorrow
```dataview
TABLE WITHOUT ID
	link(file.path, name) AS "Name",
	race AS "Race",
	status AS "Status",
	relationship AS "Relationship"
FROM "World/Cast List"
WHERE contains(type, "npc")
SORT file.name asc
```
````

---
````ad-example
title: Mentions in Session Notes
```dataview
TABLE summary AS "Session Summary" FROM #session-notes AND [[Forge of Tomorrow]]
```
````