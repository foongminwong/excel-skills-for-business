# Week 1
## Spreadsheet Design and Structure

**Spreadsheet Design Principles**
* Rename sheet name
* select one column -> move and shift right & move
* `Format Cells` -> `Alignment` -> `Center Across Selection` (it seems like merged but still maintain each individual cell)
* `Ctrl + T` -> Tick `My table has headers`
* Name your table: `tbl_sales` - distinguish from named ranges
* Create a new sheet `Lookup`
* 1-to-1 correspondence between lookup value & return value
* `remove duplicates`
* named ranges give us responsiveness we are looking for
* `Formulas` -> `Create from Selection` -> `Top row` ==> you got `Region` & `Surburb` named ranges
* Then create `tbl_surburbs`
* Create a new sheet `Report`

**Calculations**
* `Region` column ==> `=INDEX(Region, MATCH([@Suburb],Suburb,0))`
* `VLOOKUP` - if columns move around, it's going to break
* better option here `INDEX` and `MATCH`
* volatile function - `NOW`, `TODAY`, `OFFSET`, `INDIRECT`
* `=MONTH([@Date])`, `=YEAR([@Date])`

* Create a new `Calc` tab
* Last Sale Date `=MAX(tbl_Sales[Date])`
* EO = Equals `=EOMONTH(2017-9-20,-12)+1`, go back 12 months, go to 1st date of the following month
* `=EDATE(A7,1)` add one month and then format to `Short Date`
* `=AVERAGEIFS()`

**Formatting**
* Pivot tables - quickly generating data summaries
* Large data sets - pivot ables will elad to performance issues
* Save style -> `New Cell Styles`
* Date Formatting - mmmm yy
* Slicers - interactive

**Documentation**
* Name manager
* Data -> Data Validation
* `Insert Comment`

**Interface and Navigation**
* `CTRL + Drag` - duplicate
* Add navigation - insert link
* dynamic named range
* `nav_end` = `=INDEX(Data!A:A, ROWS(tbl_Sales)+4)`

**Assessment**
* build a simple financial model