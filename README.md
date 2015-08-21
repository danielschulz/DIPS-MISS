# DIPS-MISS

Is an approach for Analytics projects of any kind. Is is deisgned to guide teams on any experience level through
Big Data projects.

DIPS stands for Data Insights Project Stencil. It includes MISS-Card, which stands for Management, Inputs, Solution,
&amp; Scoring Card. Both of techniques support the successful completion of analytics projects. It is designed to cover

1. ”classic" reporting and BI projects
2. as well as Advanced Analytics
    1. Exploratory Data Analysis (EDA) and
    2. Machine Learning (ML) projects.

DIPS was designed to unify the established world of reports with the upcoming needs in Big Data projects. DIPS is
inspired by well-established techniques from Data Mining to grow up an approach to handle Data Science projects of any
kind and complexity.


## DIPS Components


### General

DIPS = {``MISS Card``, ``DIPS Overview``, ``DIPS Timeline``}

Business challenge &#8594; Project String &#8594; Project Overview with Phases &#8594; Project Timeline &#8594; specific technical
tasks

MISS Card is subject to any DIPS project, regardless of Project String.


1. To use DIPS in a project environment, the C-level executives fill out with MISS Card. This determines the ``Project
String``, so what to do, only.

2. Based on this Project String, the task at hand, the upcoming project lead supports the C-levels filling out the MISS
Card. This card will be the basis for usually upcoming questions regarding the project. Filling this out in advance
makes sure in the operational execution of the project there is very little input needed by the Top Management because
every key aspect of the project will be handed out right on the first day.

3. In the operational execution this MISS Card together with the DIPS Project String is the first go-to address for any
questions, that may come up. The DIPS Project String defines the order of execution for novices and a checklist for
experienced Data Scientists. The MISS Card contains specific information regarding this exact project, like data
sources, the destination for data/models, due date, and what platform to use.


***


### (1) DIPS Overview

DIPS Overview basically is the three Project Strings &mdash; one String for each kind of data-related project.


#### (1.1) Project Strings

There are three Project Strings: ``Report``, ``Exploratory Data Analysis``, and ``Machine Learning``. Each of the
Strings serves a clearly defined purpose. The 'right' String depends on the business challenge or question alone.


#### (1.2) DIPS Phases

Any string has exactly four Phases,
where the first is always ``Initialize``, second comes ``Transform``, third is always dependent on the Project String,
and forth is always ``Completion``. The third Phase is always the same name, the Project String has.


**String Report**

![Report String: DIPS Overview with four Phases](https://github.com/danielschulz/DIPS-MISS/blob/master/images/Report-String-DIPS-Overview-Phases.png)


**String Exploratory Data Analysis**

![Exploratory Data Analysis String: DIPS Overview with four Phases](https://github.com/danielschulz/DIPS-MISS/blob/master/images/EDA-String-DIPS-Overview-Phases.png)


**String Machine Learning**

![Machine Learning String: DIPS Overview with four Phases](https://github.com/danielschulz/DIPS-MISS/blob/master/images/ML-String-DIPS-Overview-Phases.png)


The first Phase is always the same, even from the ordered tasks to do. The following three Phases are distinct from one
another, whereas there maybe parallels in ``Exploratory Data Analysis`` and ``Machine Learning``, which stems from
their nature.


### (2) MISS Card

MISS Card stands for Management, Inputs, Solution, & Scoring Card. The management and project lead define some key
aspects here, like data sources, the destination for data/models, due date, whom to report to, and what platform to
use.

This card is designed to contain specific aspects for this exact project. Team members and developers use it whenever a
question comes up first. As the most common questions are covered here, chances are the project has fewer delay as
the time from question to answer can be reduced.

![Any String: MISS Card](https://github.com/danielschulz/DIPS-MISS/blob/master/images/Any-String-MISS_CARD.png)

From top to bottom:

1. Management

This card's section is divided into three columns: one for each Project String. Your current Project String defines
the column to fill and so the values to gather. There will usually be two columns which you may ignore. Only, iff you
are doing a project with broad scope or you are doing a follow-up project, there maybe more than one column of interest
to you. Mostly, exactly one column is what you need.


2. Inputs

Here the project lead, Data Scientists and the business stakeholders define what data to use. Those maybe
pre-processed, value-added, annotated, anonymized, etc. to meet law, business, and technological requirements. This
card's section defines the data source and destination for data & models from this endeavor.

3. Solution & Scoring

This card's section is devided into two for one reason: you may decide for a technological solution first. This is
appropriate when, maybe you platform is defined to be Cassandra or there is only an Enterprise Data Hub, Hadoop.
Then you may start out filling in the fixed values and end up with a resulting Scoring for runtime performance,
scalability and quality of visualizations.

The other way is to start out with the latter three: you may define your Scoring, like high runtime performance,
high scalability and best quality of visualizations. Then you end up deriving therefrom the technological platform,
developers, and Frameworks to use.

So these Solution & Scoring parts are strongly bonded to each other. Defining one fixes the other. So here it is
recommended to define either what is important to your project or what you already know. The other column's values will
be a result of the first filled column's values then.


### (3) DIPS Timeline

The Timeline now is defined by the Project String only. You work your way though it first from left to right and then
top to bottom. This defines the order of your tasks, that is in general the most appropriate. Please keep in mind, that
specific constraints in your project and arrangements in your company may override the general order. Please feel free
to re-arrange, add, and remove accordingly to your specific needs.

DIPS Timeline gives an ordered guide line what tasks to do. Together with your MISS Card a developer can work almost
autonomously and report the state of their work to the project lead efficiently. As there are always four Phases a
rough estimate of the allover project state for management reports is possible to derive, as well.

**Report Timeline**

![Reporting String: DIPS Timeline with four Phases](https://github.com/danielschulz/DIPS-MISS/blob/master/images/Report-String-DIPS-Timeline.png)


**EDA Timeline**

![Exploratory Data Analysis String: DIPS Timeline with four Phases](https://github.com/danielschulz/DIPS-MISS/blob/master/images/EDA-String-DIPS-Timeline.png)


**Machine Learning Timeline**

![Machine Learning String: DIPS Timeline with four Phases](https://github.com/danielschulz/DIPS-MISS/blob/master/images/ML-String-DIPS-Timeline.png)


Why is it, that in all three Phases either
  - ``Initialization`` Phases end with finding appropriate data sources and
  - ``Transform`` Phases start with the same thing?

The answer is pretty simple: ``Initialization`` Phase is done by the project leader and developers effectively read the
Codebook. ``Transform`` Phase is meant for the developers to work on and the project leader just monitoring from here
on. As finding an appropriate data source spares lots of time, both project leader and developers are meant to watch
out for them. This is little effort with much return iff successful. So this is redundant, as in projects sometimes no
practical data governance is established. So either one maybe more aware of pre-processed data, therefore.


***

## Typical Use Cases

1. **Can I use DIPS to monitor Key Performance Indicators (KPI)?**
    * examples are
        * what are my top-selling products?,
        * how much profit does each department achieve?,
        * what is the average load of my warehouse?
    * Yes, you can. ``Report`` Project String is the right choice for that. This is classical BI questions. Iff there
    are approaches fitting your IT Architecture or data better, consider using them when DIPS is too general for that.
    Otherwise DIPS gives you a guide line for that either. The reason BI questions maybe more appropriate to solve
    without DIPS is, that the reason for DIPS was the lack of clear approaches to do EDA and ML projects. As BI
    questions are common projects, there maybe something fitting your needs better than DIPS.


2. **Can I apply DIPS when there is no specific problem I can see, no KPIs to derive, etc.?**
    * You want to become Data-driven and pro-actively resolve challenges before they grow up to problems. On the one
    hand there is no need to act, but you want to gain a deeper understanding of your business and be sure potential
    risks are managed right when they come up.
    * Yes, you can. The ``EDA``Project String was designed for just that. A Data Scientist will apply various models,
    trying to isolate specific instances. There maybe pattern, that you need to be aware of. This could be anything
    from a virus in your computer network, mechanical parts with low quality ending up to enlarge the operational risk
    and maintenance costs, or methods intended to increase your productivity working in the opposite direction.


3. **I know the problem, but there is no straight-forward answer. Is DIPS applicable?**
    * There is a ver specific problem, but no easy answer. You have the feeling that a Data Scientist at least could
    track the problem and maybe limit or isolate it.
    * You can use DIPS therefore. The ``Machine Learning`` String was made just for this. A Data Scientist will look
    for patterns, like in the ``EDA`` String, maybe do an ``EDA`` beforehand, and may come up with a magic solution.

***


## How to apply

### Use of the 3 components

| Order no. | Stakeholders                          | Step                                                                                                                              |
|:---------:|:-------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------|
| 1         | Strategic Management                  | Determine business need and derive project kind from DIPS overview: <ul><li>Report</li><li>EDA</li><li>Machine Learning</li></ul> |
| 2         | Strategic Management, Project lead    | Management & project lead fill out MISS Card to determine key points of project                                                   |
| 3         | Project lead & members                | <ul><li>Take MISS Card to look up key points and </li><li>Take DIPS timeline to work through the project</li></ul>                |


### Measure progress

The progress of a project is measured by the current ``Phase`` it is in. As in all 3 ``Project Strings`` there are
exactly 4 ``Phases``, progress is quiet comparable. As a rough measure the workload distribution is about 1:2:3:1
for Phases ``Initialize``, ``Transform``, the Project String specific Phase, and ``Completion``.

| Project String                                                                                                    | Workload in percent   | Dominant roles    |
|:------------------------------------------------------------------------------------------------------------------|:---------------------:|:-----------------:|
| Initialize                                                                                                        | 15%                   | Project leader    |
| Transform                                                                                                         | 30%                   | Developers        |
| Project String specific Phase <ul><li>Report</li><li>Exploratory Data Analysis</li><li>Machine Learning</li></ul> | 40%                   | Developers        |
| Completion                                                                                                        | 15%                   | Project leader    |


The first and the last Phase is were the project leader has most of the work to do. In the second and third Phase the
Developers do and the project leader is mostly monitoring their progress.

***


## Overview of abbreviations

| Abbreviation  | Long form                                 | Public Abbr.  |
|:------------- |:------------------------------------------|:-------------:|
| BI            | Business Intelligence                     | Public        |
| DIPS          | Data Insights Project Stencil             |               |
| DSPS          | Data Science Project Stencil              |               |
| EDA           | Exploratory Data Analysis                 | Public        |
| KPI           | Key Performance Indicator                 | Public        |
| MISS          | Management, Inputs, Solution, & Scoring   |               |
| ML            | Machine Learning                          | Public        |


***


DIPS and MISS have come a long way: since it's invention, it has been reviewed, optimized, and applied in several
projects. With this publication we like you to test it in your company. You may modify this stencil to your needs as
well.

For any feedback to us and hints what to improve we are more than thankful.


***


### History

It was invented because there was no project approach for Advanced Analytics projects. DIPS was invented independently
using experience and knowledge from colleagues. Later, it turned out there are natural parallels to Crisp DM. A
comparison and the relation of the two are the subject of the upcoming section.

### Parallels to Crisp DM

DIPS can be seen as similar to
[Crisp DM](https://en.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining). DIPS is easier to follow for
inexperienced project members as it is closer to a step-by-step guide than Crisp DM. DIPS therefore also covers
specific ``Project Strings``, ``Report``, ``Exploratory Data Analysis``, and ``Machine Learning``, to fulfil the
expectations of being a helpful guide for projects. While Crisp DM has the same layout and projects were to evolve the
same in either model, ``MISS Card`` and ``DIPS Timeline`` make it easy to begin a Data Science project with fewer
experience because to process is thought-through. So team members can concentrate on techniques and Statistics.
``DIPS Overview`` for ``Report``, ``String`` is what is closest to Crisp DM. So mathematically expressed
Crisp DM &sub; DIPS. Crisp DM is very suitable for experienced teams or having a rough overview, e.g. for management
reports.


### Names

DIPS (Data *Insights* Project Stencil) is also known as DSPS (Data *Science* Project Stencil). MISS Card (Management,
Inputs, Solution, & Scoring) is a means to collect key information in one place.


### Acknowledgements

Icons on graphics are taken as is from the [Twitter Bootstrap](http://getbootstrap.com)
icon package. A big thank you to the guys at [Twitter](http://getbootstrap.com).

Developed at [Belvine University](http://university.belvine.com). Applied in projects at
[msg systems ag](http://www.msg-systems.com) and [Belvine Consulting](http://belvine.com).

&copy; 2010-2015, Daniel Schulz
