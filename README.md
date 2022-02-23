# useR-Package-Proposal
Project scope to explore intelligently combine existing functions and processes within SQL based R libraries. End goal is to provide GUI interface for connection, discovery, and query building.

	Package creation in R for use with rquery and DM 
https://cran.r-project.org/web/packages/rquery/vignettes/rquery_intro.html
https://krlmlr.github.io/dm/articles/dm.html
https://krlmlr.github.io/dm/

https://db.rstudio.com/r-packages/dbi/

Abstract rough idea. While utilizing SQL queries to pull in data from a multitude of possible databases these tools provide an excellent foundation for access, exploration, and query cultivation in R.
DBI: Creates the ODBC connections to data sources
DM: Creates ERD diagrams of the selected tables and columns.
Rquery: Builds SQL adaptive queries to be generates in R

To create visual tool that allows:
1.	[DBI] Select database 
a.	Type of ODBC
b.	Credentials
2.	[DM] Review database structure
a.	Selecting available schemas
b.	Select Tables of interest
3.	[RQuery] Create query 
a.	Dropdowns to Select 
i.	Columns
ii.	Tables (Joins)
iii.	Filter parameters
iv.	Group by
This visual will then generate the multiple R code snippets to generate the code in a clear precise output.

