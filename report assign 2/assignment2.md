# Report Assignment 2
## Question 1
- graphical report
- num of successful deliveries by transport type (transport description column)
- input data range (start and end date)

## Question 2
### A
- number of deliveries
- grouped by Service Type, Customer, Quarter of the Year
- Groups initially collapsed
- user can drill down into desired group
- group totals visible when group is collapsed

### B
- expand report built under item A.
- to the right, new report summarized deliveries:
	- by Month and day of the week
- bottom of this report: summary of number of deliveries BY BUSINESS TYPE

## Question 3
- Interactive maintenance report
- front end : list all repairs performed by employee
	- user clicks on repair to see the complete repair report

## Helpful Links
### Adding Interactive Features
#### Customizing Report Parameters
- Create DataSet to the report
- e.g. Query to get all dates in report
- Double Click Parameter that exists
- Property pages
- Available Values
	- get values from a query!!
	- select data set from the report
- Value field: what column you are looking for
- What value to display


#### Applying Interactive Sorting:
- click on the title of the column
- make sure you're selecting the text box
	- Properties (NOT SelectedText- can hit ESC)
	- Properties e.g. (TextBox2)
- Properties Pages
	- Interactive Sorting Option
	- Check checkbox
		- Detail Rows
		- Groups if have group row
	- sort by : select column data

#### Subreports
- Add a report as a table
- drag and drop a subreport
	- SubReport Properties
	- Browse for report to use as subreport
	- select Parameter to join the two together


#### Drillthrough report
- Have report to drilldown from
- Create new Report
- with data set etc
- get the drilldown info that you need for this report

#### Drilldown matrix
- make data set for matrix
- make data set for drilldown
- follow https://www.lynda.com/SQL-Server-tutorials/Adding-sparkline-drilldown-matrix/110282/118664-4.html


##### Applying An ACTION
- Apply to the textbox
- Open property pages
- Action Page
	- Go to report
	- Browse for drilldown report
	- Add parameters (what param from report to send)
		- what value (pass the options in data set e.g. an id)
- When you click on the category it will jump to the second report
- Design View -> Select Text -> Change colour to Dark blue to make it look like a link

#### Report Parts
- combine multiple elements at the same time
- useful to configure pieces individually and configure them later
- save tables by themselves as report parts
- create a regular report
- File > Publish Report PArts
	- review and modify report parts before publishing
	- scans currently open report and says what can be published



