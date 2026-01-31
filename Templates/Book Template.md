---
Title: "{{title}}"
Cover Image: "{{coverURL}}"
Author:
  - "[[{{author}}]]"
Page Count: "{{totalPage}}"
Publication Date: "{{publishDate}}"
Series:
  - "{{series}}"
"Series #":
Universe:
"Universe #":
Genre:
  - "{{categories}}"
Description: "{{description}}"
"---": ---
Read Status:
Rating:
Reads:
Ownership:
First Read:
Latest Read:
---
## Reviews

```dataview
TABLE Review, Rating, start-date AS "Start", end-date AS "End"
FROM "Reading Tracker/Reading Journal"
WHERE contains(Book, this.file.link)
SORT end-date ASC
```
