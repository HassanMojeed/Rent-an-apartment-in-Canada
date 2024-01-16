# Rent-an-apartment-in-Canada
This project delve into the real estate (house rental) industry in Canada.
### [Click here for the dynamic visuals](https://app.powerbi.com/view?r=eyJrIjoiNDIxOGNjZWMtNDMwZi00NWNhLTkzZDktM2Y3NDEyNzBhYzNiIiwidCI6ImFlM2E5OTA2LTc4MWEtNDQ2YS1iZGI2LTYzNzdjMDllMmM2ZiIsImMiOjF9&pageName=ReportSection)

### Introduction
In this project, I will conduct an in-depth analysis of long-term rental pricing in Canada, leveraging the booming real estate market. The primary goal of this project is to uncover patterns related to apartment types, costs, and locations. By deciphering the dynamics that influence housing trends nationwide, this analysis aims to offer valuable insights for both tenants and investors.

### Data Collection

The data used in this project was scraped from Kijiji, a well-known Canada's leading local classifieds platform, facilitating the buying, selling, and trading of a wide range of items, including cars, real estate, jobs, services, and more. It operates as a subsidiary of eBay and has a significant presence in Canada, as well as in other countries like Switzerland, Austria, and Japan. 
 
 I will be performing some activities such as;

- Looping: to iteratively navigate through pages, and
- Extracting vital information such as:

    1. Apartment type
    2. Rental cost
    3. Location
    4. Description
    5. Number of rooms. 


To efficiently parse the HTML content, I will use the BeautifulSoup library.

### Data Processing
The data processing and cleaning procedures in the involve employing diverse techniques. To extract attribute-based text, a custom function called extract_text is utilized, while specific HTML tags are employed to target relevant information.

### Data Export
The data is transformed into a Pandas DataFrame after undergoing a cleaning process. Subsequently, the final DataFrame is exported to an Google sheet file in order to facilitate further analysis. This step guarantees a consistent and easily accessible format for subsequent stages.

### Data Visualization
Utilizing Power BI, the exported data is transformed into visually appealing dashboards and impactful visual representations of key metrics. By harnessing the capabilities of Power BI, stakeholders gain a holistic view of rental patterns, facilitating informed decision-making in the ever-evolving real estate market.
