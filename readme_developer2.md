# A deep dive into reporting with IBM Envizi
In this article, get an overview of IBM Envizi ESG Suite, focusing on how it aids Sustainability Managers in capturing, consolidating, managing, analyzing, and reporting environmental, social, and governance (ESG) data.

## IBM Envizi: comprehensive ESG suite
IBM Envizi is a SaaS-based ESG software. The IBM Envizi ESG Suite provides comprehensive data and analytics software to collect, manage, and derive insights from environmental, social, and governance (ESG) sustainability data.

### Three pillars of IBM Envizi

Envizi is composed of three pillars to assist you at every step of your sustainability journey, be it consolidating data, streamlining reporting, identifying efficiency and emission reduction opportunities, or informing business strategy.

#### Data foundation

You may have been using a data management platform, Excel spreadsheets, or other internal systems, yet may still lack a robust data foundation. IBM Envizi offers a comprehensive set of data management tools to ensure the quality of data. You can seamlessly capture any necessary data for reporting and decision-making, consolidating all sustainability and energy data from across the organization into a robust and auditable single system of record, enabling you to report with confidence.

#### Reporting and disclosure

Reporting to both internal and external stakeholders while dealing with various frameworks can cause significant challenges. IBM Envizi addresses this complexity by offering a comprehensive suite of reporting tools, including dashboards and templates, designed to streamline the reporting and disclosure processes.

#### Accelerate decarbonization

By leveraging the insights offered on the platform, you can make informed, data-driven decisions, unlocking pathways to achieve your decarbonization goals.

### IBM Envizi modules

IBM Envizi is a modular platform, with a product framework comprising of 9 modules organized into 3 solution pillars, all supported by a robust data management layer. This modular and scalable functionality is designed to address your immediate requirements while offering the flexibility to scale up as needed.

![](/labs/images/001-modules.png)

 <!--- Comment : describe this image, provide brief writeup for the 3 pillars and the 9 modules (what are these/how can they be used) --->
<!--- Comment:Gandhi:response1 module details Updated. Pillars are already explained above.--->


The above picture shows the all the 9 modules. Here is the description about the same.

**Scope 1, 2 GHG Reporting + Accounting**: Take emissions calculations out of spreadsheets with an extensive platform built on the GHG Protocol, enabling you to prepare Scope 1 and 2 data for compliance or voluntary emissions reporting frameworks.

**Scope 3 GHG Reporting + Accounting**: Calculate Scope 3 upstream and downstream GHG emissions across your organization using all methods supported by the GHG Protocol including spend-based, average-data, hybrid and supplier-specific.

**Target Setting & Tracking**: Capture and track sustainability performance targets at any level of your organization with this comprehensive target setting and tracking tool.

**ESG Reporting Frameworks**: Upgrade your ESG data from spreadsheets into a robust platform which is finance-grade so your organization can meet reporting requirements.

**Building Ratings + Benchmarks**: Capture building attribute and utility data, calculate ratings, and benchmark and track building performance in one place.

**Risk + Materiality Assessment**: Analyze ESG performance metrics from your value chain stakeholders to measure their ESG performance and benchmark them with others.

**Value Chain Reporting**: A single portal to easily and securely collect ESG metrics from across your value chain to ease the reporting process.

**Utility Bill Analytics**: Leverage utility billing data inside a powerful analytics engine to analyze and control energy cost and consumption, identify anomalies, and inform decision making for energy efficiency.

**Interval Meter Analytics**: Automate the capture of high-resolution meter data and leverage sophisticated analytics and workflow tools, so your organization can drive efficiency and decarbonize across facilities.

**Sustainability Program Tracking**: Manage your organization’s sustainability programs in a consistent and transparent manner to track progress, verify results and optimize investment decisions.

 <!--- Comment: write how to navigate to the following screen --->
 <!--- Comment:Gandhi:response2 This section will showup, when the Blue circle near the Text "Demo Corp D4" in top navigation bar is clicked. This blue circle show up all time in all the screen. This section is like a home page and everybody knows about it. --->
 
## Data Management

The organization's operations are distributed across different locations, regions, business units, departments, manufacturing sites, suppliers, subsidiaries, and more. Organization needs to gather data from all these operations and guarantee the access to these data at any given moment. Lets see how Envizi is organizing the data.

### Organization Hierarchy

Organization hierarchy includes `Location by Region`,`Classification Groups`, and `Portfolio Groups`.

![](/labs/images/010-orghierarchy-1.png)


### Groups

Groups are  a collection of locations used for reporting or data access.There are two types of groups:

- **Classification Groups**: Represents the foundational structure of the organization. Each location must report 100% through the Classification hierarchy to be fully included in enterprise reporting. If a location is not part of a group, it will be excluded from most dashboards and reports.

- **Portfolio Groups**: Represents secondary reporting structures. A portfolio group may include some or all locations with varying report percentage allocations.

  Subgroups can be created under any of the groups.

Here, you can see the 'Classification' and 'Portfolio' Groups.
<!--- Comment: write how to navigate to the following screen --->
<!--- Comment:Gandhi: Same as response2 --->
![](/labs/images/010-orghierarchy-2.png)

### Locations, accounts, and records

**Locations** describe buildings, properties, assets, or sites within an organization. Each location can have multiple associated accounts, capturing data from various resources.

**Accounts** capture, store, and report data from organizational resources, such as electricity, water, and transport. They are configured at a location level and associated with specific data types and account styles.

**Records** represent actual data from resources, such as electricity consumption for a specific account in a given month.

The Organization hierarchy displays the Group, Subgroup, Location, Account, and Records for easy reference.

![](/labs/images/010-orghierarchy-3.png)


### Categories, data types, and account styles

Envizi includes features such as Categories, Data types, and Account styles for grouping data, describing measures or activities, and configuring data schemas.

- **Categories** serves as a grouping of data types. Your organization is pre-configured with a default set of categories designed for tracking and analyzing data at an aggregated level.

- **Data types** represent individual measures or activities. Examples of data types include electricity, diesel, natural gas, refrigerant R12, water, employees, rail shipping, scope 3 emissions, business travel, rental car, and hotel stays.

- **Account styles** refer to the data schema configured on top of a Data Type. These styles are configured per customer, offering flexibility to meet diverse data capture requirements. 

The image shows the data type as `DIESEL TRANSPORT (MILES)` and the associated account style as `DIESEL TRANSPORT - MILES`.

<!--- Comment: write how to navigate to the following screen --->
<!--- Comment:Gandhi: added the below line --->

(To view this page, open the Organization Hierarchy and click on the respective Account link).

![](/labs/images/112-account.png)



<!--- Comment: Rewrite this entire section similar to other sections--->
<!--- Comment:Gandhi: Done -->

## 3 Data capture

There are several ways available in Envizi to create Group, Subgroup, Location, Account and Record (Data).

### 1. Create Data via UI

Using Envizi User Interface the data capture can be done.

#### Create Group

1. Click on `Manage > Groups`
![](/labs/images/01-group1.png)


It shows the Groups page.

2. Click on `Create New Group` button.

![](/labs/images/01-group2.png)


3. Fill in the details as below.

- Group Type :  `Classification`
- Belongs To : The Org name of the account. Here `Demo Corp D1`
- Name :  Give any name for the Group. Ex: `G1-Telco`
- Report Percent :  100

4. Click on `Save` button.
![](/labs/images/01-group3.png)

A new Group called `G1-Telco` gets created.

#### Create Location

Similarly location can be created by clicking on `Manage > Location`.

#### Create Account

Similarly account can be created by clicking on `Manage > Account`

#### Create Records (Data)

1. Select an account from the left panel.

![](/labs/images/06-load-account-data11.png)

Account summary get displayed as below.

2. Click on `Track > Records`

![](/labs/images/06-load-account-data12.png)

3. Click on `Capture > Data`

![](/labs/images/06-load-account-data13.png)

4. Fill in the details as below.
- Start Period : Enter the starting period of the data
- End Period : Enter the ending period of the data
- Total Electricity :  Enter the total electricity consumed
- Total Cost :  Enter the total cost

The total value would split across each month available in between the given period.

5. Click on `Save` button.

![](/labs/images/06-load-account-data14.png)

The record should be saved successfully.

For the detailed explanations refer the documentation
https://community.ibm.com/community/user/envirintel/blogs/jeya-gandhi-rajan-m1/2023/04/04/create-orghierarchy-and-load-data-in-envizi-via-ui

### 2 Create Data via Universal Data Collector

Envizi allows to Create Group, Location, Account and Records via the excel file upload.

#### Create Groups and Locations

Let us create groups and locations.

1. Download the sample file [Envizi_SetupConfig_G3.xlsx](./files/Envizi_SetupConfig_G3.xlsx). The content looks like this.
![](/labs/images/image-11.png)


2. Update the file as per your requirement.

3. Click on `Manage > Upload files` to upload the file.

The file get processed and the Group and Locations gets created.

#### Account Setup and Data Load

Let us create accounts and data.

Need to download the Template file from Envizi Report.

1. Search for `Account Setup and Data Load` in Reports

![](/labs/images/image-111.png)

2. Open the report

![](/labs/images/image-112.png)

3. Choose the following

- Filter By #1:  Export selected locations with or without records
- Filter By #2:  Choose an account style as per your need
- Starting with: Choose some start date from which data exists in your envizi environment.

4. Click on `Submit`

![](/labs/images/image-113.png)

Report is displayed on the screen.

5. Click on `DOWNLOAD AS CSV`

![](/labs/images/image-114.png)

You may get the csv file as like this.

![](/labs/images/image-115.png)

6. Rename the downloaded file into `Account_Setup_and_Data_Load_xxxxx.csv`

7. Remove the unwanted records

8. Add or update as per your requirement.

9. Click on `Manage > Upload files` to upload the file.

The file get processed and the Accounts and data gets created.

### 3 Bulk Creation and Scheduling of Data Capture Issues

Envizi provides Data Capture Issues as a way to request manual data capture for accounts.

For each data capture activity, users will be notified by e-mail. 
Clicking on the `View Issue` button in the e-mail brings up a browser window with details of this particular data capture item. 
The user can update the item.
Clicking on the `Capture Data` button brings up the survey to complete.



## Reports: Comprehensive reporting options

IBM Envizi offers types of reports: Dashboards, Power Reports, Extract Reports, and Envizi API.

- **Dashboards** are Interactive pages that allow reporting and displaying data visually at various levels, from organizational to meter level. Dashboards provide multiple controls for customization.

<!--- Comment: Describe the following image and how to navigate--->
  [](/labs/images/100-dashboard-1.png)

- **Power Reports** are supercharged by Microsoft PowerBI, offer visual dashboards to support reporting. Standard and configurable reports include sustainability, portfolio performance, and more.
<!--- Comment: Describe the following image and how to navigate--->
	![](/labs/images/100-power-report.png)

- **Extract reports** allow you to specify selection criteria, view data on screen, download, and send reports via email in various formats (CSV, PDF, XLSX). Scheduled reporting options are also available.

  - Select of delivery methods such as screen or email.
  - Choose groups, locations, Regions, Utilities, and report time period/end date.
  - Opt immediate report creation and email delivery in CSV, PDF, or XLSX format using "Create Report and E-mail it now."
  - Schedule future report delivery with options like Daily, Weekly, etc., through "Schedule Report and E-mail it later."
  - Click Submit to run the report based on the selected parameters.
  <!--- Comment: Describe the following image and how to navigate--->
  
  ![](/labs/images/100-extract-report-2.png)

- **API** enables data sharing and retrieval directly through compatible third-party software, promoting efficient reporting and data analytics.

## Disclosures: Streamlining ESG reporting

During ESG reporting, IBM Envizi supports Sustainability Managers in efficiently organizing data for ESG disclosures. Pre-configured templates and reports streamline disclosure processes.

- **Sustainability Reporting Manager (SRM)**: A tool that pulls together quantitative data, attachments, web links, and response methodologies to manage ESG data and formulate final responses.

  The SRM tool covers an extensive array of ESG Frameworks, including `TCFD, SASB, GRI, SFDR, UN SDGs, INREV, EPRA, SEC Climate Proposal, EU Taxonomy, PRI, and BRSR`.
   <!--- Comment: Describe the following image and how to navigate--->
  ![](/labs/images/110-srm.png)

- **GRESB and CDP**: IBM Envizi supports widely used frameworks comprehensively and provides alternative tools for specific frameworks such as  `GRESB` and `CDP`.
 <!--- Comment: Describe the following image and how to navigate--->
  ![](/labs/images/111-cdp.png)

## Decarbonization: Tools for sustainable strategies

Envizi offers modules and tools for organizations' decarbonization strategies.

- **Target Setting and Tracking**: Capture and track sustainability performance targets at different levels of the organization with intuitive dashboards and reports.

   <!--- Comment: Describe the following image and how to navigate--->
	![](/labs/images/200-target-setting-rate-analysis.png)

- **Building Ratings + Benchmarks**: Capture building attributes and utility data, calculate ratings, and benchmark and track building performance.

   <!--- Comment: Describe the following image and how to navigate--->
	![](/labs/images/250-energy-star.png)

- **Sustainability Program Tracking**: Track progress, verify results, and optimize investment decisions for sustainability programs.

   <!--- Comment: Describe these images and how to navigate--->
	![](/labs/images/210-programs-1.png)

	![](/labs/images/210-programs-2.png)

- **Utility Bill Analytics**: Leverage powerful analytics for analyzing and controlling energy costs and consumption.

   <!--- Comment: Describe the following image and how to navigate--->
	![](/labs/images/221-utility-bill.png)

- **Interval Meter Analytics**: Automate high-resolution meter data capture and use sophisticated analytics for efficiency and decarbonization.

   <!--- Comment: Describe the following image and how to navigate--->
	![](/labs/images/240-interval-utility-performance-management.png)


### Conclusion

In conclusion, IBM Envizi ESG Suite provides a comprehensive solution for organizations aiming to simplify their sustainability journey through effective data management, reporting, and decarbonization strategies.

For more information, visit the [IBM Envizi ESG Suite](https://www.ibm.com/products/envizi) page. You can also explore the collection of self-serve assets on [GitHub repository](https://github.com/ibm) and, if you are an IBM Business Partner, access additional assets at [Tech Zone](https://techzone.ibm.com/).

