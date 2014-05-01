datascrub
=========

Series of scripts to scrub edX dumps into a more queryable format for research.

instructions
---
There are two ways of running this script:  
1. If all the course export .tar.gz files are in one folder, simply run the command:  
    `./parse path/allCourseExports`  
2. If you want to specify one or more paths to various course export .tar.gz files, run with the parameter -m:  
	`./parse -m path/courseExport1.zip path/courseExport2.zip ...`  

updates
---
v0.01b: Added support for for .tar.gz files so no extraction is necessary. Also added support for multiple extractions in one run. Fixed bug regarding bad JSON output format.  
v0.01a: Initial alpha version of script, capable of parsing one extracted course export folder.  

roadmap
---
* adding a "prettified" json parameter to be passed in (currently has to be modified in script)
* updating "data" fields of modules dynamically (known types: html, problem, video)
* adding support for multiple course exports

bug tracker
---

