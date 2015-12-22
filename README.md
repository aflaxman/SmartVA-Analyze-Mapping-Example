# SmartVA-Analyze-Mapping-Example

Example process of mapping existing VAI data into a format that can be
used as input to SmartVA-Analyze 1.1.


# Short version

SmartVA-Analyze 1.1 accepts a csv file as input, and expects a column
for every field name in the "Guide for data entry.xlsx" spreadsheet.

It also requires a handful of columns that are not in the Guide (because they do not contain data):

* child_3_10
* agedays
* child_5_7e
* child_5_6e

It is possible to run a csv through SmartVA-Analyze 1.1 without values in these columns.  Try it with example_1.csv.

Mapping the data from your existing database into this format requires careful attention to detail.


# Examples

* IPython Notebook showing a simple, hypothetical example
* More examples to come (it would be nice to have Stata and R examples... Pull requests welcome!)
