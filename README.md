# Gun Violence Analysis (Python)
## Motivation
To foster gun violence awareness throughout the U.S. and educate the public on gun violence incidents in the U.S. The analysis provides insights about gun violence incidents as it relates to States, frequency of incidents over time, and gender.
## Data Source and Limitations
This is an external data source accessed via Kaggle. Dataset is originally from gunviolencearchive.org. GVA is a is an independent collection and research group (with no affiliation to any advocacy organization), and a not-for-profit corporation that formed in 2013 to provide free online public access to accurate information about gun-related violence in the United States. GVA is a trustworthy data source that contains government and local law enforcement data.

Since GVA limits the number of incidents that are returned from a single query, and because the website's "Export to CSV" functionality was missing crucial fields, it was necessary to obtain the dataset using web scraping techniques. Limitations include data for 2013 having limited records, some manually entered data, and dataset only including incidents of gun violence that were reported to law enforcement.

Data was collected from over 7,500 local law enforcement, media, government and commercial 
sources. Data has been checked for accuracy before posted and disseminated online.
Kaggle lists the following information regarding data collection and its limitations:
Because GVA limits the number of incidents that are returned from a single query, and because the 
website's "Export to CSV" functionality was missing crucial fields, it was necessary to obtain this 
dataset using web scraping techniques.

Stage 1: For each date between 1/1/2013 and 3/31/2018, a Python script queried all incidents that 
happened at that particular date, then scraped the data and wrote it to a CSV file. Each month got 
its own CSV file, with the exception of 2013, since not many incidents were recorded from then.

Stage 2: Each entry was augmented with additional data not directly viewable from the query 
results page, such as participant information, geolocation data, etc.

Stage 3: The entries were sorted in order of increasing date, then merged into a single CSV file.

Other data limitations:

*Data for 2013 has limited records.

*Data contains some manually entered data so there may be some human error or incorrect data.

*Data only includes incidents of gun violence that were reported to law enforcement.
## Data Contents
Dataset is a comprehensive record of over 260k US gun violence incidents from 2013-2018.
Consists of 29 columns that includes the number of individuals killed or injured, source URL, the 
number of guns involved, gun type, whether the gun was stolen, address of incident, as well as 
information on state legislature and a notes column.
## Data Relevance 
This data is relevant and contains multiple dimensions in relation to gun violence incidents in the 
U.S. The dataset also meets all of the project requirements.
## Data Ethics
Though data is publicly available, ethical considerations of PII should be prioritized to protect 
individuals from identifying information such as first and last name data. The data source has been 
transparent and accountable in their data collection methods.
### Key Questions:
1. Do gun violence incidents vary in frequency throughout the year? Is there a trend or pattern 
to the data?
2. Do some states have a higher count of gun violence incidents than others? Which States 
have the highest gun violence related deaths?
3. What changes over time does the data show relating to gun violence incidents frequency?
Have incidents increased or decreased over time?
4. Does gender play a role in the incidents of gun violence?
