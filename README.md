# DrChecksParser
Simple VBA Code to (batch) Parse and Summarize Dr Checks XML Files with colorized formating.

## Quick Start Guide
You can download the .bas file and import into a macro-enabled Workbook, or simple download the *BSF DrChecks Plugin v2.xlsm* Worbook. The only visible method is the MAIN() method, which is merely a wrapper function.

1. Export full Dr Checks reports from ProjNet as XML - it's recommended to export the full report. Make sure you only use XML exports from ProjNet.
2. Save one or more of these XML reports in a folder - the names of the files doesn't really matter, just don't overwrite other XML reports.
3.  Run the MAIN() function adn select the folder

The code will generate a new Workbook alongside the XML files, with a timestamp. It will include the summary of each XML report as a different tab in the Workbook.

### Documentation

I am currently working on more robust documentation.
