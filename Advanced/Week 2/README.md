# Week 2
## Advanced Formula Techniques

**Introduction**
* Structured references in tables, array formulas, perform complex calculations
* Excel can:
	* Streamline workflows
	* Perform multiple calculations	
	* Reduce file sizes
* Will learn:
	* Structured references
	* Sort data with functions
	* array formulas
	* array functions

**Discussion**
* structured references - dynamic, automatically pick up those new values
* named ranges - refer to them by name, pros: don't need to go & select data
* array formulas - CSE formulas `CTRL + SHIFT + ENTER`
	* perform calc on multiple values in an array

**Tables and Structured Referencing**
* E.g.: Workbook for an online retail company
* create summary data
* `=ROWS(Sales)`
* Structured References - a little named ranges
	* Total By Row - `=SUM(Sales[@[Australia]:[China]])` - @ = by row
	* Total Sales - `=SUM(Sales[[Australia]:[China]])`
	* Headers
		* =Sales[[#Headers],[Australia]]
		* Last 5 Years - `=MAX(Sales[Year])-K8` the  fill handle
		* =SUMIFS(Sales[Australia],Year,$L8)
* Absolute Structured References
	* Best Quarters (1,2,3)
	* `=LARGE[Sales[Australia],TopQtr[@[Best Quarters]:[Best Quarters]]`
* Whne you add 1 new row, ALL calcs have updated to reflect the changes