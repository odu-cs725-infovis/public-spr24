# Semester Agenda

[Jump to Week 14](#week-14)

## Week 1

[Agenda and Materials](#agenda-and-materials) | [Assignment](#assignment) | [Resources](#resources)

### Due Mon (before class)

* Complete the "Start Here" tasks in Canvas
* Make an "Introduce Yourself to the Class" post in Canvas

### Due Wed (before class)

* Watch intro to data visualization videos
  * [Tamara Munzner's keynote at d3.unconf](https://www.youtube.com/watch?v=jVC6SQS23ak) (55:49) ([slides](https://www.cs.ubc.ca/~tmm/talks/minicourse14/vad15d3unconf.pdf))
    * at time 34:15 (slide 19) -- pause this video, watch the two below, then go back and finish this one
  * My Intro to InfoVis lectures from CS 432/532 in the Media Gallery ([slides](https://docs.google.com/presentation/d/1dnKwKgOAWQ37QzHXxbbIZ-J4R8KYFO4Ss12VFkit-wA/preview))
    * CS 432/532 - Mod 03, p1 - InfoVis Principles (12:15)
    * CS 432/532 - Mod 03, p2 - Visualization Idioms (12:39)
* Make a "Week 1 | Discussion Vis Overview" post in Canvas and review other students' questions.

### Agenda and Materials

**Mon:**

* Course Intro
  * [GitHub repo](README.md)
  * [Canvas course](https://canvas.odu.edu/courses/152933)
  * [Syllabus](syllabus.md)
* [Personal Intro](https://canvas.odu.edu/courses/152933/discussion_topics/723575) - Canvas discussion

**Wed:**

* Data Vis Overview
  * discuss questions from [Week 1 Discussion](https://canvas.odu.edu/courses/152933/discussion_topics/723573)
* Data Sources
  * [Stop using Kaggle for your Data Science projects](https://faun.dev/c/stories/edwarda_johnson/stop-using-kaggle-for-your-data-science-projects/)

### Assignment

* [HW1 - Vega-Lite Intro](HW1-VegaLite.md)
* Review Week 2 materials and complete the reading assignment before class

### Resources

[CS 725/825 project highlights (2021-2022)](https://ws-dl.blogspot.com/2022/12/2022-12-02-visualization-class-projects.html)

#### Data Vis Overview

* Tamara Munzner's half-day [IEEE VIS 2020 Visualization Analysis & Design Tutorial](https://www.youtube.com/playlist?reload=9&list=PLT4XLHmqHJBffudbh19w_duD7mprvNf4Q)
* Jeffrey Heer, Michael Bostock, and Vadim Ogievetsky, ["A Tour Through the Visualization Zoo"](https://queue.acm.org/detail.cfm?id=1805128%20), *ACM Queue*, Vol. 8, No. 5, May 2010
* [eagereyesTV](https://www.youtube.com/c/eagereyes/videos) - visualization videos from Robert Kosara
* Visualization Idioms
  * Improper use of line charts - <http://callingbullshit.org/case_studies/case_study_musician_mortality.html>
  * [Understanding Pie Charts](https://eagereyes.org/techniques/pie-charts), Robert Kosara, eagereyes.org
  * Stacked Bar charts - <http://www.storytellingwithdata.com/blog/2017/11/22/use-cases-for-stacked-bars>
  * [Histogram Design Decisions](https://policyviz.com/2018/11/27/histogram-design-decisions/), policyviz.com
  * [Why We Love the CDF and Do Not Like Histograms That Much](http://www.andata.at/en/software-blog-reader/why-we-love-the-cdf-and-do-not-like-histograms-that-much.html), Andreas Kuhn, ANDATA Software Blog
  * [Hexagonal Binning – a new method of visualization for data analysis](https://www.meccanismocomplesso.org/en/hexagonal-binning-a-new-method-of-visualization-for-data-analysis/) - nice explanation of why hexagons
* [Dataviz Cheatsheet](https://policyviz.com/2018/08/07/dataviz-cheatsheet/), from policyviz.com
* [my guiding principles](http://www.storytellingwithdata.com/blog/2017/8/9/my-guiding-principles), storytellingwithdata.com -- set of basic principles for vis design
* [How to define a map’s bins to visualize your data](https://policyviz.com/2018/02/08/how-to-define-a-maps-bins-to-visualize-your-data/), Policy Viz

#### Data Sources

* [list of public datasets from CS 625-F21, HW6](https://github.com/odu-cs625-datavis/public/blob/main/fall21/HW6.md#data-sources)
* [Data Is Plural archive](https://www.data-is-plural.com/archive/) - weekly newsletter of useful/curious datasets
* [Our World in Data GitHub](https://github.com/owid), [datasets](https://github.com/owid/owid-datasets/tree/master/datasets)
* [US Census Bureau data](https://data.census.gov)
  * articles with tools and tips on using US Census Bureau data, <https://carolinademography.cpc.unc.edu/category/story-recipe/>
  * R package, <https://walker-data.com/tidycensus/>
  * Python package, <https://pypi.org/project/census/>

## Week 2

[Agenda and Materials](#agenda-and-materials-1) | [Assignment](#assignment-1)
| [Resources](#resources-1)

### Due (before class)

*nothing due this week*

### Agenda and Materials

**Mon: NO CLASS - MLK, Jr. Holiday**

**Wed:**

Observable/Arquero/Vega-Lite Practice Notebook - <https://observablehq.com/@oducs-vis/observable-arquero-vega-lite-practice-notebook> ([in-class version](https://observablehq.com/@oducs-vis/cs725s24-inclass-1))

Observable - see [Observable](#observable) links below

Arquero, library for query processing and transformation of array-backed data tables - see [Arquero](#arquero) links below

### Assignment

* Review Week 3 materials and complete the reading assignment before class

### Resources

#### Observable

* [Getting Started](https://observablehq.com/@observablehq/getting-started)
* [Learning Observable collection](https://observablehq.com/@observablehq/learning-observable-introduction?collection=@observablehq/intro-to-observable)
  * [Notebooks and cells](https://observablehq.com/@observablehq/learning-observable-notebooks-and-cells?collection=@observablehq/intro-to-observable)
  * [Getting data into Observable](https://observablehq.com/@observablehq/learning-observable-getting-data-into-observable?collection=@observablehq/intro-to-observable)
  * [Cell modes, reactive Markdown, and HTML](https://observablehq.com/@observablehq/learning-observable-cell-modes-reactive-markdown-and-html?collection=@observablehq/intro-to-observable)
  * [Reactive dataflow](https://observablehq.com/@observablehq/learning-observable-reactive-dataflow?collection=@observablehq/intro-to-observable), introduces the [Minimap](https://observablehq.com/@observablehq/minimap)
  * [JavaScript and Observable](https://observablehq.com/@observablehq/learning-observable-javascript-and-observable?collection=@observablehq/intro-to-observable)
* [A Minimal Introduction to JavaScript and Observable](https://observablehq.com/@uwdata/a-minimal-introduction-to-javascript-and-observable) - JavaScript basics
* [Keyboard Shortcuts](https://observablehq.com/@observablehq/keyboard-shortcuts)
* [Observable/GitHub flavored Markdown summary](https://observablehq.com/@ajlimbert/github-flavored-markdown-cheatsheet-observable)

#### Arquero

* [Introducing Arquero](https://observablehq.com/@uwdata/introducing-arquero)
  * [Data Transformation](https://observablehq.com/@nyuvis/data-transformation) - preview of Data Transformation in JavaScript and D3
* [Arquero API Reference](https://uwdata.github.io/arquero/api/)
* [Arquero Notebook Collection](https://observablehq.com/collection/@uwdata/arquero)

## Week 3

[Agenda and Materials](#agenda-and-materials-2) | [Assignment](#assignment-2) | [Resources](#resources-2)

### Due Wed (before class)

* Read Enrico Bertini, [From Data Visualization to Interactive Data Analysis](https://medium.com/@FILWD/from-data-visualization-to-interactive-data-analysis-e24ae3751bf3), medium.com, November 2017. ([PDF available in Canvas](https://canvas.odu.edu/files/31761513/))

### Agenda and Materials

**Mon:**

Observable/Arquero/Vega-Lite Practice Notebook - <https://observablehq.com/@oducs-vis/observable-arquero-vega-lite-practice-notebook>  ([in-class version](https://observablehq.com/@oducs-vis/cs725s24-inclass-1))

Vega-Lite in Observable - see [Vega-Lite API Style](#vega-lite-api-style) and [Vega-Lite JSON style](#vega-lite-json-style) links below

**Wed:**

[Visual Analytics slides](https://docs.google.com/presentation/d/1SnabdFdtfhyYQov66Hr3ZvfMp1U3TZ3DSuTVDBZHTTU/preview)

* watch visual analytics videos
* discuss Bertini article
* highlight examples of visual analytics systems

### Assignment

* HW1 is due next week
* Review next week's materials before class
  * in particular, fork and start experimenting with the D3 Observable notebook - *to be posted*

### Resources

#### Vega-Lite API style

* [Vega-Lite API Reference](https://vega.github.io/vega-lite-api/api/)
* [Observable for Vega-Lite](https://observablehq.com/collection/@observablehq/observable-for-vega-lite) - collection of intro notebooks
  * [Charting with Vega-Lite](https://observablehq.com/@observablehq/vega-lite?collection=@observablehq/observable-for-vega-lite)
  * [Vega-Lite Chart Types](https://observablehq.com/@observablehq/vega-lite-chart-types?collection=@observablehq/observable-for-vega-lite)  - Week 5 in CS 625
  * [Layers and Facets and Concat, Oh My!](https://observablehq.com/@observablehq/layers-facets-concat?collection=@observablehq/observable-for-vega-lite)
* [UW's Data Visualization Curriculum](https://observablehq.com/@uwdata/data-visualization-curriculum) - collection of more detailed notebooks, several covered in CS 625
  * *won't be directly covered in class, but here for your reference*
  * including [Introduction to Vega-Lite](https://observablehq.com/@uwdata/introduction-to-vega-lite), [Data Types, Graphical Marks, and Visual Encoding Channels](https://observablehq.com/@uwdata/data-types-graphical-marks-and-visual-encoding-channels), [Data Transformation](https://observablehq.com/@uwdata/data-transformation), [Scales, Axes, and Legends](https://observablehq.com/@uwdata/scales-axes-and-legends), [Multi-View Composition](https://observablehq.com/@uwdata/multi-view-composition), [Interaction](https://observablehq.com/@uwdata/interaction)
* [Vega-Lite API v4](https://observablehq.com/@vega/vega-lite-api) vs. [Vega-Lite API v5](https://observablehq.com/@vega/vega-lite-api-v5)
* [CS 625 Observable Collection](https://observablehq.com/collection/@oducs-vis/cs625)
* Learn by example -- use Google to search for examples specifically in Observable, ex: "scatterplot vega-lite site:observablehq.com"

#### Vega-Lite JSON-style

* [Vega-Lite Reference](https://vega.github.io/vega-lite) (JSON-based)
* [Vega Embed](https://github.com/vega/vega-embed)
* [Hello Vega-Embed](https://observablehq.com/@vega/hello-vega-embed)
* [Working with Vega-Lite](https://observablehq.com/@didoesdigital/working-with-vega-lite)
* [Vega-Lite API vs. JSON Examples](https://observablehq.com/@oducs-vis/vega-lite-api-vs-json?collection=@oducs-vis/cs625) - Week 5 in CS 625

#### Visual Analytics Videos

* Jean-Daniel Fekete, Visual Analytics - Mastering the Information Age, 2010, <https://www.youtube.com/watch?v=5i3xbitEVfs> (7:39)
* Jeff Hemsley (Syracuse iSchool), What is Visual Analytics?, 2021, <https://www.youtube.com/watch?v=0og3HT8UqD4> (19:00)

#### Examples of Visual Analytics Systems

* [Visual Analysis and Dissemination of Scientific Literature Collections with SurVis](https://ieeexplore.ieee.org/document/7192633), IEEE TVCG 2016
* [TopicSifter: Interactive Search Space Reduction Through Targeted Topic Modeling](https://arxiv.org/pdf/1907.12079.pdf), IEEE VIS 2019
* [MineTime Insight: Visualizing Meeting Habits to Promote Informed Scheduling Decisions](https://cgl.ethz.ch/Downloads/Publications/Papers/2019/Anc19b/Anc19b.pdf), IEEE VIS 2020
* [SmartAdP: Visual Analytics of Large-scale Taxi Trajectories for Selecting Billboard Locations](http://urban-computing.com/pdf/SmartAdP_Zheng.pdf), IEEE TVCG 2017
* [PassVizor: Toward Better Understanding of the Dynamics of Soccer Passes](https://arxiv.org/pdf/2009.02464.pdf), IEEE VIS 2020
* [DECE: Decision Explorer with Counterfactual Explanations for Machine Learning Models](https://arxiv.org/pdf/2008.08353.pdf), IEEE VIS 2020

## Week 4

[Agenda and Materials](#agenda-and-materials-3) | [Assignment](#assignment-3) | [Resources](#resources-3)

### Due Mon (before class)

* HW1

### Agenda and Materials

**Mon:**

* D3 Principles and Data Manipulation
  * [D3 Data Intro](https://observablehq.com/@oducs-vis/d3-data-intro?collection=@oducs-vis/cs-725)

**Wed:**

* IEEE VIS Conferences
  * slides ([IEEE VIS slides](https://docs.google.com/presentation/d/1Qy17ElNTbgEvvcqxKuAqRMfrifVDPDr8KbKCR5mb6Vw/preview))
* Reading Academic Papers
  * slides from CS 800 ([Week-03b-Reading](https://docs.google.com/presentation/d/1iCAQLektZfcHzJi95StyGhzhAc-zjhi2cDmII3_Tlik/preview))

## Assignment

* [HW2 -  Data Manipulation](HW2-data.md)
* Review next week's materials before class

### Resources

#### D3 Data

* NYU Visualization [Guides and Examples Collection](https://observablehq.com/collection/@nyuvis/guides-and-examples)
* JavaScript
  * [Docs @Mozilla Dev Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  * [Docs @W3Schools](https://www.w3schools.com/jsref/jsref_reference.asp)
  * NYU Vis [JavaScript Basics](https://observablehq.com/@nyuvis/javascript-basics?collection=@nyuvis/guides-and-examples)
* NYU Vis [Data Transformation](https://observablehq.com/@nyuvis/data-transformation?collection=@nyuvis/guides-and-examples)
* NYU Vis [SVG and D3 Basics](https://observablehq.com/@nyuvis/d3-introduction?collection=@nyuvis/guides-and-examples)

#### IEEE VIS

* IEEE VIS YouTube channel, <https://www.youtube.com/@IEEEVisualizationConference/featured>
* IEEE VIS main website, <https://www.ieeevis.org>
* IEEE Xplore (ODU proxy) - <https://ieeexplore-ieee-org.proxy.lib.odu.edu/Xplore/home.jsp>
* [IEEE VisWeek Papers on the Web](http://www.cad.zju.edu.cn/home/vagblog/vispapers.html) - last updated 2019
* [IEEE Transactions on Visualization and Computer Graphics (TVCG)](https://www.computer.org/csdl/journal/tg)
  * [TVCG @ IEEE Xplore](https://ieeexplore-ieee-org.proxy.lib.odu.edu/xpl/RecentIssue.jsp?punumber=2945)
* [Vispubdata](https://sites.google.com/site/vispubdata/home)

#### Reading Academic Papers

* [My Research Methods Guidelines](https://docs.google.com/document/d/1ZIlCog36OoNKymgWZkJ5D8142JQ19WGjbaqW34ymd_8/edit)
* Example of off-campus access to ACM Digital Library, <https://dl-acm-org.proxy.lib.odu.edu/doi/abs/10.5555/1218112.1218509>
* Example of off-campus access to IEEE Xplore, <https://ieeexplore-ieee-org.proxy.lib.odu.edu/document/6970187>
* Fatcat, <https://fatcat.wiki/>
  * My papers: <https://fatcat.wiki/release/search?q=michele+c.+weigle>
  * Example search for a particular paper, <https://fatcat.wiki/release/search?q=Automatically+Selecting+Striking+Images+for+Social+Cards>
  * Example search for a particular conference venue, <https://fatcat.wiki/container/search?q=Joint+conference+on+digital+libraries>
  * JCDL page, <https://fatcat.wiki/container/kw2apmx5ynfyjf6jhs5gzrrx6e>
  * IEEE Transactions on Visualization and Computer Graphics page, <https://fatcat.wiki/container/hjrujdrg7zaghbdsp5pdzq7cmm>
* Internet Archive Scholar, <https://scholar.archive.org/>
  * My papers: <https://scholar.archive.org/search?q=michele+c.+weigle>
  * Example search for a particular paper, <https://scholar.archive.org/search?q=automatically+selecting+striking+images+for+social+cards>
* S. Keshav, [How to Read a Paper](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf)
* [Reading Papers](https://www.cs.odu.edu/~mweigle/courses/JFB_03_reading_papers.pdf), lecture slides from Dr. Brunelle's CS 891, Spring 2019
* William Griswold, [How to Read an Engineering Research Paper](http://www.cs.ucsd.edu/users/wgg/CSE210/howtoread.html)
* [Example of marking up a paper](https://drive.google.com/open?id=1UQeT9o-IvLhp5RAv1vAJ7DS-lXQdNW7E)
* Jason Eisner, [How to Read a Technical Paper](http://www.cs.jhu.edu/~jason/advice/how-to-read-a-paper.html)
* Michael Mitzenmacher, [How to Read a Research Paper](http://www.eecs.harvard.edu/~michaelm/postscripts/ReadPaper.pdf)
* Tia Newhall, [Some Tips for Reading Research Papers](http://www.cs.swarthmore.edu/~newhall/cs97/s00/ReadingAdvice.html)

## Week 5

[Agenda and Materials](#agenda-and-materials-4) | [Assignment](#assignment-4) | [Resources](#resources-4)

### Agenda and Materials

**Mon:**

* [D3 Vis Intro](https://observablehq.com/@oducs-vis/d3-vis-intro)
  * [supplemental slides](https://docs.google.com/presentation/d/1r_hh5f0sdSrxXYb-UJGSu-OlG1U65H32pAgraMVDVg0/preview)
  * [SVG Translate Example slides](https://docs.google.com/presentation/d/1TKFcgmPKvybFX22-XDJ8f3Hn_0IVbmo5rt045GX34jE/preview)

**Wed:**

* Giving Presentations
  * slides from CS 800 ([Week-06-Presenting](https://docs.google.com/presentation/d/1bCCL7bw5j41e3se3oLH-qakLT0P0GKFhec5T8EZ9FXs/preview))

### Assignment

* [Academic Paper Presentation](presentation.md)
  * [suggested papers list](papers.md)
* Review next week's materials before class

### Resources

#### D3 Vis Intro

* [Video playlist for W209 Data Visualization at UC Berkeley's Masters in Data Science (MIDS) Program](https://www.youtube.com/playlist?list=PLmRfPZr9-VoGodduNBkPKoNNXeOBMmQGz) - includes web development basics, ObservableHQ, Intro to D3 with Observable, Intro to Vega-Lite with Observable, and more!
* D3 Vis Intro
  * [NYU Visualization Guides and Examples Collection](https://observablehq.com/collection/@nyuvis/guides-and-examples)
  * [NYU Vis D3 Introduction](https://observablehq.com/@nyuvis/d3-introduction?collection=@nyuvis/guides-and-examples)
  * [NYU Vis Bar Chart Walk-through](https://observablehq.com/@nyuvis/bar-chart-walk-through?collection=@nyuvis/guides-and-examples)
* [Learn D3 Collection](https://observablehq.com/collection/@d3/learn-d3)
  * [Learn D3: By Example](https://observablehq.com/@d3/learn-d3-by-example?collection=@d3/learn-d3)
* [D3 Documentation Collection](https://observablehq.com/collection/@d3/documentation)
* [D3 Gallery](https://observablehq.com/@d3/gallery)
* [D3 API Reference](https://github.com/d3/d3/blob/main/API.md)

#### Giving Presentations

* Ashwin Ram, [Presenting a Paper](https://www.cc.gatech.edu/faculty/ashwin/wisdom/how-to-present-a-paper.html) - focuses on presenting others' work
* Jiri Srba, [How to Read and Present a Scientific Paper](https://homes.cs.aau.dk/~srba/courses/FS-07/slides-talk.pdf)
* Nicholas Nethercote, [Giving a Good Research Talk](https://web.archive.org/web/20200220135851/http://njn.valgrind.org/good-talk.html)
* Justin Brunelle, [Presenting Academic Research slides](https://www.cs.odu.edu/~mweigle/courses/JFB_06_presenting101.pdf), from CS 891, Fall 2019
* Tamara Munzner, <http://www.cs.ubc.ca/~tmm/policy.txt>
* Jones et al., [How to Give a Good Research Talk](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/08/giving-a-talk.pdf)
* Arnaud Legout, [How To Give a Talk](http://cel.archives-ouvertes.fr/cel-00529505/en/) - comprehensive set of guidelines, includes advice on slide design
* Jean-luc Doumont, [Creating Effective Slides](https://www.youtube.com/watch?v=meBXuTIPJQk), talk April 4, 2013 at Clark Center, Stanford Univeristy, video (1:03:03)
* English Communication for Scientists, [Giving Oral Presentations](https://www.nature.com/scitable/ebooks/english-communication-for-scientists-14053993/giving-oral-presentations-14239332) (includes delivering as a non-native speaker)

## Week 6

[Agenda and Materials](#agenda-and-materials-5) | [Assignment](#assignment-5) | [Resources](#resources-5)

### Due Mon (before class)

* HW2

### Due Wed (before class)

* Skim Heer and Shneiderman, [Interactive Dynamics for Visual Analysis](https://queue.acm.org/detail.cfm?id=2146416) ([CACM pdf](https://idl.cs.washington.edu/files/2012-InteractiveDynamics-CACM.pdf)), *Communications of the ACM*, vol. 55, no. 4, 2012, pgs. 45-54
* Watch the videos [Flat and Hierarchical Clustering | The Dendrogram Explained](https://www.youtube.com/watch?v=ijUMKMC4f9I) (8:26) and [K Means Clustering: Pros and Cons of K Means Clustering](https://www.youtube.com/watch?v=YIGtalP1mv0) (watch up to time 4:44)

### Agenda and Materials

**Mon:**

* D3 Vis Intro
  * [Bar Chart](https://observablehq.com/@oducs-vis/d3-intro-bar-chart?collection=@oducs-vis/cs-725) ([supplemental slides](https://docs.google.com/presentation/d/1r_hh5f0sdSrxXYb-UJGSu-OlG1U65H32pAgraMVDVg0/preview))
  * [Scatterplot](https://observablehq.com/@oducs-vis/d3-intro-scatterplot?collection=@oducs-vis/cs-725)
  * [Line and Area Charts](https://observablehq.com/@oducs-vis/d3-intro-line-and-area-charts?collection=@oducs-vis/cs-725)
  * [Layered Line and Area Charts](https://observablehq.com/@oducs-vis/d3-intro-layered-line-and-area-charts?collection=@oducs-vis/cs-725)
  * [Multi-Line Chart Arquero Data Setup](https://observablehq.com/@oducs-vis/multi-line-chart-arquero-data-setup?collection=@oducs-vis/cs-725)

**Wed:**

* Handling Complexity in Data, [Complexity slides](https://docs.google.com/presentation/d/1YRXiqL7U1YXw5eXBtpmQphD8aJsWhNPrCQkyQrxfG1Y/preview)
* [Clustering slides](https://docs.google.com/presentation/d/1UWOzrw_93Rx4bNY5PSU0HeVF8UKd0SBU-OWnjp4vFj8/preview)
  * [Clustering Example with Vega-Lite](https://observablehq.com/@oducs-vis/vega-lite-clustering-example?collection=@oducs-vis/cs-725)

### Assignment

* [HW3](HW3-D3.md) - Intro to D3
* Review next week's materials before class

### Resources

#### D3 Vis

* [CS 725/825 Observable Collection](https://observablehq.com/collection/@oducs-vis/cs-725) - public notebooks for this semester
* [D3 Lessons](http://lessons.vaclab.unc.edu/), UNC INLS 641 Visual Analytics, David Gotz
* [NYU Vis Bar Chart Walkthrough](https://observablehq.com/@nyuvis/bar-chart-walk-through)
* [NYU Vis SVG and D3 Basics Practice](https://observablehq.com/@nyuvis/svg-and-d3-basics-practice-solutions) - scatterplot
* [NYU Vis Lines and Maps](https://observablehq.com/@nyuvis/lines-and-maps) - line and area charts
* [NYT Vis Graphical Encoding Examples](https://observablehq.com/@nyuvis/graphical-encoding-examples) - layered line charts, small multiple area charts
* [Arquero and D3](https://observablehq.com/@uwdata/arquero-and-d3?collection=@uwdata/arquero)
* [Multi-line chart data preparation in Arquero](https://observablehq.com/@uwdata/multi-line-chart-data-preparation)
* [Multi-line chart D3 template](https://observablehq.com/@d3/multi-line-chart/2)

#### Handling Complexity

* Tamara Munzner's VAD lectures
  * [Ch 11/12 Interactive Views, p1](https://www.youtube.com/watch?v=dHSYXZMY96s&list=PLT4XLHmqHJBeB5LwmRmo6ln-m7K3lGvrk&index=19) (25:38)
  * [Ch 11/12 Interactive Views, p2](https://www.youtube.com/watch?v=hxBRDRf_rTM&list=PLT4XLHmqHJBeB5LwmRmo6ln-m7K3lGvrk&index=20) (29:27)
  * [Ch 13 Reduce: Aggregation and Filtering](https://www.youtube.com/watch?v=3KjGpVo6JDU&list=PLT4XLHmqHJBeB5LwmRmo6ln-m7K3lGvrk&index=21) (24:39)
  * [Ch 14 Embed: Focus + Context](https://www.youtube.com/watch?v=A6NfuuAlENc&list=PLT4XLHmqHJBeB5LwmRmo6ln-m7K3lGvrk&index=22) (8:53)

#### Clustering

* Segaran, [*Programming Collective Intelligence*](https://go.oreilly.com/old-dominion-university/library/view/programming-collective-intelligence/9780596529321/) - textbook used in CS 432/532, includes lots of Python code examples
* [Flat and Hierarchical Clustering | The Dendrogram Explained video](https://www.youtube.com/watch?v=ijUMKMC4f9I)
* K-Means
  * [K-means Clustering Python Example](https://towardsdatascience.com/machine-learning-algorithms-part-9-k-means-example-in-python-f2ad05ed5203)
  * [Visualizing K-Means Algorithm](http://tech.nitoyon.com/en/blog/2013/11/07/k-means/)
  * [K-Means Walkthrough in Observable](https://observablehq.com/@andreaskdk/k-means)
  * [kmeans() in Observable](https://observablehq.com/@spond/k-means-clustering-algorithm)
  * [K Means Clustering: Pros and Cons of K Means Clustering video](https://www.youtube.com/watch?v=YIGtalP1mv0) - watch up to time 4:44

## Week 7

[Agenda and Materials](#agenda-and-materials-6) | [Assignment](#assignment-6) | [Resources](#resources-6)

### Due Mon (before class)

* Review [CS 625 Vega-Lite Interaction notebook](https://observablehq.com/@oducs-vis/cs-625-interaction)
* Skim [NYUVis D3 Interaction notebook](https://observablehq.com/@nyuvis/interaction?collection=@nyuvis/guides-and-examples)

### Due Wed (before class)

* Paper selection for presentation

### Agenda and Materials

* Vega-Lite: Interaction in Vega-Lite, <https://observablehq.com/@oducs-vis/vega-lite-interaction>
* D3: NYU Vis Interaction notebook, <https://observablehq.com/@nyuvis/interaction>

### Assignment

* Review next week's materials before class

### Resources

#### Interactivity in Vega-Lite

* [CS 625 - Interaction](https://observablehq.com/@oducs-vis/cs-625-interaction?collection=@oducs-vis/cs625)
  * based on [Interaction in Vega-Lite](https://observablehq.com/@uwdata/interaction) - notebook from UW IDL
* [Intro to Interactions in Vega-Lite](https://observablehq.com/@jonfroehlich/intro-to-interaction-in-vega-lite), complements original UW notebook and includes more complex examples, including
  * more examples and explanations of `params()`
  * combining multiple selections
  * legend binding (click on legend to interact with chart)
  * using Observable Inputs with Vega-Lite
* Vega-Lite v5 updates - <https://github.com/vega/vega-lite/releases/tag/v5.0.0> (moves from using `selection` to `params`)
  * Selection Parameters section in Dynamic Behaviors with Parameters, <https://vega.github.io/vega-lite/docs/parameter.html#select>
* [Vega-Lite API v5 Selection Methods Examples](https://observablehq.com/@weiglemc/vega-lite-api-v5-selection)
  * based on [Vega-Lite API Selection Methods](https://observablehq.com/@john-guerra/vega-lite-selection-methods), which uses Vega-Lite v4
* Docs
  * <https://vega.github.io/vega-lite-api/api/#parameters>
  * <https://vega.github.io/vega-lite-api/api/#parameter-bindings>
  * <https://vega.github.io/vega/docs/event-streams/>
  * <https://vega.github.io/vega-lite/examples/#interactive>

#### Observable Inputs

* [Observable Inputs reference](https://observablehq.com/@observablehq/inputs?collection=@observablehq/libraries)
* [Hello, Inputs!](https://observablehq.com/@observablehq/hello-inputs) - examples
* <https://observablehq.com/@mbostock/scrubber>

#### Interaction in D3

* [Interaction - D3](https://observablehq.com/@nyuvis/interaction?collection=@nyuvis/guides-and-examples) - notebook from NYU Vis
* [JavaScript Event reference](https://developer.mozilla.org/en-US/docs/Web/Events#Standard_events)
* [Introduction to views](https://observablehq.com/@observablehq/introduction-to-views) - Observable specific
* [d3-brush docs](https://github.com/d3/d3-brush)
* [d3-brush examples](https://observablehq.com/collection/@d3/d3-brush)
* [Introduction to D3, Part 2](https://observablehq.com/@uwdata/introduction-to-d3-part-2) - includes interaction

## Week 8

[Agenda and Materials](#agenda-and-materials-7) | [Assignment](#assignment-7) | [Resources](#resources-7)

### Due Mon (before class)

* Skim (little more than [Keshav's 1st pass](http://ccr.sigcomm.org/online/files/p83-keshavA.pdf), little less than Keshav's 2nd pass)
   * Sarikaya et al., "What Do We Talk About When We Talk About Dashboards?", IEEE VIS 2018, <https://alper.datav.is/assets/publications/dashboards/dashboards-preprint.pdf>
   * Bach et al., "Dashboard Design Patterns", IEEE VIS 2022, <https://arxiv.org/abs/2205.00757>
* HW3

**Mon:**

* Counterfactuals
  * Gotz et al., "Improving Visualization Interpretation Using Counterfactuals", IEEE VIS 2021, <https://vaclab.unc.edu/publication/tvcg_2022_kaul/tvcg_2022_kaul.pdf>
  * Video of presentation: https://vimeo.com/640020787 (10:55)
* Dashboard Design
  * "What Do We Talk About When We Talk About Dashboards?", VIS 2018 video, <https://vimeo.com/299862354> (12:50)
  * "Dashboard Design Patterns", VIS 2022 presentation <https://www.youtube.com/watch?v=n6qWuzk3u0k&t=3008s> (12m), pre-precorded video <https://www.youtube.com/watch?v=P70kXAco3Qo> (14:12) 
  * Dashboard Design Patterns website, <https://dashboarddesignpatterns.github.io/>
  * Bakusevych, [10 Rules for Better Dashboard Design](https://uxplanet.org/10-rules-for-better-dashboard-design-ef68189d734c)
  * Tableau Help, [Best Visual Practices](https://help.tableau.com/current/blueprint/en-us/bp_visual_best_practices.htm)

**Wed:**

* Implementing Dashboards
   * [Vega-Lite Dashboard with Brushing and Linking](https://observablehq.com/@oducs-vis/vega-lite-dashboard-with-brushing-and-linking?collection=@oducs-vis/cs-725)
   * [D3 Dashboard with Brushing and Linking](https://observablehq.com/@oducs-vis/d3-dashboard-with-brushing-and-linking?collection=@oducs-vis/cs-725)

### Assignment

* Table Scraps video and discussion - see Canvas Discussions
* [HW4](HW4-dashboard.md) - Dashboards and Interaction
* [Project: Interactive Dashboard Visualization](project.md)
* *Next week is Spring Break!*
  
### Resources

*no additional resources*

## Week 9

[Agenda and Materials](#agenda-and-materials-8) | [Assignment](#assignment-8) | [Resources](#resources-8)

### Due Wed (before class)

* HW4
* Review Ch 9 in *Visualization Analysis & Design* (textbook link in the Syllabus)

### Agenda and Materials

**Mon:**  ***Class will be held asychronously***

* Visualizing Uncertainty - *watch the lecture video in Canvas Media Gallery*
  * [Uncertainty slides](https://docs.google.com/presentation/d/1sAO0ARfRDhF1I2014zqnoqSzTuM7H9_9PLpJRPPuexg/preview)
  * watch the ["How to Read Uncertainty Visualizations" video](https://www.youtube.com/watch?v=byDZlMwi7kU) from Lace Padilla

**Wed:**

* Network and Tree Vis
  * [Networks and Trees slides](https://docs.google.com/presentation/d/1O6K14vhHuoEBwUbcDFSHq0nKZYPN-bqMyYa_cPfT_Eg/preview)
* Table Scraps paper/video discussion
  * video - <https://www.youtube.com/watch?v=woyuvqUu52I>
  * [Table Scraps: An Actionable Framework for Multi-Table Data Wrangling From An Artifact Study of Computational Journalism](http://www.cs.ubc.ca/group/infovis/pubs/2020/table-scraps/), IEEE VIS 2020
  * Open Journalism GitHub, <https://github.com/silva-shih/open-journalism>
* Project Discussion

### Resources

#### Visualizing Uncertainty Slide References

* Nicole Torres, ["Why It’s So Hard for Us to Visualize Uncertainty"](https://hbr.org/2016/11/why-its-so-hard-for-us-to-visualize-uncertainty), Harvard Business Review,  
* Nathan Yau, ["Visualizing the Uncertainty in Data"](https://flowingdata.com/2018/01/08/visualizing-the-uncertainty-in-data/)
* Nathan Yau, ["Showing uncertainty during the live election forecast"](https://flowingdata.com/2016/11/15/showing-uncertainty-during-the-live-election-forecast/)
* [Live Presidential Forecast](https://www.nytimes.com/elections/2016/forecast/president), *NY Times*
* [Lace Padilla](https://www.lacepadilla.com/), Assistant Professor of Computer Science and Psychology, Northeastern University
* [Jessica Hullman](http://users.eecs.northwestern.edu/~jhullman/), Associate Professor of Computer Science, Northwestern University
* Lace Padilla, Matthew Key, and Jessica Hullman, ["Uncertainty Visualization"](https://psyarxiv.com/ebd6r), in *Handbook of Computational Statistics and Data Science*, book chapter preprint  
* Lace Padilla, "How to Read Uncertainty Visualizations", [video](https://www.youtube.com/watch?v=byDZlMwi7kU)
* Claus Wilke, [*Fundamentals of Data Visualization*](https://clauswilke.com/dataviz/)
* Hullman, J., P. Resnick, and E. Adar. 2015. [“Hypothetical Outcome Plots Outperform Error Bars and Violin Plots for Inferences About Reliability of Variable Ordering.”](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0142444) *PLOS ONE* 10: e0142444.

#### Network and Tree Visualization Slide References

* Tamara Munzner, Visualization Analysis & Design [slides](https://www.cs.ubc.ca/~tmm/talks/minicourse14/vadallslides.pdf) (pdf)
  * [Ch 9 Network Data](https://www.youtube.com/watch?v=XOUJssmvz58&list=PLT4XLHmqHJBeB5LwmRmo6ln-m7K3lGvrk&index=13) (30:49)
* [Force-directed Graph Drawing (Wikipedia)](https://en.wikipedia.org/wiki/Force-directed_graph_drawing)
* Kate Starbird, [“Information Wars: A Window into the Alternative Media Ecosystem”](https://medium.com/hci-design-at-uw/information-wars-a-window-into-the-alternative-media-ecosystem-a1347f32fd8f)
* [Intro to Forced Layouts](https://observablehq.com/@jkeohan/intro-to-forced-layouts) - examples of different forces
* [Force-Directed Graph](https://observablehq.com/@d3/force-directed-graph/2) - interactive version (interaction code starts at d3.drag())
* [Simple Force-Directed Graph for CS 432/532](https://observablehq.com/@weiglemc/force-directed-layout-example-cs-432-532-spring-2020)
* [Interactive & Dynamic Force-Directed Graphs with D3](https://medium.com/ninjaconcept/interactive-dynamic-force-directed-graphs-with-d3-da720c6d7811) - walkthrough with more explanation (d3.v4)
* [NYU Networks notebook](https://observablehq.com/@nyuvis/networks) - adjacency matrix, force-directed node-link
* D3 [Matrix Diagram](https://observablehq.com/@bstaats/matrix-diagram)
* D3 [Radial Tree](https://observablehq.com/@d3/radial-tree/2)
* D3 [Arc Diagram](https://observablehq.com/@bstaats/arc-diagram)
* D3 [Treemap](https://observablehq.com/@d3/treemap-stratify)
* D3 [Circle Packing](https://observablehq.com/@d3/pack/2)
* D3 [Sunburst](https://observablehq.com/@d3/sunburst/2)

## Week 10

[Agenda and Materials](#agenda-and-materials-9) | [Assignment](#assignment-9) | [Resources](#resources-9)

### Due Mon (before class)

* Academic Paper Presentation slides
* Project topic

### Agenda and Materials

VIS Paper Presentations ([schedule with links](https://canvas.odu.edu/courses/152933/pages/paper-presentation-schedule))

**Mon:**

* Thu - Multiple Forecast Visualizations (MFVs): Trade-offs in Trust and Performance in Multiple COVID-19 Forecast Visualizations, IEEE VIS 2022, <https://ieeexplore-ieee-org.proxy.lib.odu.edu/document/9904455>
* David - Let the Chart Spark: Embedding Semantic Context into Chart with Generative Model, IEEE VIS 2023, <https://arxiv.org/abs/2304.14630>
* Jenah - Affective Visualization Design: Leveraging the Emotional Impact of Data, IEEE VIS 2023, <https://arxiv.org/abs/2308.02831>

**Wed:**

* Caleb - Affective Learning Objectives for Communicative Visualizations, IEEE VIS 2022, <https://arxiv.org/abs/2208.04078>
* Yasasi - EmphasisChecker: A Tool for Guiding Chart and Caption Emphasis, IEEE VIS 2023, <https://arxiv.org/abs/2307.13858>
* Wes - Dead or Alive: Continuous Data Profiling for Interactive Data Science, IEEE VIS 2023, <https://arxiv.org/abs/2308.03964>

### Assignment

*no assignment*

### Resources

*no additional resources*

## Week 11

[Agenda and Materials](#agenda-and-materials-10) | [Assignment](#assignment-10) | [Resources](#resources-10)

### Due Mon (before class)

* Project audience, task, and scenario

### Agenda and Materials

VIS Paper Presentations ([schedule with links](https://canvas.odu.edu/courses/152933/pages/paper-presentation-schedule))

**Mon:**

* Eikra - My Model is Unfair, Do People Even Care? Visual Design Affects Trust and Perceived Bias in Machine Learning, IEEE VIS 2023, <https://ieeexplore-ieee-org.proxy.lib.odu.edu/document/10296507>

**Wed:**

* Prashant - Swaying the Public? Impacts of Election Forecast Visualizations on Emotion, Trust, and Intention in the 2022 U.S. Midterms, IEEE VIS 2023, <https://ieeexplore-ieee-org.proxy.lib.odu.edu/document/10309864>
* Soujanya - Reasoning Affordances with Tables and Bar Charts, IEEE VIS 2023, <https://ieeexplore-ieee-org.proxy.lib.odu.edu/document/10002893>
* Darin - Animated Vega-Lite: Unifying Animation with a Grammar of Interactive Graphics, IEEE VIS 2022, <https://vis.csail.mit.edu/pubs/animated-vega-lite.pdf>

### Assignment

*no assignment*

### Resources

*no additional resources*

## Week 12

**NO CLASS - Work on Projects**

## Week 13

**NO CLASS - Work on Projects**

## Week 14

[Agenda and Materials](#agenda-and-materials-11) | [Assignment](#assignment-11) | [Resources](#resources-11)

### Due Mon (before class)

* Project implementation

### Agenda and Materials

Project demos

* Thu - Global Landslide Occurrences
* David - Internet Usage in the US
* Wes - NFL ELO rating
* Prashant - Impact of Weather on Crops

You can view your classmates' projects and provide feedback or ask questions in the [Project Demo Discussion](https://canvas.odu.edu/courses/152933/discussion_topics/863553).

**Wed:**

Project demos

* Jenah - City of Norfolk Parks and Rec
* Eikra - Airbnb in NYC
* Yasasi - Graduation and Dropout Rates in Virginia Public Schools
* Maaz - Global Influenza Outbreaks

You can view your classmates' projects and provide feedback or ask questions in the [Project Demo Discussion](https://canvas.odu.edu/courses/152933/discussion_topics/863553).

### Assignment

*no assignment*

### Resources

*no additional resources*

## Week 15

[Agenda and Materials](#agenda-and-materials-12) | [Assignment](#assignment-12) | [Resources](#resources-12)

### Agenda and Materials

Maaz (paper presentation) - The Arrangement of Marks Impacts Afforded Messages: Ordering, Partitioning, Spacing, and Coloring in Bar Charts, IEEE VIS 2023, <https://ieeexplore-ieee-org.proxy.lib.odu.edu/document/10291030>

Project demos

* Caleb - EPA Automotive Trends
* Soujanya - COVID Tracking in the US
* Darin - MLB Spending and Playoff Success

You can view your classmates' projects and provide feedback or ask questions in the [Project Demo Discussion](https://canvas.odu.edu/courses/152933/discussion_topics/863553).

### Assignment

*no assignment*

### Resources

*no additional resources*
