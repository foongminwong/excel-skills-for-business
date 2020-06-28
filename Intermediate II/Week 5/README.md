# Week 5
## Data Models

**Modelling Functions: SUMPRODUCT**
* Example: Software Manuals - model the project cost and revenue in Excel
* `SUMPRODUCT`
* Calculate `Weighted Average` - `=SUMPRODUCT(B6:D6,$B$4:$D$4)/SUM($B$4:$D$4)`

![](screenshot/weighted-average.gif)

* Check each value if they're greater than or equal to 100
* Do logical test inside SUMPRODUCT
* `=SUMPRODUCT(1*(E6:E11>=100))`

![](screenshot/sum-product-logical-test.gif)