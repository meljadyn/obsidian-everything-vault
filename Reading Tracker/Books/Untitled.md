---
Author:
  - 
  - "[[{{author}}]]"
Series:
  - 
  - "{{series}}"
"Series #":
Rating:
Genre:
  - 
  - "{{categories}}"
Read Status:
  - 
  - Unread
Ownership:
  - 
  - Unowned
Page Count: "{{totalPage}}"
Publication Date: "{{publishDate}}"
Universe:
"Universe #":
Reads:
Title: "{{title}}"
Cover Image: "{{coverURL}}"
Description: "{{description}}"
"---": ---
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
