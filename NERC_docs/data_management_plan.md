Data Management Plan

This is where the fine detail can go. Which DB, hosting, R packages, etc...

***

# DATA MANAGEMENT PLAN

***N.B. - Feels like there should be a pointer to the data collection plan outlined in the proposal here?**

### 1. CONSULT AND DESIGN DATABASE SCHEMA
 It is important for efficiency of the project that RSE and Library RDM involvement in the implementation of the DMP and design of the deta model begin right at the beginning and continue throughout. In this way we can get a good understanding of function and pressure points in:
 - the compilation of data 
 - alignment of data
 - intended use of data by researchers.
 
 The data model will ensure that all pertinent metadata are stored either within or with the database and full traceability and record of datapoint provenance is maintained. As such, source transparency will be mantained and attribution preserved. Metadata will include detailed information about how the data were arrived at, i.e. metadata, covering methods of collection, processing, calibration and quality control.

### 2. BUILD DATABASE AND HOST ONLINE

  Once the data model has been agreed, we will build the first version of the database and provide scripts and support for the research team to be able to add data. Additionally we will work with the NERC Environmental Information Data Centre (EIDC) to get the database assigned with a formal DOI and keep it updated to reflect versioning of the data. Appropriate licenses will also be prepared **plant atlas specifically**!.
  
### 3. DEVELOP SOFTWARE TO FACILITATE EASY ACCESS TO DATA

The primary objective of the access software stage is to facilitate easy user querying according to their most likely query needs. It will take the form of a lighweight R package built around an API and follow best **outside in** API and database access development principles. Again, this underpins the necessity for RSE to be involved from the beginning, to be able to work on the user-interface first in order to guide the data model. It also involves iterating the design of the API in response to feedback by the research team through validation and testing stages to ensure both the API and software are fit for purpose.

The API will mean that the database can be used as a service to other data apps while the R package software will allow easy access to users, optimising both machine and human access to the data.

There is also the potential to submit the package for rOpenSci review.

### 4. DEVELOP ARCHIVE VERSION
  Once the project ends, there will be no funds to maintain a live instance of the database.
   - To ensure long-term sustainability, we will archive the data in a NERC data center.
   - Software will be developed that will allow automatic construction of a live database for others to host, either locally or online
   
### 5. DEVELOP DOCUMENTATION
Version controlled fully documented record of development of the database and software. This will ensure transparency and reproducibility of all project outputs. As well as the data and software products, full web-hosted documentation will be provided on:
  - Access and use of live database
  - Access and use of the API
  - Deployment and use of archived database
