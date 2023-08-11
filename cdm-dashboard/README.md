# CDM Dashboard and SLA Tracking
SLA Tracking project for the CDS department. This project aims to use CDM task data in order to outline the quantity and time taken of tasks completed by the CDS department.

Data is downloaded from the CDM platform in the form of 4 reports:
- Team Report
- Team Tasks Report
- Task History Report
- User Report

The scripts read and process the data and determine:
- The number of tasks completed and rejected for each process
- The median turnaround time for each process
- The number of overdue tasks at the end of each month
- The number of tasks with missing task tracking information (missing process type, missing case number)
- The breakdown of rejected tasks and their respective rejection reasons

The end goal of this project is to monitor the productivity of the CDS department and even expand into monitoring trends for individual workers. We are considering generating a BI dashboard from this data to show trends graphically.


