# Spatial Data Science

## Course Description
This is the first of a two-course series focused on teaching intermediate skills in spatial data science with emphasis on the Esri ecosystem of geospatial technologies. Students will gain the baseline skills required to build end-to-end data integration pipelines and perform reproducible deterministic spatial analyses. By the end of the course, students will be able to build geospatial workflows and data systems that can address intermediate-level spatial analysis problems.

## Learning Objectives
By the end of this course, students will be able to:
1. Work across the Esri ecosystem with ArcPro, Python, Jupyter Notebooks, and
supporting open source software tools
2. Create and edit data types including vector, raster, tabular, geojson, spacetime
cubes, TINs, terrain, and networks
3. Perform intermediate deterministic spatial analysis on multiple data types
4. Perform route optimization and solve spatial allocation problems optimally
5. Describe the spatial computing algorithms that underlie Esri toolsets
6. Create spatial data science documentation and workflows at a professional-level


## Student Resources

- [2022 Syllabus](https://docs.google.com/document/d/1imnVS4QfQwgs8pTZEKjKABCTn8jYp0Yq/edit?usp=sharing&ouid=117926763410213500553&rtpof=true&sd=true)
- [How People Learn](https://docs.google.com/presentation/d/1b6uqHuiguISJPoROvoqOs9dAFAWZYbvMM5lTeO9655o/edit#slide=id.gaf8ebdd7e6_0_76)
- [Lab Report Template](https://docs.google.com/document/d/1gOGBtTe3dQzrXCEMl644QIVdJgMp8ahN/edit)


#### Weekly Activities
- [Sign up Weekly Student Note Taker](https://docs.google.com/spreadsheets/d/1gZBnFBbjkb3ryIFFotg0zilk9sXMZDIjLa--vnBuaUA/edit#gid=2014120666)
- [Example of Notes](https://docs.google.com/document/d/1OpdmrQNGFvg8OnD--i64asvWsNqwl6XiDkn72cUgIlM/edit)
- [Sign up for Inspiration Presentation](https://docs.google.com/spreadsheets/d/1UBUII60QZ9UxZowIRpkKireNtQYl2NHcw70HT7dND6A/edit#gid=750114212)
- [Example Inspiration Presentation](https://docs.google.com/presentation/d/1AmKitoWbCqK3ZeWPFVe1dm0KkKqUaknvkp1MQErbM9g/edit#slide=id.p)

#### Final Projects
- [Project Overview](https://docs.google.com/document/d/1Ipqnq78cdC5e94BoTvaD6ZCK6RsoPNbp/edit)
- [Final Project Sign up](https://docs.google.com/spreadsheets/d/1InjQSVN8neXKewZ0TawpBBjvzDhrMeOr/edit#gid=1892231489)


# Week 1
- Slides: [Introduction and Overview](https://docs.google.com/presentation/d/1Ih2Zsf4nfYDunFsd07ffMhLvQ0tVVs7t/edit#slide=id.p1)
- [Lab 0](https://docs.google.com/document/d/1Iz9zoDyZu6bNrij5YiwXLlFaJvFuWhzR/edit#heading=h.gjdgxs)
- [Lab 0 ESRI Learning Plan](https://www.esri.com/training/my-learning-plans/)



# Week 2: Foundations
- Slides: [Representation, Abstractions, and Interfaces](https://docs.google.com/presentation/d/1GiCiLoNf9TsXgQA7K69pPdMkA_OTEUEy/edit?usp=sharing&ouid=117926763410213500553&rtpof=true&sd=true)
- Continue working on Lab 0, Prospectus, and Inspiration Presentations

### Optional Reading:

#### Strongly recommend reviewing ESRI's overview of ArcPy classes (e.g. abstractions and interfaces)
> ArcPy provides a number of classes to better support workflows using Python. In addition to the classes listed in this topic, additional classes can be found in other ArcPy modules, including ...

From [An Overview of ArcPy Classes](https://pro.arcgis.com/en/pro-app/latest/arcpy/classes/alphabetical-list-of-arcpy-classes.htm)


#### Get deeper into the computer science view of abstractions and representation:

> Models capture phenomena—of the world or of the imagination—in such a way that a general-purpose computer can emulate, simulate, or create the phenomena. But the models are usually not obvious. The real world is complex and nonlinear, there’s too much detail to deal with, and relationships among the details are often hidden. Computer scientists deal with this problem by careful, deliberate creation of abstractions that express the models. These abstractions are represented symbolically, in notations appropriate to the phenomena. The design of languages for these models and for analyzing, processing, and executing them is a core activity of computer science.

From [National Research Council (2004). 4 Abstraction, Representation, and Notation. in Computer Science: Reflections on the Field, Reflections from the Field. Washington, DC: The National Academies Press. doi: 10.17226/11106.](https://nap.nationalacademies.org/read/11106/chapter/6)


#### Get deeper into how these questions of abstraction and representation are tied to philosophical underpinnings in geography and spatial science:

> The ongoing debate in GIS regarding the relative merits of vector versus raster representations of spatial information is usually couched in technical terms. Yet the technical question of the most appropriate data structure begs the philosophical question of the most appropriate conceptualization of geographic space. The paper confronts this latter question in the context of the opposition between the "object" and "field" views of space. I suggest that GIS can turn a rather dry debate into a source of insights regarding the nature of its subject matter by learning from how people actually experience and deal with the geographic world. Human cognition indeed appears to make use of both the object and field views, but at different geographic scales, and for different purposes. These observations suggest a list of desiderata for the next round of thinking about spatial representation in GIS.

Abstract from [Couclelis, H. (1992). People manipulate objects (but cultivate fields): Beyond the raster-vector debate in GIS. In: Frank, A.U., Campari, I., Formentini, U. (eds) Theories and Methods of Spatio-Temporal Reasoning in Geographic Space. Lecture Notes in Computer Science, vol 639. Springer, Berlin, Heidelberg. https://doi.org/10.1007/3-540-55966-3_3](http://www.dpi.inpe.br/gilberto/references/couclelis_1992_objects_fields.pdf)
