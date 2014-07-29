FastFilter For Actuate BIRT Reports
===================================

Get instantaneous satisfaction with Fast Filter for BIRT reports.

The goal is to allow users to filter their report tables with the minimum number of clicks. There are two types of fast filters: column searches and table wide searches.  With Fast Filter, every table can Excel-like filters on specified table columns and/or a single edit box to search every column in a table. Column searches and table wide searches seamlessly work together and the results are additive.  You can clear the results of a column filter or table wide filter without clearing the other filters.  Aggregations and charts that are based on the table data will automatically be updated.

For a column search, a user can simply select the value from the list of distinct values in the dropdown and only the rows with the selected column will appear.  After the table is updated, the selected value in the column filter drop down will be “Filtered.”  To clear the column filter, click on the filter dropdown and select “<Clear Filter>”.

For table-wide searches, just enter a phrase in the edit text box.  Table-wide searches are additive, you can narrow down your search results by simply adding another search string.  If you enter a number, that number will be searched in all numeric columns.  To the left of the table wide search edit box, there is a check box to ignore the case of the search strings.  To the right of the search edit box, there is a list of terms that you have searched for.

Developers are able to add the FastFilter code to any BIRT report that has tables. All of the javascript code is added the report’s “onContentUpdate”.  They can implement the column search fast filters on any column that they want.  For each column that you want a fast filter for, you need to add a <select> tag in a html edit box.  Blah, blah…

Of course, nothing is free.  If you add Fast Filter to your tables, the amount of time required to render the report increases.  The amount of time increases with the number of fast filter columns that you add and the number of pages returned.  The table wide search feature does not significantly increase report render time.
 
