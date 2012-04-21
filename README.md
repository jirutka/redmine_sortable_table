Sortable Tables
===============

Plugin for easy create sortable tables in redmine wiki.

By ideas of http://www.redmine.org/issues/1718. Based on [unobtrusive table sort script revisited](http://www.frequency-decoder.com/2006/09/16/unobtrusive-table-sort-script-revisited), big thanks to Brian McAllister.


Usage
-----

    {{sortable_table}}


    |_(sortable). Column 1|_(sortable-numeric). Column 2|_. Unsortable|
    |bbbb|12|something|
    |aaaa|24|anything|
    |cccc|9|nothing|

More info about sorting:
  http://www.frequency-decoder.com/2006/09/16/unobtrusive-table-sort-script-revisited



Installation
------------

1. copy plugin into `vendor/plugins` directory with name `sortable_table`
2. restart redmine



How it work
-----------

* macros `sortable_table` include required javascript and css files.
* included javascript automatically make sortable all tables with columns headers class `sortable*`


What’s new in this fork?
------------------------

* Redesigned sortable header – simple arrows on transparent background and nothing more (i.e. inherit user’s style of table header).
