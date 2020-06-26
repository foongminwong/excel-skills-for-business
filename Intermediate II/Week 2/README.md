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

**Combining Logical Functions I: IF, AND, OR**
* Calculate 10% Arrears Penalty `=IF(AND(B4>0,C4<>"Y"),B4*10%,0)`

![](screenshot/calculate-arrears-penalty.gif)

* Calculate Helper or Employee Discount `=IF(OR(I4>=16,J4),250,0)`

![](screenshot/calculate-helper-employee-discount.gif)

**Combining Logical Functions II: Nested IFs**
* `CTRL + PLUS` - new column
* Previous Balance Category `=IF(B4=0,"A",(IF(B4>0,"B","C")))`

![](screenshot/previous-balance-category.gif)

* Calculate multi-ifs sibling discount `=IF(G4=1,0,(IF(F4=1,E4*5%,E4*8%)))`

![](screenshot/multi-sibling-discount.gif)

