# Week 3
## Named Ranges

**Introducing Named Ranges**
* refer data by name rather than cell reference
* Excel automatically uses relative referencing
* So, use `F4` make sure the excel don't move the call, make the value absolute/fixed - absolute cell references
* Instead of using `Absolute Cell Reference`, we can use `Named Ranges`

![](screenshot/named-ranges.gif)

* A named range automatically gives us that absolute cell reference.
* EXP2017 which is just like E27, and is thus a cell reference which is not allowed to name a range.
* create a single cell using name box

**Creating Named Ranges*** 
* `CTRL + SHIFT + DOWN`
* Scope - define where this named range can be seen
* `Create from Selection` - name multiple ranges simultaneaously
* `Name Box`, `Define Names`, `Create from Selection`
* `Create from Selection`

![](screenshot/create-from-selection.gif)

**Managing Named Ranges**
* Edit, update, audit name ranges
* `Name Manager`

![](screenshot/name-manager.gif)

**Named Ranges in Formulas**
* Named Ranges for Caculation
* Dragging the whole column VS using named ranges when sum/average, etc.

![](screenshot/name-ranges-calculation-1.gif)

* `F3` to get the named ranges

![](screenshot/name-ranges-calculation-2.gif)

* Named ranges are usually a great idea, rather than using cell references when performing calculations because of the following reasons:
	* Named ranges are more meaningful to both yourself, as well as communicating the workings of your spreadsheet to others.
	* Formulas will be faster to create. Otherwise, you will be spending time selecting data, can be time-consuming for large spreadsheets

**Apply Names**
* Apply Names

![](screenshot/apply-names.gif)

* Paste List

![](screenshot/paste-list.gif)

* Why Paste List useful?
	* It can be used to show which ranges the named ranges apply to. This is useful if the worksheet is complex and there is a lot going on.
