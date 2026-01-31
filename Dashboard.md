

```chartsview
# chart type 
type: Column

# chart data
data: |
  dataviewjs:
  return dv.pages('"Reading Tracker/Books"')
           .groupBy(p => p["Read Status"])
           .map(p => ({folder: p.key, count: p.rows.length}))
           .array();

# chart options
options:
  xField: "folder"
  yField: "count"
  padding: auto
  label:
    position: "middle"
    style:
      opacity: 0.6
      fontSize: 12
  columnStyle:
    fillOpacity: 0.5
    lineWidth: 1
    strokeOpacity: 0.7
    shadowColor: "grey"
    shadowBlur: 10
    shadowOffsetX: 5
    shadowOffsetY: 5
  xAxis:
    label:
      autoHide: false
      autoRotate: true
  meta:
    count:
      alias: "Count"
```

Latest Reads:
![[Books.base#Recent Reads]]