# Furlough_Tool_Supply_Chain

This README file is for an interactive Excel dashboard for furloughing supply chain employees during the early days of the pandemic. Although not the most sophisticated spreadsheet in history, it was built on the fly, under severe time pressure in little more than two days. This README provides a clear and professional overview of the project, including its purpose, features, and how to use it.

About

This project is an interactive Excel dashboard designed to furlough supply chain personnel as quickly as possible, in an organized fashion, and on an industrial scale. The dashboard leverages Excel features such as VLOOKUPs, SUMIFs, COUNTIFs, and array formulas.

Executive Summary

The Business Problem: With the onset of the pandemic in March and April of 2020 sales volumes dropped drastically. The drop was so immediate and across the board that an organized procedure needed to be developed to rapidly furlough up to 40% of the employees in the supply chain warehouses and distribution centers. The furlough method needed to be consistently applied across the United States supply chain locations to avoid legal ramifications.

The Solution: The fairest method to furlough employees was by seniority. The most experienced senior workers would retain their full hourly shifts and the lower seniority employees would either work reduced hours or be furloughed until volume increased. A furlough tool was developed, replicated, and sent out across locations to enable the above.

Next steps: After the initial furlough of approximately 25% of the workforce, there were weekly stakeholder meetings to determine necessary headcount depending on volume projections for the coming weeks. As volume returned to normal, more and more workers were brought back, some reluctantly as pandemic era unemployment paid more than their respective hourly wages

The Impact: 95% of furloughed workers were eventually brought back and the furlough program concluded after three months as pandemic consumer behavior ‘normalized’. The furlough tool was briefly considered for a corporate furlough, but layoffs were used instead.

Dashboard Features

Furlough: This sheet allows users to select locations by a dropdown in cell B4. Once the location had been selected the various department personnel were displayed by department manager.  Volume projections were then used to determine necessary staffing needs for individual departments with the percent decrease in staffing inputted in cell I4 (for the first department at least). Employees were ranked in order of decreasing seniority and any employees in gray highlighted areas were subject to the furlough. This process was carried out for each department moving left to right across the sheet, with enough departments built in to the tool to accommodate the largest facilities, but most facilities not needing all of the department slots.

Facility_View: This tab was requested by facility management to get an overall view of building headcount by department and job title. Volume amounts (anticipated and usual) by worker hours were also added for management to see the volume difference in employee hours. The tab didn’t really move the needle for me but building management liked it.

Skills Used

Microsoft Excel: Used for all data manipulation, calculations, and visualization.

SQL: Used to customize the backend reporting (hidden USSSD tab) such as Headcount and New Hire reports.

Author

Ian Hood – github.com/Hood-Analytics
