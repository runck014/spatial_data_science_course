# Spatial Data Science

This repo holds a two course sequence for spatial data science. 

- **Part 1** focuses on automated workflows and data integration both locally and in cloud-based workflows for online results storage and delivery.

- **Part 2** focuses on deterministic and stochastic spatial analysis and simulation with an emphasis on architecting distributed geospatial systems.

## Notes on the Updated Version
Over the past four years, I've had the pleasure of hiring and employing many of the students who have taken this course sequence. I have hired my past students always in the context of applied R&D in spatial data science. This means that I've been on all sides of the education process - from first introduction to learning and then on the backend in skill use. This process has shown me repeatedly areas where I have not done the job I need to as an instructor to develop students who are capable of executing complex spatial data science projects in the wild. My goal with this refactor is to address my prior curriculum's shortcomings. Some changes will unfortunatley make the curriculum worse, but I hope, on net, the changes result in even better trained spatial data scientists.


## Theoretical Components of Spatial Data Science

| Major Concept | Description |
|---------------|-------------|
| Abstract Spatial Data Types | Foundational digital representations; primitives of the field of SDS |
| ASDT Measures | Valid measures within and between ASDTs given different views of space, time, distance, area, etc |
| Mutation Processes of ASDTs | Valid transformations and mutations of ASDTs across spatiotemporal scales - for the purposes of data fusion and harmonization, map interpolation and prediction |
| ASDT Validity and Quality Evaluation | Ensuring parsimony between ASDT, measures, and mutations |


## Engineering for Spatial Data Science

| Major Concept | Description|
|---------------|-------------|
| ASDT Implementation | Different implementation approaches; comparison of implementations of points, lines, polygons, rasters, etc. |
| Spatial model implementation | Different implementation approaches for optimization, interpolation, and prediction; comparison of models in terms of fit and prediction capability |
| Spatial data system flow mapping | Data flow mapping; upstream and downstream |
| Spatial data system architecting | Matching functional and technical specifications; centralized vs distributed, etc. |
| Spatial data system performance evaluation | Analysis of competing algorthmic systems |
| Spatial data system network, storage, and computation performance | How do different implementation combinations affect compute/storage performance? |
| Spatial data system testing and quality assurance | Static and real-time testing and quality assessment; system security |

## Prerequisite Knowledge
| Discipline | Major Concept | Description |
|------------|---------------|-------------|
| Geographic Information Science | Coordinate reference systems | Datums, projections |
| Geographic Information Science | Representation | vector, raster |
| Geographic Information Science | Spatial summarization | Basic spatial thinking and implementation in GIS |
| Geographic Information Science | GI Systems Use | Exposure to open and closed GIS (ArcGIS, QGIS, python-based and OGC stack, arcpy) |
| Cartography | Basic Map Design | Map design process; communication model of mapping, etc |
| Computer Science | Abstraction | Nimble representation of entities and phenomena in objects; object-oriented programming; abstraction of computers |
| Computer Science | Databases | Data modeling; entity-relationship diagram; spatial indexing; extended 9-intersection model; SQL |
| Computer Science | Control structures | loops, if-then, etc |
| Computer Science | Computational complexity | Exposure and practice with Big O; definition of NP-hard; Ch 3 of Rosen 2011 |
| Discrete Math | Logic and proofs | Ch 1 of Rosen 2011 |
| Discrete Math | Sets, functions, sums, matrics | Ch 2 of Rosen 2011 |
| Discrete Math | Graphs | Ch. 10 of Rosen 2011 |
| Discrete Math | Trees | Ch. 11 of Rosen 2011 |
| Statistics | Discrete probability | Ch 7 of Rosen 2011 plus applied probabilistic programming |
| Statistics | Descriptive statistics | Commons in first semester statistics course |
| Statistics | Inferential statistics | distributions, hypothesis testing, linear regression; use of bootstrapping and simulation |
| Scientific Computing | Environment management | package management (conda), version control, containers |
| Scientific Computing | System navigation | file system navigation in commandline (bash; zsh) or GUI; ssh; scp |
| Scientific Computing | Reproducible Code | GitHub and repository structuring; Jupyter notebook; scripting; creating libraries |
| Information Technology | Cloud Computing | Virtual servers, hosted databases, serverless platforms, continuous integration and deployment (AWS, Google, Azure) |
| Information Technology | Enterprise system management | Security and access for data; network management; etc |
