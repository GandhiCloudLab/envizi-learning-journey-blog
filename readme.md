# Envizi Learning Journey

This article gives you an overview about IBM Envizi ESG Suite and how it helps the Sustainability Manager of an organization to simplify the capture, consolidation, management, analysis and reporting of their environmental, social and governance (ESG) data.

#### Authors
[Jeya Gandhi Rajan M](https://community.ibm.com/community/user/envirintel/people/jeya-gandhi-rajan-m1), [Indira Kalagara](https://community.ibm.com/community/user/envirintel/people/indira-kumari-kalagara1), [Mamatha Venkatesh](https://community.ibm.com/community/user/automation/people/mamatha-venkatesh)

## 1. Envizi 
[IBM Envizi ESG Suite](https://www.ibm.com/products/envizi) is a SaaS based ESG software.  

IBM Envizi ESG suite offers comprehensive data and analytics software to collect, manage and derive insights from your environmental, social and governance (ESG) sustainability data.

### 1.1 Three pillars of Envizi
Envizi is composed of three pillars to helps clients at every step of their sustainability journey, whether they need to consolidate their data, streamline reporting, identify efficiency and emission reduction opportunities, or inform business strategy. 

#### Data Foundation
Clients may have already been using a data management platform, Excel spreadsheets, or other internal systems, but are still lacking a strong data foundation. Envizi provides a rich set of data management tools to ensure quality data, clients can automatically capture any data required for reporting and decision-making and consolidate all sustainability and energy data from across an organization in a robust and auditable single system of record that allows clients to report with confidence

#### Reporting and Disclosure
Reporting to internal and external stakeholders and dealing with multiple frameworks can be challenging. Envizi provides a suite of reporting tools, such as dashboards and reporting templates that help users to streamline reporting and disclosure. 

#### Accelerate Decarbonization
By using the insights provided on the platform, users are empowered to make informed data-driven decisions to unlocking pathways to decarbonization goals.

### 1.2 Modules
Envizi is a modular platform. The product framework consists of 9 modules with 3 solution pillars, underpinned by the data management layer. The modular and scalable functionality ensures clients current needs are met now and can scale up as needed. 

<img src="images/001-modules.png">


## 2 Data Management

The organization's operations are distributed across different locations, regions, business units, departments, manufacturing sites, suppliers, subsidiaries, and more. Organization needs to gather data from all these operations and guarantee the access to these data at any given moment. Lets see how Envizi is organizing the data.

### 2.1 Org Hierarchy

Envizi facilitates the organization of data through a hierarchical structure, enabling the creation of groups, subgroups, locations, accounts, meters, records, and more.

Here is the organization hierarchy that shows `Location by Region`, `Classification` and `Portfolio` Groups.

<img src="images/010-orghierarchy-1.png">

### 2.2 Groups

Groups are a collection of locations used for reporting or data access.

Groups are two types. The previous 2 images shows both the groups.
- Classification group
- Portfolio group

**Classification :** Classification type represent the foundation structure of the Organization. Each location must report 100% through the Classification hierarchy in order to be 100% included in enterprise reporting. If a location is not part of a group then it will be excluded from most dashboards and reports.

**Portfolio :** Portfolio type groups to reflect secondary reporting structures. 
A portfolio group may include some or all locations of varying report percentage allocations.

Subgroups are created under any group. 

Here you can see the `Classification` and `Portfolio` Groups.
<img src="images/010-orghierarchy-2.png">

You can see the Group, Subgroup, location, account and records in the Org Hierarchy here.
<img src="images/010-orghierarchy-3.png">

### 2.3 Locations

Locations are used to describe buildings, properties, assets or sites within an Organization. An Organization can have multiple locations. Locations can also represent a virtual collection of account data.

The below screenshots shows that the Account is associated with a Location.

### 2.4 Accounts

Accounts are used to capture, store and report data from the various resources of an organization such as electricity, water, transport and etc.

It is configured at a location level. 
Account is associated with specific specific `data type` and `account style`.

The image shows the Data Type as `DIESEL TRANSPORT (MILES)` and Account style as `DIESEL TRANSPORT - MILES`
<img src="images/112-account.png">

### 2.5 Records

Records represents the actual data from the resources. Ex: The electricity consumption of a particular account for the month.

The above image show the records associated with the account.

### 2.6 Categories

A Category in Envizi is grouping of data types.

Your organization is setup by default with a set of categories that are useful for tracking and analyzing your data at an aggregated level.

The below picture shows that there is a Category called `Electricity` that groups all the electricity related data types here.

<img src="images/113-datatype1.png">


### 2.7 Data Type

Data types in Envizi describe a single measure or activity. 

The example data types are Electricity, Diesel, Natural Gas, Refrigerant R12, Water, Employees, Rail Shipping, Scope 3 emissions, Business Travel, Rental Car, Hotel Stays.

Data type contains the primary unit of measure `cost` and `consumption`.

Data type is assigned with some emissions scope (1/2/3/None). You can see in the above picture that each data type is associated with an scope.
 
### 2.8  Account Styles

Account Styles refers to the Data schema configured on top of a Data Type.

Account Styles are configured per customer to provide flexibility to meet different data capture requirements.

Account style defines the data fields (primary and secondary fields) to be captured 

Already 600+ account styles are available for the data type Electricity [kWh]

Here the primary field is `Distance Travelled (qty)` and secondary fields are `Cost` and etc.

<img src="images/114-account-style.png">


## 3 Data capture 

There are several ways available in Envizi to create Group, Subgroup, Location, Account and Record (Data). 


### 3.1 Create Data via UI

Using Envizi User Interface the data capture can be done.

#### Create Group

1. Click on `Manage > Groups` 
<img src="images/01-group1.png">

It shows the Groups page.

2. Click on `Create New Group` button.

<img src="images/01-group2.png">

3. Fill in the details as below. 

- Group Type :  `Classification`
- Belongs To : The Org name of the account. Here `Demo Corp D1`
- Name :  Give any name for the Group. Ex: `G1-Telco`
- Report Percent :  100

4. Click on `Save` button.
<img src="images/01-group3.png">

A new Group called `G1-Telco` gets created.

#### Create Location

Location can be created by clicking on `Manage > Location`.


#### Create Account

Account can be created by clicking on `Manage > Account` 


#### Create Records (Data)

1. Select the account from the left panel. 

<img src="images/06-load-account-data11.png">

Account summary get displayed as below.

2. Click on `Track > Records` 

<img src="images/06-load-account-data12.png">

3. Click on `Capture > Data` 

<img src="images/06-load-account-data13.png">

4. Fill in the details as below. 
- Start Period : Enter the starting period of the data
- End Period : Enter the ending period of the data
- Total Electricity :  Enter the total electricity consumed
- Total Cost :  Enter the total cost

The total value would split across each month available in between the given period.

5. Click on `Save` button.

<img src="images/06-load-account-data14.png">

The record should be saved successfuly.

For the detailed explanations refer the documentation
https://community.ibm.com/community/user/envirintel/blogs/jeya-gandhi-rajan-m1/2023/04/04/create-orghierarchy-and-load-data-in-envizi-via-ui

### 3.2 Create Data via Universal Data Collector

Envizi allows to Create Group, Location, Account and Records via the excel file upload.

#### Create Groups and Locations

Let us create groups and locations.

1. Download the sample file [Envizi_SetupConfig_G3.xlsx](./files/Envizi_SetupConfig_G3.xlsx). The content looks like this.
<img src="images/image-11.png">

2. Update the file as per your requirement.

3. Click on `Manage > Upload files` to upload the file.

The file get processed and the Group and Locations gets created.

#### Account Setup and Data Load

Let us create accounts and data.

Need to download the Template file from Envizi Report.

1. Search for `Account Setup and Data Load` in Reports

<img src="images/image-111.png">

2. Open the report

<img src="images/image-112.png">

3. Choose the following 

- Filter By #1:  Export selected locations with or without records
- Filter By #2:  Choose an account style as per your need
- Starting with: Choose some start date from which data exists in your envizi environment.

4. Click on `Submit`

<img src="images/image-113.png">

Report is displayed on the screen.

5. Click on `DOWNLOAD AS CSV`

<img src="images/image-114.png">

You may get the csv file as like this.

<img src="images/image-115.png">

6. Rename the downloaded file into `Account_Setup_and_Data_Load_xxxxx.csv`

7. Remove the unwanted records

8. Add or update as per your requirement. 

9. Click on `Manage > Upload files` to upload the file.

The file get processed and the Accounts and data gets created.

### 3.3 Bulk Creation and Scheduling of Data Capture Issues

Envizi provides Data Capture Issues as a way to request manual data capture for accounts.

For each data capture activity, users will be notified by e-mail. 
Clicking on the `View Issue` button in the e-mail brings up a browser window with details of this particular data capture item. 
The user can update the item.
Clicking on the `Capture Data` button brings up the survey to complete.

## 4 Reports

There are 4 types of reports available in Envizi.
- Dashboards
- Power Reports – PowerBI Standard Content
- Extract Reports
- Envizi API
	
## 4.1 Dashboards

Dashboards are interactive pages that allow the reporting and display of data in a visual format.

Dashboards are available at all levels generally where there is a Summary page:
- Organizational 
- Group 
- Location
- Account
- Meter

<img src="images/100-dashboard-1.png">

Several controls are available in Dashboard.

- Compare With current period with other periods.
- View As specifies the Unit of measure for the data in the dashboard. 
- Time slider indicates the current period chosen to display.
- The filter funnel activates the filtering options available: Groups, Measures, Regions, Locations.
- Actions activates the Email dashboard or Schedule a Dashboard options

### 4.2 Power Reports
Envizi PowerReport is supercharged by Microsoft PowerBI. Envizi content powered by PowerReport provides a range of visual dashboards to support reporting.

Some of the standard and configurable reports are listed here.

#### Standard Content
- Sustainability (Executive Report)
- Sustainability (Portfolio Performance)
- Account Data Health Check 

#### Configurable Content
- Market-based Emissions
- CDP Climate Report
- Scope 3 Emissions

<img src="images/100-power-report.png">

### 4.3 Extracting reports

IBM Envizi reports allow users to specify a range of selection criteria to view the data in screen and download and to send the report in mail.

Extracting reports provides the following options.
- Choose from various delivery methods (screen, email)
- Choose Groups, locations, Regions, Utilities, report time period/end date
- Choosing `Create Report and E-mail it now` in CSV, PDF, XLSX format
- Choosing `Schedule Report and E-mail it later` also adds the Daily, Weekly, ...etc. schedule.

Click Submit to run the report based on the selected parameters.
<img src="images/100-extract-report-2.png">

### 4.4 API

The Envizi API promotes sharing of data from the Envizi platform and allows users to access and retrieve data from Envizi directly through to compatible third-party software, such as Microsoft Excel, Tableau or Power BI, without the need to log in to Envizi's main user interface. 

- Envizi API is an add-on feature in freeing up the data within Envizi
- Saves time and streamlines reporting and data analytics needs
- Extract multiple data sets at once
- Reports maintain data connectivity & can be refreshed by a user at anytime
- Combine these data sets to create a single reporting output 
- Envizi can integrate with your organization’s 3rd party reporting tools

Refer the documentation.

Use APIs to expose Envizi data to external systems
https://developer.ibm.com/articles/use-apis-to-expose-envizi-data-for-external-systems/

https://knowledgebase.envizi.com/home/envizi-api-overview
 

## 5 Disclosures

During the ESG reporting season, sustainability manager manages multiple ESG disclosure projects concurrently. The volume of data that needs to be complied and reviewed from multiple teams and stakeholders across the business is immense. And the stakes are high: reports need to be financial grade, need to be fully auditable, and the VP of Sustainability needs to sign off before disclosures are published.

In Envizi, Sustainability manager can efficiently organize the people, processes, responses and supporting data required to respond to ESG disclosures. 

Through pre-configured templates and reports, as well as the ability to create custom disclosures, Envizi supports streamlining disclosures to a number of different frameworks.

### 5.1 Sustainability Reporting Manager (SRM)

The Envizi Sustainability Reporting Manager is a tool that pulls together Envizi's quantitative data, attachments, web links, and response methodologies to facilitate the management of ESG data and the formulation of final responses.

The SRM offers up-to-date guidance on best practices to facilitate the completion of responses as mandated by ESG frameworks.

The SRM tool encompasses a wide range of ESG Frameworks, including `TCFD, SASB, GRI, SFDR, UN SDGs, INREV, EPRA, SEC Climate Proposal, EU Taxonomy, PRI, and BRSR`.

<img src="images/110-srm.png">

### 5.2 GRESB and CDP

Though Envizi supports most widely used frameworks comprehensively, there may be certain frameworks that are not included. In such instances, Envizi has developed alternative tools and reports to meet the requirements of specific frameworks, as is the case with `GRESB` and `CDP` at present.
 
<img src="images/111-cdp.png">


## 6 De-Carbonization

Envizi has several modules and tools to help the organziations decarbonization strategy. 

### 6.1 Target setting and Tracking

Organizations may need to track and report their actual emissions against targets over time.

Envizi helps to capture and track sustainability performance targets at any level of your organization with the comprehensive target setting and tracking tool.

Capture and track targets can be done at different levels in the organization.
Multiple types of targets, such as energy, cost, emissions or intensity can be set.
Intuitive dashboards and reports to compare performance against targets are available.

This tool helps to track performance more accurately and access results when you need them and make more informed decisions.
Also it improve the accountability for results at different levels of your organization and engage your people in sustainability performance.

<img src="images/200-target-setting-rate-analysis.png">

### 6.2 Building Ratings + Benchmarks

This tool helps to capture building attribute and utility data, calculate ratings, and benchmark and track building performance in one place.

This helps the organization to build robust way of reporting to external ratings frameworks such as GRESB, ENERGY STAR and NABERS.

<img src="images/250-energy-star.png">

### 6.3 Sustainability Program Tracking

Organizations who are planning or implementing a broad range of sustainability programs as part of their overall decarbonization strategy.

This tools helps the organization’s sustainability programs in a consistent and transparent manner to track progress, verify results and optimize investment decisions.

It can capture and report all sustainability project data in a central system including costs, savings estimates, project timelines, baseline data and more.

<img src="images/210-programs-1.png">

<img src="images/210-programs-2.png">


### 6.4 Utility Bill Analytics

Organizations with energy-intensive facilities which have a need to reduce utility cost, consumption, and emissions.

Utility billing data is Leveraged inside a powerful analytics engine to analyze and control energy cost and consumption, identify anomalies, and inform decision making for energy efficiency.

Envizi offers both standard and customizable connectors designed for automating the capture of utility bill data, encompassing both total cost and consumption metrics. 
It provides an extensive library of emissions factors specific to various utilities. 
Moreover, it delivers comprehensive utility performance analysis and benchmarking through interactive dashboards.

<img src="images/221-utility-bill.png">

### 6.5 Interval Meter Analytics

This tool automates the capture of high-resolution meter data and leverage sophisticated analytics and workflow tools, so your organization can drive efficiency and decarbonize across facilities.

This tool contains the following features.
- Rules-based anomaly detection.
- Integrated issue tracking and workflow tools.
- Energy intensity benchmarking tools.

This tool helps to 
- Minimize energy waste.
- Identify more savings opportunities.
- Drive higher efficiency and accelerate decarbonization.

<img src="images/240-interval-utility-performance-management.png">

### Conclusion

This article should have provided an overview about IBM Envizi ESG Suite. Stay tuned for more articles and tutorials covering various topics related to IBM Envizi ESG Suite, as listed below
- Data Management
- ESG Reporting 
- Reporting Framework and Disclosures( SRM)
- Envizi Implementation Strategy such as Emission Factor and Scope 3 handling
- Envizi Integration with external system for Decarbonization 
