---
Visual Progress: □□□□□□□□□□ 0%
Author:
  - "[[Marie Brennan]]"
Books:
  - "[[Reading Tracker/Books/A Natural History of Dragons\\|A Natural History of Dragons]]"
  - "[[The Tropic of Serpents]]"
  - "[[Voyage of the Basilisk]]"
  - "[[In the Labyrinth of Drakes]]"
  - "[[Within the Sanctuary of Wings]]"
Short Stories:
  - "[[From the Editorial Page of the Falchester Weekly Review]]"
Planned Book Count: 5
Series Image:
  - "[[MemoirsofLadyTrent.jpg]]"
Track?: true
Read Count: "0"
Stories Count: "5"
Progress: 0%
Mainline Book Count: "5"
Mainline Read: "0"
Read Side-Stories: "0"
Side-Stories Count: "1"
Short Story Authors: "[[Marrie Brennan]]"
Novel Authors: "[[Marie Brennan]], [[Marrie Brennan]]"
---
```dataview
TABLE row["Series #"] as "#", read-status as "Status", latest-read as "Last Read"
FROM "Reading Tracker/Books"
WHERE contains(Series, this.file.link)
SORT row["Series #"] ASC
```
