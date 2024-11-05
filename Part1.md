# Applied Spatial Data Science - Part 1

## Course Description
This is the first of a two-course series focused on teaching intermediate skills in spatial data science with emphasis on the Esri ecosystem of geospatial technologies. Students will gain the baseline skills required to build end-to-end data integration pipelines and perform reproducible deterministic spatial analyses. By the end of the course, students will be able to build geospatial workflows and data systems that can address intermediate-level spatial analysis problems.

## Learning Objectives
By the end of this course, students will be able to:
1. Work across the Esri ecosystem awith ArcPro, Python, Jupyter Notebooks, and
supporting open source software tools
2. Create and edit data types including vector, raster, tabular, geojson, spacetime
cubes, TINs, terrain, and networks
3. Perform intermediate deterministic spatial analysis on multiple data types
4. Perform route optimization and solve spatial allocation problems optimally
5. Describe the spatial computing algorithms that underlie Esri toolsets
6. Create spatial data science documentation and workflows at a professional-level


## Student Resources

- [Syllabus](https://docs.google.com/document/d/1imnVS4QfQwgs8pTZEKjKABCTn8jYp0Yq/edit?usp=sharing&ouid=117926763410213500553&rtpof=true&sd=true)
- [How People Learn](https://docs.google.com/presentation/d/1b6uqHuiguISJPoROvoqOs9dAFAWZYbvMM5lTeO9655o/edit#slide=id.gaf8ebdd7e6_0_76)
- [Lab Report Template](https://docs.google.com/document/d/1gOGBtTe3dQzrXCEMl644QIVdJgMp8ahN/edit)


#### Weekly Activities
- [Sign up Weekly Student Note Taker](https://docs.google.com/spreadsheets/d/1gZBnFBbjkb3ryIFFotg0zilk9sXMZDIjLa--vnBuaUA/edit?usp=sharing)
- [Example of Notes](https://docs.google.com/document/d/1OpdmrQNGFvg8OnD--i64asvWsNqwl6XiDkn72cUgIlM/edit)
- [Sign up for Inspiration Presentation](https://docs.google.com/spreadsheets/d/1UBUII60QZ9UxZowIRpkKireNtQYl2NHcw70HT7dND6A/edit?usp=sharing)
- [Example Inspiration Presentation](https://docs.google.com/presentation/d/1AmKitoWbCqK3ZeWPFVe1dm0KkKqUaknvkp1MQErbM9g/edit#slide=id.p)

#### Final Projects
- [Project Overview](https://docs.google.com/document/d/1Ipqnq78cdC5e94BoTvaD6ZCK6RsoPNbp/edit)
- [Final Project Sign up](https://docs.google.com/spreadsheets/d/1InjQSVN8neXKewZ0TawpBBjvzDhrMeOr/edit?usp=sharing&ouid=117926763410213500553&rtpof=true&sd=true)
- [Peer Review Sign up](https://docs.google.com/spreadsheets/d/1EtpaXWx4cc9lzecs0SdcBKrmeCi3Qas0yZrrOhFM2ys/edit?usp=sharing)

# --- Introduction ---
# Week 1
- Slides: [Introduction and Overview](https://docs.google.com/presentation/d/1Ih2Zsf4nfYDunFsd07ffMhLvQ0tVVs7t/edit#slide=id.p1)
- [Lab 0](https://docs.google.com/document/d/1Iz9zoDyZu6bNrij5YiwXLlFaJvFuWhzR/edit#heading=h.gjdgxs)
- [Lab 0 ESRI Learning Plan](https://www.esri.com/training/my-dashboard/)

# --- Foundations: Modeling Space and Place ---
# Week 2
- Slides: [Representation, Abstractions, and Interfaces](https://docs.google.com/presentation/d/1GiCiLoNf9TsXgQA7K69pPdMkA_OTEUEy/edit?usp=sharing&ouid=117926763410213500553&rtpof=true&sd=true)
- [Lab 1](https://docs.google.com/document/d/1hREy9BSfYNHWedRdvJpk8U8ZD3zGs8cqlgOKioYMsZM/edit#heading=h.haql5ac3lg7k)
- Esri Data Types Shared [Sheet](https://docs.google.com/spreadsheets/d/1AYm7LLa80W_o0oOe7K1MvqhXcI5BeYo_a36TvkCwZkY/edit#gid=0)

### Optional Reading:

#### Strongly recommend reviewing ESRI's overview of ArcPy classes (e.g. abstractions and interfaces)
> ArcPy provides a number of classes to better support workflows using Python. In addition to the classes listed in this topic, additional classes can be found in other ArcPy modules, including ...

From [An Overview of ArcPy Classes](https://pro.arcgis.com/en/pro-app/latest/arcpy/classes/alphabetical-list-of-arcpy-classes.htm)


#### Get deeper into the computer science view of abstractions and representation:

> Models capture phenomena—of the world or of the imagination—in such a way that a general-purpose computer can emulate, simulate, or create the phenomena. But the models are usually not obvious. The real world is complex and nonlinear, there’s too much detail to deal with, and relationships among the details are often hidden. Computer scientists deal with this problem by careful, deliberate creation of abstractions that express the models. These abstractions are represented symbolically, in notations appropriate to the phenomena. The design of languages for these models and for analyzing, processing, and executing them is a core activity of computer science.

From [National Research Council (2004). 4 Abstraction, Representation, and Notation. in Computer Science: Reflections on the Field, Reflections from the Field. Washington, DC: The National Academies Press. doi: 10.17226/11106.](https://nap.nationalacademies.org/read/11106/chapter/6)


#### Get deeper into how these questions of abstraction and representation are tied to philosophical underpinnings of geography and spatial science:

> The ongoing debate in GIS regarding the relative merits of vector versus raster representations of spatial information is usually couched in technical terms. Yet the technical question of the most appropriate data structure begs the philosophical question of the most appropriate conceptualization of geographic space. The paper confronts this latter question in the context of the opposition between the "object" and "field" views of space. I suggest that GIS can turn a rather dry debate into a source of insights regarding the nature of its subject matter by learning from how people actually experience and deal with the geographic world. Human cognition indeed appears to make use of both the object and field views, but at different geographic scales, and for different purposes. These observations suggest a list of desiderata for the next round of thinking about spatial representation in GIS.

Abstract from [Couclelis, H. (1992). People manipulate objects (but cultivate fields): Beyond the raster-vector debate in GIS. In: Frank, A.U., Campari, I., Formentini, U. (eds) Theories and Methods of Spatio-Temporal Reasoning in Geographic Space. Lecture Notes in Computer Science, vol 639. Springer, Berlin, Heidelberg. https://doi.org/10.1007/3-540-55966-3_3](http://www.dpi.inpe.br/gilberto/references/couclelis_1992_objects_fields.pdf)

# Week 3
- Slides: [Data Pipelining, Interoperability, and Wrangling](https://docs.google.com/presentation/d/1H3wKZnttw1WZXGM_PXnwKRwHGBnRn6A-/edit#slide=id.p1)
- Continue Lab 1

### Optional Reading:

#### Learn about how ArcPy's geometry classes relate to one another
> Geometry objects define a spatial location and an associated geometric shape. In many geoprocessing workflows, you may need to run a specific operation using coordinate and geometry information but don't...

From [ArcPy Classes: Geometry](https://pro.arcgis.com/en/pro-app/2.8/arcpy/classes/geometry.htm)

#### Get deeper in the role that commandline tools can play in your spatial data science workflows
> Today, data scientists can choose from an overwhelming collection of exciting technologies and programming languages. Python, R, Julia, and Apache Spark are but a few examples. You may already have experience in one or more of these. If so, then why should you still care about the command line for doing data science? What does the command line have to offer that these other technologies and programming languages do not?

From [Data Science at the Command Line](https://datascienceatthecommandline.com/2e/chapter-1-introduction.html)

#### Pipelining often involves building data-intensive software systems. Learn more from this book
> [W]e need to build applications that are reliable, scalable and maintainable in the long run. We need to understand the range of available tools and their trade-offs. For that, we have to dig deeper than buzzwords.

From [Designing Data-Intensive Applications](https://dataintensive.net/)

# Week 4
- Slides: [Data Capture, Storage, Quality Assurance and Control](https://docs.google.com/presentation/d/1nwUkBhRsvEkGVFkaU9e6DdUiAe1CAcD2/edit#slide=id.gf4c686e7e1_0_90)
- Continue with Lab 1; quiz next week
- [Folder for QAQC Matrices and Diagrams Activity](https://drive.google.com/drive/folders/1WuKEQ50OpBrLnrIEhjUnWVb4ViQz28I1)

### Optional Reading
#### Continuous streams of data present unique challenges for spatial and temporal quality assurance and control checks. The instrumentation community has substantial experience in managing such data and illustrates the socio-technical nature of QAQC programs. Learn more from this paper...
> Sensor networks are revolutionizing environmental monitoring by producing massive quantities of data that are being made publically available in near real time. These data streams pose a challenge for ecologists because traditional approaches to quality assurance and quality control are no longer practical when confronted with the size of these data sets and the demands of real-time processing. Automated methods for rapidly identifying and (ideally) correcting problematic data are essential. However, advances in sensor hardware have outpaced those in software, creating a need for tools to implement automated quality assurance and quality control procedures, produce graphical and statistical summaries for review, and track the provenance of the data. Use of automated tools would enhance data integrity and reliability and would reduce delays in releasing data products. Development of community-wide standards for quality assurance and quality control would instill confidence in sensor data and would improve interoperability across environmental sensor networks.

From [John L. Campbell, Lindsey E. Rustad, John H. Porter, Jeffrey R. Taylor, Ethan W. Dereszynski, James B. Shanley, Corinna Gries, Donald L. Henshaw, Mary E. Martin, Wade M. Sheldon, Emery R. Boose, Quantity is Nothing without Quality: Automated QA/QC for Streaming Environmental Sensor Data, BioScience, Volume 63, Issue 7, July 2013, Pages 574–585, https://doi.org/10.1525/bio.2013.63.7.10](https://academic.oup.com/bioscience/article/63/7/574/289294)

#### Data quality is both a consideration of accuracy of measures compared to a standard measure as well as how well it fits a data consumers' expectations.
>Poor data quality (DQ) can have substantial social and economic impacts. Although firms are improving data quality with practical approaches and tools, their improvement efforts tend to focus narrowly on accuracy. We believe that data consumers have a much broader data quality conceptualization than IS professionals realize. The purpose of this paper is to develop a framework that captures the aspects of data quality that are important to data consumers.

From [Wang, R. Y., & Strong, D. M. (1996). Beyond accuracy: What data quality means to data consumers. Journal of management information systems, 12(4), 5-33.](http://mitiq.mit.edu/Documents/Publications/TDQMpub/14_Beyond_Accuracy.pdf)

#### Cross-location data collection increases the usefulness and cost effectiveness of data collection, but comes with challenges. This paper describes the process that the National Ecological Observation Network (NEON) has used to improve sensor data quality, and serves as a good example of what it takes to acheive high quality data.
> Data quality is the degree to which data are fit for use by data consumers (Wang & Strong, 1996). Standardization has long been recognized as essential for meeting quality requirements of distributed environmental measurements. Beginning in the 18th century, meteorological societies developed standardized, calibrated instrumentation and regulated observation procedures (Kington, 1974). Organizations like the World Meteorological Organization (WMO; established 1950) carry this work forward today, publishing technical standards and guidelines for generating high-quality, comparable sensor measurements (e.g. WMO, 2008). Since the late 1900s, cross-disciplinary networks such as FLUXNET (Baldocchi et al., 2001) and the Long Term Ecological Research program (LTER; Hobbie et al., 2003) have harnessed standardization to share and synthesize data collected at independently run stations to understand large-scale and long-term ecosystem dynamics. Individual site investigators coordinate on measured and derived quantities, general processing steps and data formats. NEON builds off of these historical efforts, incorporating standards and guidelines from relevant scientific communities into its design and operational requirements and additionally unifying sensors and measurement infrastructure, collection and maintenance protocols and processing algorithms.

From [Sturtevant, C., DeRego, E., Metzger, S., Ayres, E., Allen, D., Burlingame, T., ... & SanClements, M. (2022). A process approach to quality management doubles NEON sensor data quality. Methods in Ecology and Evolution, 13(9), 1849-1865.](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.13943)


# Week 5
- [Quiz](https://canvas.umn.edu/courses/456385/assignments/4151667)
- [Lab 2](https://docs.google.com/document/d/1HqW_6GluS0Y2s7KIE-ehvBiiB8W8iQCj/edit?usp=sharing&ouid=117926763410213500553&rtpof=true&sd=true)

# Week 6
- [Slides](https://docs.google.com/presentation/d/1J9bPSbyoucbMCtLtm4rocwOWP1DhGliI/edit#slide=id.p3)
- Continue with Lab 2

### Optional Reading
#### Routing and optimal paths are foundational to our field, and they're built on top of cost surfaces. The techniques to arrive at a cost surface are highly similar to those to perform a suitability analysis.
> Suppose you needed to locate the best route for a proposed highway, or pipeline or electric transmission line. What factors ought to be considered? How would the criteria be evaluated?

From [Beyond Mapping III: Topic 19: Routing and Optimal Paths](http://www.innovativegis.com/basis/MapAnalysis/Topic19/Topic19.pdf)

# Week 7
- [Slides](https://docs.google.com/presentation/d/1I8pVck9UQC66UQCKP12Cxr2cj7W61SWB/edit#slide=id.p8)
- Continue with Lab 2
- Sign up for [peer reviews](https://docs.google.com/spreadsheets/d/1EtpaXWx4cc9lzecs0SdcBKrmeCi3Qas0yZrrOhFM2ys/edit#gid=0)

# Week 8
- [Slides](https://docs.google.com/presentation/d/1W6m_ssvQ652KEZUAhdC7v21GEtwo85aj/edit?usp=drive_web&ouid=117926763410213500553&rtpof=true)
- [Toy Model](https://docs.google.com/spreadsheets/d/1yqlhxlGmtuCTMAmne0jzacP6IH3I92GB/edit?usp=sharing&ouid=117926763410213500553&rtpof=true&sd=true) to download and use in excel

### Optional Reading
#### Model Analysis is an important part of characterizing what your model can and cannot do well. Learn more...
> Modeling, like computing and statistics, should produce insights, not merely numbers... When we consider model validation, we are interested in the quality of the model. This is a more difficult problem than one might suppose.

From Haefner, J. W. (2005). Modeling biological systems. Springer.

# Week 9
- Quiz. See Canvas.

# Week 10
- [Slides](https://docs.google.com/presentation/d/1PrXjw7pOE1jqYmv-lXur7kJ0EOjEf0R8/edit#slide=id.p2)
- [Lab](https://docs.google.com/document/d/1Pt163DzQbImnV4e6nBMm2UKs17s1BGFC/edit)
- [Notebook Cross Validation Toy Problem](https://github.com/runck014/interpolation_cross_validation)
