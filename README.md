# gsheet-importrefresh
Function for refreshing Google sheets Import-x functions to facilitate automated refreshes via time trigger

Go through all sheets in a spreadsheet, identify and remove all spreadsheet import functions, then replace them a while later. This causes a "refresh" of the "import" functions. For periodic refresh of these formulas, set this function up as a time-based trigger.

 * Caution: Formula changes made to the spreadsheet by other scripts or users during the refresh period COULD BE OVERWRITTEN.
 * From: http://stackoverflow.com/a/33875957/1677912
