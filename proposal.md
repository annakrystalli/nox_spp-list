# nox_spp-list
NERC grant application fro project: 
### **Assessing the efficacy and costs of noxious species lists, a common policy tool in invasive species management.**

***
<br>

## RSE DMP (data management plan) proposal:

Planned as a collaboration betweeen RSE and the Library. The plan is to support the project from the beginning with research data management and guide the collation of the various datasets to enable final compilation into a usable data product. This data product will consist of a versioned database with a doi, which will be live and queryable for the duration of the project. In addition a light software wrapper will be designed and developed to facilitate easy and efficient querying of the database for researchers without a need for database querying languages. Finally, at the end of the project, the database and the full functionality developed around it will be packaged for archival and local use. 

This field is generally a fast evolving ecosystem, both in terms of power of avaialable technologies, the capabilities and availability of archiving infrastrucuture and open data requirements. So the technologies used will be the most up to date and may not refelect current apporaches, include potentially some propsed here. The project itself will involve some experimentation and so the 6 months proposed & costed pertain to a certain level of innovation, not simply a standard out of the box service. So in addition to the database, we envisage our involvement will also push forward in the field of making data product FAIR.

**Estimated time: 6 months**

**Estimated cost:**

<br>

***

# ACTION PLAN

## 1. CONSULT AND DESIGN DATABASE SCHEMA
 It is important for efficiency of the project that our involvement in the implementation of the DMP begin right at the beginning and continue throughout. In this way we can get a good understanding of function and pressure points in:
 - the compilation of data 
 - alignment of data
 - intended use of data by researchers.

## 2. BUILD DATABASE AND HOST ONLINE
  Once the data model has been agreed, we will be build the first version of the database and provide scripts and support for the research team to be able to add data. If there is enough time, updating the database could also be included in the software package. See below 
  
  
  
## 3. DEVELOP SOFTWARE TO FACILITATE EASY ACCESS TO DATA

The primary objective of the access software stage is to facilitate easy user querying according to their most likely query needs. It will most likely take the form of a lighweight r package built around an API, will most likley take the form of a lightweight R package and follow best API and database access development principles of developing from the **outside in**. Again, this underpins the necessity for RSE to be involved from the begining, to be able to working on the user-interface first in order to guide the data model. It also involves iterating the design of the API in response to feedback by the research team through validation and testing stages to ensure both the API and software are fit for purpose.

The API will mean that the data pbase can be used as a service to other data apps while the R package software will allow easy access to users, optimising both machine and human access to the data.

There is also the potential to submit the package for rOpenSci review.

## 4. DEVELOP ARCHIVE VERSION
  Once the project ends, there will be no funds to maintain a live instance of the database.
   - To ensure long-term sustainability, we will archive the data in a permanent repository such as Zenodo or Orda
   - Software will be developed that will allow automatic construction of a live database for others to host, either locally or online
   
## 5. DEVELOP DOCUMENTATION
  - Version controlled fully documented record of development
  - Documentation on access and use of live database
  - Documentation on access and use of archived database

<br>








