# Week 3
## Automatic Lookups

**Introduction to Lookups: CHOOSE**
* `CHOOSE` - retrieve a value from a list based on a given numeric value
* do  alookup from a very finite list
* `=CHOOSE([@[Loc Code]],$K$6,$K$7,$K$8,$K$9,$K$10)`

![](screenshot/choose-lookup.gif)

* `CHOOSE` 1st argument -> index number
* The values in the CHOOSE function need to be listed individually, separated by a comma. This can take a long time to set up when you have lots of values.

**Approximate Matches: Range VLOOKUP**
* press `F4` to make them absolute
* `=VLOOKUP(D4,$G$4:$H$7,2)`
* The lookup data set that the table_array points to should be listed from smallest to largest, the range should be referred to with absolute references, and headings should not be included.


![](screenshot/range-vlookup.gif)