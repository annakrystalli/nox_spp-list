# nox_spp-list
NERC grant application fro project: 

### **Assessing the efficacy and costs of noxious species lists, a common policy tool in invasive species management.**

***
<br>

![](https://imgs.xkcd.com/comics/digital_resource_lifespan.png)

## Research Software Engineering (RSE) proposal:

Planned as a collaboration betweeen RSE and the Library. The plan is to support the project from the beginning with research data management and guide the collation of the various datasets to enable final compilation into a usable data product. This data product will consist of a versioned database with a DOI, which will be live and queryable for the duration of the project. In addition a light software wrapper will be designed and developed to facilitate easy and efficient querying of the database for researchers without a need for database querying languages. Finally, at the end of the project, the database and the full functionality developed around it will be packaged for archival. Documentation will be developed to enable anyone with the requisite compute resources to recreate the live service.

This field is generally a fast evolving ecosystem, both in terms of power of avaialable technologies, the capabilities and availability of archiving infrastrucuture and open data requirements. As such, the technologies used will be the most up to date and may not refelect current apporaches, include potentially some propsed here. The project itself will involve some experimentation and so the 6 months proposed & costed pertain to a certain level of innovation, not simply a standard out of the box service. In addition to the database, we envisage our involvement will also push forward in the field of making a data product [FAIR](https://www.force11.org/group/fairgroup/fairprinciples).

Going to this effort of RDM means the fruits of this important work for both research and policy can be compiled to a high standard of data quality and integrity, accessed in a variety of ways allowing multiple and diverse downstream use cases for a variety of stakeholders.

**Estimated time: 6 months**

**Estimated cost: £50,000**

<br>

***

# ACTION PLAN

### 1. CONSULT AND DESIGN DATABASE SCHEMA
 It is important for efficiency of the project that our involvement in the implementation of the DMP and design of the deta model begin right at the beginning and continue throughout. In this way we can get a good understanding of function and pressure points in:
 - the compilation of data 
 - alignment of data
 - intended use of data by researchers.
 
 The data model will ensure that all pertinent metadata are stored either within or with the database and full traceability and record of datapoint provenance is maintained.

### 2. BUILD DATABASE AND HOST ONLINE
  Once the data model has been agreed, we will be build the first version of the database and provide scripts and support for the research team to be able to add data. If there is enough time, updating the database could also be included in the software package. See below 
  
### 3. DEVELOP SOFTWARE TO FACILITATE EASY ACCESS TO DATA

The primary objective of the access software stage is to facilitate easy user querying according to their most likely query needs. It will most likely take the form of a lighweight R package built around an API and follow best API and database access development principles of developing from the **outside in**. Again, this underpins the necessity for RSE to be involved from the begining, to be able to working on the user-interface first in order to guide the data model. It also involves iterating the design of the API in response to feedback by the research team through validation and testing stages to ensure both the API and software are fit for purpose.

The API will mean that the data pbase can be used as a service to other data apps while the R package software will allow easy access to users, optimising both machine and human access to the data.

There is also the potential to submit the package for rOpenSci review.

### 4. DEVELOP ARCHIVE VERSION
  Once the project ends, there will be no funds to maintain a live instance of the database.
   - To ensure long-term sustainability, we will archive the data in a permanent repository such as Zenodo or Orda
   - Software will be developed that will allow automatic construction of a live database for others to host, either locally or online
   
### 5. DEVELOP DOCUMENTATION
Version controlled fully documented record of development of the database and software. This will ensure transparency and reproducibility of all project outputs. As well as the data and software products, full web-hosted documentation will be provided on:
  - Access and use of live database
  - Access and use of the API
  - Deployment and use of archived database


<br>



OVERALL





