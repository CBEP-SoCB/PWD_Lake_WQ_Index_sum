# Portland Water District Lake Water Qulaity Index

<img
    src="https://www.cascobayestuary.org/wp-content/uploads/2014/04/logo_sm.jpg"
    style="position:absolute;top:10px;right:50px;" />

This short repository includes data that underpins the Portland Water District 
(PWD) Lake Index, and code for redrawing their excellent summary graphics in
R. The primary purpose of the repository is to redraw those graphics so that
they look more similar to other graphics in the SoCB report.

# Statement of Purpose
CBEP is committed to the ideal of open science.  Our State of the Bay data
archives ensure the science underlying the 2020/2021 State of Casco Bay report
is documented and reproducible by others. The purpose of these archives is to
release  data and data analysis code whenever possible to allow others to
review, critique, learn from, and build upon CBEP science.

# Archive Structure
CBEP 2020/2021 State of the Bay data analysis summaries contain a selection of 
data,  data analysis code, and visualization code as used to produce 
results shared via our most recent State of Casco Bay report. Usually, these
archives are organized int otwo or three folders, including the following:

- Data.  Contains data in simplified or derived form as used in our
data  analysis.  Associated metadata is contained in related Markdown documents,
usually `DATA_SOURCES.md` and `DATA_NOTES.md`.

- Analysis.  Contains one or more R Notebooks proceeding through the principal
data analysis steps that underpin SoCB reporting. To simplify the archives,
much preliminary analysis, and many analysis "dead ends" have been omitted. 

- Graphics.  Contains R Notebooks stepping through development of graphics, and
also copies of resulting graphics, usually in \*.png and \*.pdf formats.  These
graphics may differ from graphics as they appear in final State of the Bay
graphical layouts. Again, most draft versions of graphics have been omitted for 
clarity.

This repository includes no graphics code, as site-by-site variation in 
conditions strongly dominate the observed patterns, and those differences are
most easily shown via maps. The "Analysis" folder includes code that explores
ways to analyze these data to evaluate long-term trends (none were found), and
export data that could be used in GIS to produce informative maps.

# Summary of Data Sources
Data was derived from an Excel File provided by Portland Water District, and is 
based on data that underlies the following paper:

> Hunt, Paul T., Kate McDonald, and Kirsten Ness. 2016. Sebago Lake, Maine and 
the Water Quality Index: A Method for Subwatershed Protection. LakeLine, 
36(3)10-18. North American Lake Management Society. Fall 2016. Available here: <https://www.pwd.org/sites/default/files/hunt.pdf>.