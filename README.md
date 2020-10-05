# QRDS
Relevant data stream for the offense summary pages

This application is designed to explain how to enrich QRadar UI and enhance Analyst experience.

Main topics adresses are :
- how to use Fragments to insert your dev in an existing QRadar screen (offenses)
- AQL request and how to isolate events and flows that participate to an offense
- how to use a graphical library to display results


v3.8
added highchart library as a static module to avoid external communications

v1.2
added flow size for src and dst.
Alert is now a spline graph
known issue : may hang on firefox when disabling a series by clicking on the label
![Screenshot](screencap12.jpeg)

v1.1
initial release
![Screenshot](screencap.jpeg)
