# Week 4
## Finance Functions and Working with Dates

**Intro**
* cost benefit analysis
* perform complex calculations, determine investments, model financial
* date functions, calc future & present val of investments, create loan schedules, cal the net presentval & internal rate of return, depreciation functions

**Discussion**
* Rate (RATE)
* Payment Period (NPER) - by month
* Present Value (PV)
* Future Value (FV)
* Net Present Value Func (NPV)
* Internal Rate of retunr (IRR)
* Financial based date functions
* End of Month function, EDATE()
* Straight Line Depreciation (SLN), Sum of Year Digits, Double Declining balance

**Working with Dates (EOMONTH, EDATE, WORKDAY.INTL)**
* E.g: Financial Reports
* Due Date - `=EOMONTH(C5,0)`, 0 = end of the month for the date we've selected, 1 - the end of the month for the previous month, 2 - end of month for this quarter (3 months time)
* workday and workday international function
	* `=WORKDAY.INTL(EOMONTH(C5,0),10,1,K5:K7)`, K5:K7 - holiday days
* Reminder Date - `=EDATE(C5,2)`

**Financial Functions (FV, PV, PMT)**
* Client investment queries
* FV (Future Value) - how much an investment will be worth in the future
* PV (Present Value) - amount you're going to invest or borrow at the current time
* RATE (Rate) - the rate you're going to earn per Payment Period (NPER)
* PMT (Payment Amount) - regular payment we'll be making monthly or annually
* Value of investment at the end of 25th year: `=FV(B3,B4,B5,B6,0)`, 0 - end of period
* Amount to be invested now -  `=PV(B3,B4,B5,B6)`
* Amount to be invested at the end of every year - `=PMT(B3,B4,B5,B6)`

