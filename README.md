spreadsheet-to-gui - Ergaster
=============================

Convert Microsoft Excel Spreadsheets to User Friendly Input and Reporting Screens.

Too often companies create huge collections of undocumented, hard to maintain, and non-user friendly spreadsheets. The spreadsheet paradigm is suitable for formulae and what-if analysis but it does not have the same set manipulation and querying capability found in relational databases. 

In addition, applying the principals of programming logic in a spreadsheet is unwieldy when extending across multiple columns, rows, worksheets, and spreadsheets. Though Microsoft continues to roll out enhancements such as aliases, these only highlight that a spreadsheet really is not the context for more advanced programmatic operations.

Two key concerns are data quality and usability. Data quality requires traceability of changes and the ability to revert back to correct errors. However, without a suitable framework, enforcing data quality in spradsheets is frequently an after-thought or requires brute-force and a lot people checking for errors.

Spreadsheet-to-gui (project Ergaster "Working Man") takes a MS Excel spreadsheet and converts it into a Grails user interface that makes the navigation and modification of spreadsheets more humane and rational. The architecture is a such:

(1) GUI - Presentation Layer GRAILS / Apache with custom controls
(2) Object to Relational Layer (ORM) -  (MYSQL database but can be switched)
(3) Object Layer
(4) Translation Layer - Read/write spreadsheets into mappings
(5) File Layer - Management of import spreadsheet imports into Ergaster system

Ergaster will not only load data but also Excel formulae and incorporate them into object constraints and methods.

