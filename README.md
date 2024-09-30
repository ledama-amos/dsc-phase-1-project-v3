The aviation industry offers a variety of options regarding dimensions, functionality, cost, and safety. This analysis aims to examine the safety and well-being of different aircraft by utilizing accident data from the Aviation_Data.csv file.



Notebook Structure
Data collection

Data preprocessing

Exploratory data analysis(EDA)

Comparative analysis and Visualization

Conclusion and insight
Business Questions with Respect to Safety
What are the best types of aircraft to invest in that are the least risky?
How to guarantee which engine type is the safest in an aircraft?
What backup plans are in place for flight systems?

Problem Statement: Determine the least hazardous aircraft for launching the company's new initiative at a competitive and equitable price, while ensuring a successful market entry.

Key Stakeholders: The stakeholders will encompass a diverse group, including internal parties such as company stakeholders and potential investors, as well as external factors like government regulations, competing airlines, and customers.

Responsibility: Successfully adapting to the aviation sector and choosing an aircraft that presents the lowest risk.

Resources: Industry reports, budget allocations, aircraft safety data, and expert consultations.

Risks: Potential financial losses and incidents related to safety.



Project Overview:
This project aims to identify the types of aircraft used in commercial and private sectors, as well as to determine which manufacturing and assembly companies are more prone to accidents and incidents. I intend to investigate whether these accidents are primarily due to human error or the condition of the aircraft. Understanding the frequency of accidents and losses in the industry is crucial, so I seek to ascertain how often aircraft accidents occur.


Data Understanding:
My project involves data that has been gathered by various data scientists. This information is hosted on Kaggle, where it is regularly updated and available in CSV format. When I load the data into my notebook using the pandas library, I obtain a data frame consisting of 90,348 rows and 31 columns. A quick glance at the data frame reveals that the information pertains to an investigation of aircraft accidents. The dataset includes both categorical and continuous variables, with the former comprising the majority of the data.

ata Cleaning:
After gaining an understanding of the data, I delved deeper to identify what is essential and why. It's vital to enter the market armed with clear, thorough, and relevant knowledge. I calculated the percentage of missing values across all columns, which helped assess their significance in providing key insights for my project.

I opted to remove columns that were not pertinent to my analysis, including: Schedule, FAR.Description, Latitude, Longitude, Location, Air.Carrier, and Airport.Name. The Schedule column had over 85% of its values missing, while the Air.Carrier column had more than 80% missing values as well.

Conclusion and Findings
From the detailed analysis and exploratory data analysis (EDA) conducted, the following conclusions can be made:

The engine type most associated with fatal accidents was the turbo fan, while geared turbo fan and LR engines proved to be the safest, as they did not result in any accidents.

The safest aircraft identified were blimps and airplanes. Blimps reported no fatalities and a low overall injury rate, while airplanes exhibited low fatal injury rates and the highest number of uninjured individuals, indicating they are relatively safe.

The WSFT aircraft recorded the fewest survivors following accidents, leading to its classification as the most dangerous aircraft.

Conversely, the Powered-Lift, ULTR, and UNK aircraft did not result in any fatal injuries in the event of an accident.

Recommendations



Based on our findings and insights, we can proceed with the following recommendation: The optimal engine types for aircraft are Geared Turbofan and LR, as they have not caused any fatal accidents. As the company considers entering this market, it should invest in these two enginesSS