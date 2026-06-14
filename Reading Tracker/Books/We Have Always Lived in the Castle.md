---
Author:
Series:
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
Cover Image: https://m.media-amazon.com/images/I/A1YlGmse1mL._AC_UF1000,1000_QL80_.jpg
Description: "{{description}}"
"---": ---
Read Status:
  - Completed
Reads:
  - "[[Reading Tracker/Reading Log/We Have Always Lived in the Castle]]"
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
