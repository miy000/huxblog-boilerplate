---
layout:     post
title:      "DATA VISUALIZATION"
subtitle:   "A reading report of data visualization"
date:       2017-06-07
author:     "MIYO"
header-img: "img/post-bg-js-version.jpg"
tags:
    - Data visualization
---

## CONTENT

- I.INTRODUCTION
- II.BACKGROUND OF VISUALIZATION
- III.FOUNDATION FRAMEWORK
- IV.GEOGRAPHIC INFORMATION VISUALIZATION
- V.TREE AND NETS DATA VISUALIZATION
- VI.TIME-VARYING DATA VISUALIZATION
- VII.MEDIA DATA VISUALIZATION
- REFERENCES

## I.	Introduction 
Visualization is the graphic presentation of data-portrayals meant to reveal complex information at a glance. However, there are still some problems confusing me. Is data visualization just specialized in big data? Whether visualization contains bar chart, graphic pictures? What are the differences between infographics and visualization? 
After reading some books and documents, I wrote this report to conclude my understanding of data visualization. The book Data visualization written by Wei CHEN helped me establish the framework of visualization as it provides a complete introduction to important topics in visualization. Beautiful visualization, a book that written by more than 20 experts specialized in design, science, statistics and analysis shows us how visualization can be applied into their work and life. It helps me have a further understanding on the practical application of visualization and put forward my ideas. Moreover, I read some paper and conference documents to acquire the latest information of visualization. There are three famous international conference to promote the development of visualization every year. They are IEEE conference on scientific visualization (SciVis), IEEE conference on Information visualization(infoVis), IEEE conference on visual analytics science and technology(VAST).

## II.	Background Of Visualization
**A.	History of data visualization**
Before the 17th century, map is the representative of data visualization in that period. Later in the 17th century, physical measurement became a new and important branch in visualization and statistical graphics became prosperous in 18th and 19th century. In the first half of the 20th century, when we design the visualization we will apply the psychological knowledge into it and visualization have been wide spread in daily life. Moreover, iconology and semiology was put forward by Bertin in 1967 which laid the foundation of visualization so that we can developed the visual display of quantitative information later. Currently, visualization has been a discipline in many university.
**B.	Classification of data visualization**
**1)	Scientific visualization**
One of the modern and well-developed visualization area is scientific visualization, which is widely used in different theoretical and experimental researches. It focuses on 3D real world of physical and chemical phenomena. According to the data can be divided into scalar, vector and tensor, scientific visualization can also be classified into these three parts.
**2)	Information visualization**
Information visualization deals with the abstract and unstructured data, which compared with the scientific visualization, it focuses more on abstract and high dimensional data.
**3)	Visual analytics**
Visual analytics are defined as an analysis of reasoning subject that basic on the visual interface and is associated with multiple areas. In the visualization, it contains infographics, scientific visualization and computer graphics. The analysis of data connect with it contains the acquisition of information, data processing and data mining and in the interaction, visual analytics mix human-computer interaction and cognitive science.
**C.	Visual perception theory**
To study visualization better, we should also equip the knowledge of visual perception theory so that the user can learn our idea easily. Audiences obtain information through visual perception, coding to form cognition and they will obtain the solution during the process of interaction analysis.
The visual perception theory includes psychology, color and visual encoding. User can memory the graphic information better. They will recognize the overall the picture first and later to figure out the partial of the picture. We should take full advantage of color psychology and visual illusion in our design.
Human recognition system will have different understanding and ability of information acquisition with different visual channel. The following picture describe the general situation of expressive force of various kind of visual channel which ranks from top to bottom respectively according to the performance from high to low.

   	the rank of human recognition system
**D.	Neighboring subjects**
As data visualization is a comprehensive subject, it has several neighboring subjects that related with it but still have some differences.
**1)	Infographics design**
Information graphics are visual representation of information and data or knowledge often used to support information, which will strengthen it within a sensitive context. It concentrates on the two-dimensional visual design and lay particular stress on the expression of arts. While data visualization are visual displays of measured quantities by means of the combined use of a coordination system, points, lines, shapes, digits, letter quantified by visual attributes. Data visualization are general, context-free and often times created automatically. They also have several concepts in common. Both of them can be static, animated or interactive. To conclude it, information graphics are used to tell a story or answer a question while data visualization are used to let the user find his own story or answer.
**2)	Dataology**
Dataology contains data governance, data analysis & data mining and data warehouse. Data visualization and data analysis & data mining have the same goal in acquisition of knowledge in the data processing but they use different tools. 

**3)	Visualization of specific field**
Visualization can apply into various areas and help people get the information in a lively and attractive way. In the education field, for example, the educational administration system. Teachers can through the system realize the students’ overall learning status, their scores and major, etc. In the medical field, life science contains lots of knowledge and it is vital for doctors to clarify the data relationship in a short time. Medical visualization can help doctor to grasp of the status of the patient in a short time which is of great significance for the medical treatment.

## III.	Foundation Framework
**A.	Data visualization processing**
Generally speaking, the data visualization process contains data acquisition, data cleaning, data analysis and the last step is data visualization. We divide data visualization into three parts and there are also some differences between them. Scientific visualization will contain the geometric data so that we need to filter them, map and render into the image data. Infographics visualization we need to turn the user’s behavior into data and build the visual structure like website, poster to help user develop their insight through the visualization. Visual data exploration process is characterized through interaction between data, visualizations, models about the data, and the users in order to discover knowledge.
**B.	Elements of visualization**
Visualization elements contains data, chart and their basic pattern. Data for visualization can be divided into three categories: order data, ratio data and category data. Visualization basic pattern includes design their size, color, location, network and time. We need to cooperate with their relationship appropriately. 
**C.	The principle in visual design**
Moreover, we need to follow some principles in visual design, such as the aesthetics rule, interface design and visual metaphor. Aesthetics are not the main goal of visualization, but the outstanding visualization must combine aesthetics with data display. There are plenty of ways to improve the aesthetics of visualization and we can conclude it as concentration, simple and balance. Interface design is necessary in the complicated visualization system. It must explain the data directly and let the user understand and remember our data easily. Visual metaphor is a method that introduce user into a new area by traditional ways. It can use time metaphor or space metaphor to help us explain new concepts better.

## IV.	Geographic Information Visualization
**A.	Geographic information system**
Geographic information system have been widely use in daily life and military affairs. Projection is popular in the geographic visualization and it includes Mercator projection, albers projection and azimuthal projection. When we design the geographic information, not only should we consider the geographic coordinate system but also we need to combine it with our social rules, such as ground resolution, map scale, confidentiality and military map.
**B.	Basic methods in the geographic information visualization**
- Point data. Point data is often use to label in the map and it can help us realize the notice of the area conveniently. PixelMap arithmetic is popular in dealing with point data which always overlap in the surface. It can let the data float in it.
- Line data. Map is the earliest to use line data to draw flow map and it can make the movement of the objective in it directly.
- Area data. To specify various area situation, we usually use choropleth map, cartogram map and thermodynamic diagram. We can tell different area data by their different color or proportion.
- Spatiotemporal data. To combine geographic data and space data together, we can tell the story by spatiotemporal data. We can use animation to explain the movement of the map and it is increasingly popular that we use visual analysis of complex geographic data.

     	Spatiotemporal data          

**C.	Online  map**
Online map is the pioneer of data visualization in our daily life. Online map can be connected with all our life, trip and on and off duty. Google map and Baidu map are well known in the world as we will use the map in case of getting lost. Moreover, the online map can help people drive a long way and no need to remember the details of the road which is of great significance for modern people’s life.

## V.	Tree And Nets Data Visualization
**A.	Hierarchical data**
Hierarchical data is the foundation of human’s cognition. The most important problem of Hierarchical data hard to present the huge quantities of data. One of the solution is to use the “focus and context” technology to enlarge the selected data while shrink the rest of information.
In the representation of it, we can use the node-link, it can use different dimension to introduce the data and we can clarify their hierarchical structure easily. Space-filling can make full use of space to explain the huge volume of data such as treemap and sun burst. While hybrid layout combine the advantage of node-link and space-filling and it still have some drawbacks as it will be hard to explain the relationship of the data.
**B.	Network data
1)	General express way
a)	Node-link figure**
It is the most common use in social network data visualization. By arranging the appropriate position of the node, it can represent the liquidity and consistency of the picture better.
In graph drawing, an arc diagram is a style of graph drawing, in which the vertices of a graph are placed along a line in the Euclidean plane, with edges being drawn as semicircles in one of the two halfplanes bounded by the line, or as smooth curves formed by sequences of semicircles. It cannot tell the overall situation of the data but it can show the relationship of different data in a direct way.
Force directed graph drawing algorithms are a class of algorithms for drawing graphs in an aesthetically pleasing way. It can produce good-quality results which is full of flexibility and interactivity. However, it will cost high running time to produce the final result. 

            arc diagram                                              Force directed layout
**b)	Adjacency matrix**
In graph theory and computer science, an adjacency matrix is a square matrix used to represent a finite graph. The elements of the matrix indicate whether pairs of vertices are adjacent or not in the graph. 
**c)	Node trix**
If we need to deal with the data with part of dense and sparse, it is hard to find a method that can deal with them. In this way, we can combine these two methods together and provide choice for the user to represent the data in their best way.
**d)	Path visualization for adjacency matrices**
Adjacency matrix can explain the direct relationship of different data in the immediate way but hard to appear the indirect relationship of them. Sheny adjusted augment adjacency matrices with path visualization and associated interaction techniques to facilitate path finding in the paper in 2007 and following picture is their work.
  
                                            node trix                               path visualization for adjacency matrices
**2)	Optimization way**
GMap is a practical algorithm for visualizing relational data with geographic-like maps. It makes up of the drawback of traditional techniques, such as they will capture the underlying structural information, clustering and neighborhoods.
Hierarchical edge bundles are a new method for visualizing such compound graphs. The approach is based on visually bundling the adjacency edges, i.e., non-hierarchical edges, together. This hierarchical bundling reduces visual clutter and also visualizes implicit adjacency edges between parent nodes that are the result of explicit adjacency edges between their respective child nodes.
 
                                   Gmap                                                            Hierarchical edge bundles

## VI.	Time-Varying Data Visualization
**A.	An introduction to visualization for time-oriented data**
Time-varying data can be divided into two parts: arranged in the timeline of time-varying data and data set that have intrinsic order but not varied with time. It is one of the most familiar data in our daily life because the price that varied with time is belong to that kind of data, such as stock. The goal of the analysis of time-oriented data is to calculate the similarity of the data and their extreme and it can help us have a quick search through it.

**B.	Visual survey of visualization techniques for time-oriented data  
1)	Type of data**
If we put the attribute of time as the horizontal axis and data will be the corresponding variable of time in the index. Time is an exceptional dimension that is common to many application domains such as medicine, engineering, business, science, biography, history, planning, or project management. Understanding time-oriented data enables us to learn from the past in order to predict, plan, and build the future. 
There are two types of time-oriented data. One is the frame of reference and the other is number of variables. Frame of reference contains abstract and spatial type of data. While in the number of variables, one of the typical time-oriented data is Gantt chart and in the multivariate, we can use X-axis or the Y-axis to explain the flow time in different branch. As the following example, we can tell the story from the horizontal axis or the vertical axis and it will be convenient for the user to understand our story in a short time.
 
  X-axis represents time                                          Y-axis represents time    
Moreover, we can use multiple perspective to explain the linear time. In the orthogonal layout, we can use data vases and the arab spring to tell the story. Thakur used the data vases to show the time series of crime rates in North Carolina 100 countries during 1980-2005. Individual kite diagrams are arranged alphabetically from left to right based on county names and colored based on geographic regions in North Carolina.
In the picture of Arab Spring, it represents the development of Arab in different times. The horizontal axis shows various countries and the vertical axis represents the time period. We can use different color of symbol to put on the picture to present the breaking news in that area of time period.
 
           data vases                                                                   arab spring 

**2)	Time**
There are several types of time arrangement of the time-oriented data. Tominski introduced multiple-dimension time oriented data in his paper and named it timewheel. The following picture is the screen shot of a timewheel. The lengths of the circular axes and the color fading are computed according the angle formed by each axis with the central axis of reference. This method can show multiple-dimension time oriented data in a direct way. However, there are still some disadvantages beside it such as some data will be kept out so that we cannot present too many data.
Later in 2008, Tominski improved existing spiral displays by applying the expressive two-tone pseudo coloring. It allows users to read off data values more precisely. More importantly, they enhanced two-tone spiral display with efficient interaction facilities.
In 2012, Tominski used trajectory wall to explained the instant of time. The core of their approach is a hybrid 2D/3D display. They solution was equipped with analytical and interactive mechanisms for selecting and ordering of trajectories. 
Moreover, triangular model is popular to explain the time interval. In this model, x-axis on behalf of the time while y-axis is the time interval. Every event’s time interval can be understood by the y-axis. It is useful to show the relationship between data and time interval.
![13.png](https://i.loli.net/2017/07/30/597d897ef216f.png)

**3)	Type of visualization **
There are static and dynamic mapping ways of visualization and static mapping is mainly used in visualization. One of the representative of dynamic mapping is Trendalyzer, animated scatter plot. Generally speaking, these 2D scatter plot shows two kinds of data and animation emphasize time. But Trendalyzer, a special information visualization software, can create a new dimension by color and area to explain more information.
As for the dimensionality, we can use 2D and 3D pictures to explain the data. 3D has a main problem that will cover some data. Carvalho created a model which use temporal focus and context to visualize several time periods.
**C.	Streaming data visualization  **
Streaming data is data that generated continuously by thousands of data sources, which typically send in the data records simultaneously and in small sizes. It is beneficial in most scenarios where new, dynamic data is generated on a continual basis. It applies to most of the industry segments and big data use cases. Users can have three interactions with them: search for the output, arrange data layout and custom-made big data.
The technology of streaming data processing is quite mature. Time window, time series data similarity calculation and symbolic aggregate approximation have been applied in this field.
As for the streaming data visualization case, system log monitoring data flow and text data stream is popular in our work and life. For example, the event river. In the following picture, it is the CNN news from August 1 to 24, 2006 in EventRiver. The horizontal axis of the display is a time axis where time flows from left to right. Each bubble represents an event mapped to a cluster of documents in the collection. Events with the same color and adjacent to each other in their vertical positions are closely related and construct a long-term story.

event river

## VII.	Media Data Visualization
**A.	Text and ducuemnt visualization**
As my dissertation is the analysis of public opinion and I find this quite useful for me. Before we analyze the data, we need to turn the text and document into digital. There are several aspects that we can do research on. First of all, in the text visualization based on keywords, word cloud, docuburst and document cards are popular to show the keywords. Themeriver and history flow is the represent method of the text content visualization that based on the timing. Furthermore, sentiment analysis visualization is quite useful in the text and document visualization. We can divide our data into two parts, positive and negative and sentiment map is the most common method to show it.
There are three types of text relationship visualization and they are based on hierarchy model, map or the collection of document. Word tree and newsmap are one of the visualization that based on hierarchy models. Phrase nets show the relationship of different word and picture based by pictures. The collection of document visualization will use galaxy view and themescape to introduce the data. In addition, contextour, faceatlas and parallel tag clouds are frequently used in the expression of multi-level data.
**B.	Hypermedia data visualization**
Image, video and sound data can also be visualized. An image is a well-behaved uniform dataset and we can use color, light and shade and scene to visualize their characteristics. Hypermedia data visualization’s strategy is to provide the user with different hierarchies, each giving a different perspective to the underlying information space to help the user better comprehend the information. It proposed an algorithm based on content and structural analysis to form hierarchies from hypermedia networks. The algorithm is automatic but can be guided by the user. The multiple hierarchies can be visualized in various ways.
Social networking visualization is increasingly popular as internet users from all over the world have created a large volume of time-stamped, geo-located data. Take one of our Weibo visualization homework as an example, we can obtain personal expression, hot news in the first step and extract major topics from a set of selected messages and rank them probabilistically using Latent Dirichlet Allocation. Furthermore, we can analyze the networking data to provide insights for investigations and understanding the extent of incidents, their severity and consequences.

## References
1.CHEN Wei, SHEN Zeqian, TAO Yubo, et al. Data visualization[M].Beijing: Electronic Industry Press, 2013
2.Steele J, Iliinsky N P N. Beautiful visualization /[M]. O'Reilly Media, 2010.
3.Sheny Z, Maz K L. Path Visualization for Adjacency Matrices.[C]// Joint Eurographics-ieee Tcvg Symposium on Visualization. DBLP, 2007:83-90.
4.Henry N, Fekete J D, Mcguffin M J. NodeTrix: a Hybrid Visualization of Social Networks[J]. IEEE Transactions on Visualization & Computer Graphics, 2007, 13(6):1302-1309.
5.Gansner E R, Hu Y, Kobourov S. GMap: Visualizing graphs and clusters as maps[C]// Visualization Symposium. IEEE, 2010:201-208.
6.Keim D A, Panse C, Sips M, et al. Visual data mining in large geospatial point sets[J]. IEEE Computer Graphics and Applications, 2004, 24(5): 36-44.
7.Holten D. Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data[J]. IEEE Transactions on Visualization & Computer Graphics, 2006, 12(5):741-748.
8.Aigner W, Miksch S, Schumann H, et al. Visualization of time-oriented data[M]. Springer Science & Business Media, 2011.
9.Thakur S, Hanson A J. A 3D visualization of multiple time series on maps[C]//Information Visualisation (IV), 2010 14th International Conference. IEEE, 2010: 336-343.
10.Tominski C, Abello J, Schumann H. Axes-based visualizations with radial layouts[C]//Proceedings of the 2004 ACM symposium on Applied computing. ACM, 2004: 1242-1247.
11.Tominski C, Schumann H. Enhanced interactive spiral display[C]//SIGRAD 2008. The Annual SIGRAD Conference Special Theme: Interaction; November 27-28; 2008 Stockholm; Sweden. Linköping University Electronic Press, 2008 (034): 53-56.
12.Tominski C, Schumann H, Andrienko G, et al. Stacking-based visualization of trajectory attribute data[J]. IEEE Transactions on visualization and Computer Graphics, 2012, 18(12): 2565-2574.
13.Peuquet D J, Ci-Xiang Z. An algorithm to determine the directional relationship between arbitrarily-shaped polygons in the plane[J]. Pattern Recognition, 1987, 20(1): 65-74.
14.Yi J S, ah Kang Y, Stasko J. Toward a deeper understanding of the role of interaction in information visualization[J]. IEEE transactions on visualization and computer graphics, 2007, 13(6): 1224-1231.
15.Carvalho A, De Sousa A A, Ribeiro C, et al. A temporal focus+ context visualization model for handling valid-time spatial information[J]. Information Visualization, 2008, 7(3-4): 265-274.
16.Chae J, Thom D, Bosch H, et al. Spatiotemporal social media analytics for abnormal event detection and examination using seasonal-trend decomposition[C]//Visual Analytics Science and Technology (VAST), 2012 IEEE Conference on. IEEE, 2012: 143-152.
17.Cao N, Lin Y R, Sun X, et al. Whisper: Tracing the spatiotemporal process of information diffusion in real time[J]. IEEE Transactions on Visualization and Computer Graphics, 2012, 18(12): 2649-2658.
