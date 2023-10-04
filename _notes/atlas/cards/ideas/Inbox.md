This isn't a normal inbox. It's a cooling pad 🧊.

[[A writing inbox for transient and incomplete notes]]

Thoughts come in hot 🌶. But after a few days, they cool down ❄️.

When cooler thoughts prevail, you can better prioritize. Cool? 

``` dataview
TABLE WITHOUT ID
 file.link as "Encounters and new notes",
 (date(today) - file.cday).day as "Days alive"

FROM "encounters" 

SORT file.cday asc

LIMIT 20
```
