# nox_spp-list
NERC grant application fro project: 

### **Assessing the efficacy and costs of noxious species lists, a common policy tool in invasive species management.**

***
<br>

![](https://imgs.xkcd.com/comics/digital_resource_lifespan.png)

## Research Software Engineering (RSE) proposal:

Good data management techniques are a fundamental component of good scientific practice. In this project, a large number of diverse data sources are required to be combined and interogated. The most ideal way to manage access to such a complex stucture is through a database. This approach will preserve the data linkage and interoperability developed during the project and retain smooth and easy access to a complex data product.

Planned as a collaboration betweeen RSE and the Library. The plan is to support the project from the beginning with research data management and guide the collation of the various datasets to enable final compilation into a usable data product. This data product will consist of a versioned database with a DOI, which will be live and queryable for the duration of the project. In addition a light software wrapper will be designed and developed to facilitate easy and efficient querying of the database for researchers without a need for database querying languages. Finally, at the end of the project, the database and the full functionality developed around it will be packaged for archival. Documentation will be developed to enable anyone with the requisite compute resources to recreate the live service.

This field is generally a fast evolving ecosystem, both in terms of power of avaialable technologies, the capabilities and availability of archiving infrastrucuture and open data requirements. As such, the technologies used will be the most up to date and may not refelect current apporaches, include potentially some propsed here. The project itself will involve some experimentation and so the 6 months proposed & costed pertain to a certain level of innovation, not simply a standard out of the box service. In addition to the database, we envisage our involvement will also push forward in the field of making a data product [FAIR](https://www.force11.org/group/fairgroup/fairprinciples). We will also happily work with specialists at the appropriate NERC Data Centre.

Going to this effort of RDM support the integrity, transparency and openness of the research the data will support. It will also ensure the continuing availability of the fruits of this important work in the form of high data quality and integrity while an emphasis on accessibility tools in a variety of ways will allow for multiple and diverse downstream use cases for a variety of stakeholders, including research, teaching, and wider exploitation for the public good, by individuals, government, business and other organisations. This enables the maximum value to be gained from the investment of public funds made in their compilation and provides the widest possible opportunities for re-use of these data.



**Estimated time: 6 months spread over the duration of the project**

**Estimated cost: Approx £36,000 (based on a daily rate of £274)**

<br>

***

# ACTION PLAN

### 1. CONSULT AND DESIGN DATABASE SCHEMA
 It is important for efficiency of the project that our involvement in the implementation of the DMP and design of the deta model begin right at the beginning and continue throughout. In this way we can get a good understanding of function and pressure points in:
 - the compilation of data 
 - alignment of data
 - intended use of data by researchers.
 
 The data model will ensure that all pertinent metadata are stored either within or with the database and full traceability and record of datapoint provenance is maintained. As such, source transparency will be mantained and attribution preserved. Metadata will include detailed information about how the data were arrived at, i.e. metadata, covering methods of collection, processing, calibration and quality control.

### 2. BUILD DATABASE AND HOST ONLINE

  Once the data model has been agreed, we will be build the first version of the database and provide scripts and support for the research team to be able to add data. If there is enough time, updating the database could also be included in the software package. See below. Additionally we will work with NERC data centres to get the database assigned with a formal DOI and keep it updated to reflect versioning of the data. Appropriate licenses will also be prepared.
  
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



NOTE: NERC offer sevices for both helping reseraches with DMPs and subsequent data curation as well as for responding to complex data requests. Caan we make the case that that this we take the pressure off all this aspects with respect to this project?




