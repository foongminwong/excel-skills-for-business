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

**Data Tables**
* See a range of different outcomes using different inputs using just 1 formula

![](screenshot/calculate-fixed-expenses.gif)

* `Data` -> `What if Analysis` -> `Data Table`
* One input data table
* `=TABLE(,E17)`

![](screenshot/one-input-data-table.gif)

* Two input data table
* array formulas

![](screenshot/two-input-data-table.gif)

**Goal Seek**
* Given a cell that has a calculation in it, it'll adjust that cell to a specified value by changing one of the inputs that you provide
* `What if Analysis` -> `Goal Seek`
* Project Costing Model

![](screenshot/goal-seek.gif)

**Scenario Manager**
* keep diferent data iputs in a single worksheet
* create selection
* `Data` -> `What-if Analysis` -> `Scenario Manager`

![](screenshot/scenario-manager.gif)

**Solver**
* Maximize, minimize values, set it to a specific value
* Add as scenario
* add constraints

![](screenshot/solver-set-to-specific-value.gif)

* Set to max
* Solver - allow us to model different situations with a variety of inputs and constraints & event integrate that with the Scenario Manager

![](screenshot/solver-max-scenario-summary.gif)

**Week 5 Final Assessment**
* Dataset: Landscape Data
