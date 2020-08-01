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
* When you add 1 new row, ALL calcs have updated to reflect the changes

**Using Functions to Sort Data**
* sorted everytime when they come & refresh data
* `Data` -> `Get Data` -> `Legacy Wizards` -> `From Web`
* Hit `No`
* `COUNTIFS(rateCodes,"<="&)` - codes get ranking
* `&` to join that to my cell reference
* `=MATCH(ROW()-4,N5:N14,0)` - say that value 1 is in 4th position
* Right order currency conversion table - `=INDEX(rateCodes,MATCH(ROW()-4,N5:N14,0))`

**Introduction to Array Formulas**
* E.g.: Product List Sheet
* Array functions <-> CSE formulas - `CTRL + SHIFT + Enter`
* `=C4:C36*H4` - `C4:C36 USD PRICE`, `H4 AUD RATE`
* `=SUM(H7:H9*I7:I9)` - `H7:H9 QUANTITY`, `I7:I9 AUD PRICE`, then `CTRL + SHIFT+ENTER`
* mult-cell array formula
	* `=LARGE(D4:D36,{1;2;3})` - `D4:D36 - ALL AUD PRICE`, k is the constant array 1,2,3 then `CTRL + SHIFT+ENTER`
	
	
