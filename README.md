ElyCharts
=========

Interactive Javascript (SVG|VML) Charting Library

NOTE: Feb 2014: recommend the new Elycharts 2.x here: https://code.google.com/p/elycharts/

Don't use master... use dev-forward (branch)

After some searching (google code, github), this seemed to be the most up-to-date branch/version of Elychart to fork from:
https://github.com/pduval/ElyCharts/commit/ee6be7ccaefab3bade534101de361afce5810d0f
(https://github.com/pduval/ElyCharts/)

It also appeared to be the version that was being issued at the Official Elychart website, although it hadn't been pulled into "voidlabs / ElyCharts" (as of March-ish 2013).
Notice that the most recent commit from "pduval" was skipped; this was not part of the Official Elychart website release.

This branch works well with this particular version of Raphael:
http://raw.github.com/DmitryBaranovskiy/raphael/dbe241f4c5310dd9bf3b451c538d78c6c4a0e288/raphael.js
(http://github.com/DmitryBaranovskiy/raphael/commit/dbe241f4c5310dd9bf3b451c538d78c6c4a0e288)
(http://github.com/DmitryBaranovskiy/raphael/commits/2.0) (a commit in this branch)

It does NOT work with Raphael 2.0; that could be a new project.

It works well with jQuery 1.7.1.

The modifications in this fork were made to suit some development needs, such as:
line chart: skipping null values instead of averaging over them
pie chart: centering the tooltip
... plus more
