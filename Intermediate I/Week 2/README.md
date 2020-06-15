# Week 2
## Text & Date functions

**Combining Text (CONCAT, &)**
* Concatenate, linking together
* `=CONCAT()`
* Concat names

![](screenshot/concat-names.gif)

* Ampersand sign, concat emails

![](screenshot/concat-emails.gif)

**Changing Text Case (UPPER, LOWER, PROPER)**
* `=PROPER(CONCAT(C4," ",B4))`

![](proper-function.gif)

* `=LOWER(C4&"."&B4&"@pushpin.com")`

![](lower-function.gif)

**Extracting Text (LEFT, MID, RIGHT)**
* `=LEFT(K4,2)`

![](left-function.gif)

* `=RIGHT(K4,4)`

![](right-function.gif)

* `=MID(K4,4,4)` - Managed to get `WEST`, `NORT` but not `NORTH`

![](middle-function.gif)

**Finding Text (FIND)**
* `=MID(K4,4,FIND(" ",K4)-4)`

![](find-function.gif)