---
Author:
  - 
  - "[[{{author}}]]"
Series:
  - 
  - "{{series}}"
Reads:
"Series #":
Rating:
Genre:
  - 
  - "{{categories}}"
Ownership:
  - 
  - Unowned
Page Count: "{{totalPage}}"
Publication Date: "{{publishDate}}"
Universe:
"Universe #":
Title: "{{title}}"
Cover Image: "{{coverURL}}"
Description: "{{description}}"
"---": ---
Read Status:
  - Unread
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
