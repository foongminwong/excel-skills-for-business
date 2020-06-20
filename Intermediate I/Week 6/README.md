# Week 6
## Pivot Tables, Pivot Charts, and Slicers

**Recap**
* Produce quick summaries and autoamtion in our workflows

**Intro**
* Pivot Tables - create dynamic reports and charts can be customized on the run
* Summarize and filter large amounts of info to produce useful reports

**Creating and Modifying a Pivot Table**
* `Table Design` -> Change Table Name to `Sales`
* The data does not need to be in a table, but it can help when you update the data.
* Create Pivot Tables

![](screenshot/create-pivot-tables.gif)

* Total Sales by Customer Type

![](screenshot/pivot-sales--by-customer-type.gif)

* If we add some more data that ahd different customer types, just hit `Refresh button`
* easily get pivoted or changed to get different views on the data

* Insert Another New Pivot Table - Sales by Account Manager

![](screenshot/pivot-sales--by-account-manager.gif)

* A field that contains text data, automatically adds that to the `Rows` area, each of those becomes row label
* A field that contains numeric data, automatically adds to `Values` area and summed

* Total by State - Column Label
* Total by Year

![](screenshot/pivot-total-sales-by-state-year.gif)

**Value Field Settings**
* Summarize Values By

![](screenshot/summarize-by-values.gif)

* Show Values As (e.g.: percentage as grand total/ column total, original - No calculation)
* Number Format

![](screenshot/show-values-as.gif)

* Sales by State with subtotals

![](screenshot/sales-by-state-with-subtotals.gif)

**Sorting and Filtering a Pivot Table**
* Quarterly Sales Trends by region for 2015 and 2016
* Ungroup and then group by quarter and year based on `Order Date`

![](screenshot/quarterly-sales-trend-group.gif)

* Expand/ Collapse Field

![](screenshot/expand-collapse-field.gif)

* Pivot automatically sort data by Row & Column

* Filter data both by Row and Column Label
* Quarterly Sales Trends for 2015, 2016 only VIC, WA

![](screeshot/quarterly-sales-2015-2016.gif)

**Reporting Filter Pages**
* Filter data by `Account Manager`
* Filter the entire pivot to only show a specific account manager
* Show 3 total values if you filtered with 3 account managers
* `Show report Filter Pages`

![](screenshot/report-filter-by-account-manager.gif)

* Rename Pivot Table to `Regional Pivot`

* Take a deeper look at sales figures , you can just `double-click` the special/low value, Excel will show the snapshot of all values that we used to create that value
* `Field List` - On/Off Pivot Tables

![](screenshot/field-list.gif)

**Pivoting Charts**
* Pivot Chart by Customer Type (Pie Chart)

![](screenshot/pivot-pie-chart.gif)

* Pivot Chart + Interactive Dashboard

![](screenshot/pivot-bar-chart-interactive-dashboard.gif)

**Pivoting Slicers**
* Slicer - another tool to filter data, easy to use
* `Analyze` -> `Insert Slicer`
* Add Slicers - State, Customer Type, Account Manager
* Hold down `CTRL` key and multi-select

![](screenshot/slicers-state-custype-accmanager.gif)

* Connect slicers to multiple pivots
* Slicer Options
* Make both charts showing data when slicer is clicked

* Interactive visual reports & dashboards
* `Report Connections` under Slicer

![](screenshot/slicer-report-connect.gif)