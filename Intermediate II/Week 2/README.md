# Week 2
## Conditional Logic (Logical functions)

**Logical Functions I: IF**
* Example: Parent Invoices
* Have siblings `=IF(E4>=2,"Y","")`

![](screenshot/have-siblings.gif)

* Have sibling discount, `=IF(F4="y",D4*5%,0)`
* equals is not case sensitive

![](screenshot/siblings-discount.gif)

**Logical Functions II: AND, OR**
* Arrears Penalty `=AND(B4>0,C4="Y")`

![](screenshot/arrears-penalty.gif)

* Helper or Employee Discount `=OR(I4>=16,J4)`

![](screenshot/helper-employee-discount.gif)

* TRUE if cells X1, Y1, Z1 are in ascending order `=AND(X1<Y1,Y1,Z1`

* TRUE if at least 2 cells with same value `=OR(X1=Y1,X1=Z1,Y1=Z1)`
