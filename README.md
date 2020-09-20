# basic-IBM-DB2-command-project-food-ordering-system

This is a group of 2 school project.
The objective of this project is to design a ibm db2 database with food ordering system in mind.
Included are queries to reconstruct the database and a report.
This database is created on IBM DB2.It is recommended that you use the lastest version of db2 to avoid errors.

The order in which the triggers are created is VERY
important as the order in which it excutes depends on the order
it is created.The order are as follows:
<br>
1)Trigger 1(get_detailsPrice)
<br>
2)Trigger 2(get_detailsPriceUpd)
<br>
3)Trigger 3(inv_totalPriceUPD)
<br>
4)Sub queries(inv_totalPriceDel)
<br>
5)Aggregate function(inv_totalPriceIns)
<br>

A 'queries' text document is included for reconstruction of the database.

Thank you for your time!
