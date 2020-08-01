# Week 3
## Data Cleaning and Preparation

**Intro**
* Clean messy data sets
* automate processes
* clean data dynamically
* replace blanks, fix dates, remove spaces & characters

**Replace blanks with repeating values**
* `Go to Special` -> Select `Blank` -> Paste the copied `=A3`
* `=IF(ISBLANK(Sheet!A2),A1,Sheet!A2)`

**Fix Dates (DATE, MONTH, YEAR, DAY, TEXT)**
* `=TODAY()`
* dd = 17, ddd = Tue, dddd = Tuesday
* Join Month - `=TEXT(J1, "mmmm")`
* Join Date
	* chop off text into day, month,year, reformat it as a recognized Excel date 
	* `=DATE(LEFT(Sheet!F2,4),MID(Sheet!F2,6,2),RIGHT(Sheet!F2,2))`
* 2015.04.05

**Remove Unwanted Spaces (TRIM, CLEAN)**
* Remove leading, trailing, extra spaces `=TRIM(Data!B3)`
* `PivotTable Tools` -> `Analyze` -> `Refresh`
* Removes many, but not all, of the non-printing characters
	* =TRIM(CLEAN(Data!B3))`
	
**Diagnostic Tools (ISNUMBER, LEN, CODE)**
* Convert text numbers back to numerics, and remove any additional hidden spaces
* CODE function - convert to its decimal code `=CODE(RIGHT(I2,1))`
* Get rid of OF 160