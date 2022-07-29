# Hackathon_project

<!-- toc -->

- [Hackathon_project](#hackathon_project)
- [Challenge](#challenge)
- [Using Git](#using-git)
  - [Resources](#resources)
  - [Git command line cheat sheet](#git-command-line-cheat-sheet)
- [Office for National Statistics (ONS)](#office-for-national-statistics-ons)
  - [Git at the ONS](#git-at-the-ons)
  - [Github at the ONS](#github-at-the-ons)
- [Use of git at DESTATIS (German Federal Statistical Office)](#use-of-git-at-destatis-german-federal-statistical-office)
- [Statistics New Zealand (StatsNZ)](#statistics-new-zealand-statsnz)
  - [How are statistical or ML research organisations using public GitHub repositories?](#how-are-statistical-or-ml-research-organisations-using-public-github-repositories)
  - [Are there guidelines for how GitHub is used by these organisations?](#are-there-guidelines-for-how-github-is-used-by-these-organisations)

<!-- tocstop -->

# Challenge
[Totally Not MD Collaboration Week Challenges](https://github.com/TNMDCollaborationWeek/Challenges)

**Theme 1 & 4: What is GitHub? + Elegant documentation**

![i said git gif](images/i-said-git.gif)

* What are some tips on using git?
* How are other National Statistical Organisations (NSO) using GitHub?


# Using Git

## Resources

<https://www.youtube.com/watch?v=RGOj5yH7evk>

<https://www.youtube.com/watch?v=USjZcfj8yxE>

## Git command line cheat sheet

Check git status

`git status`

To see differences with previous

`git diff`

To add a file to the staging area

`git add <filename>`

To stage a commit

`git commit -m "meaningful message about changes"`

To push to remote repo

# How are other National Statistical Organisations (NSO) using GitHub?

## Use of Git at the Office for National Statistics (ONS)

### Git at the ONS

Although there doesn't appear to be official usage/guidelines for using Git/Github at the ONS, an introduction to Git course can be found on their [learning hub](https://learninghub.ons.gov.uk/course/view.php?id=532). As of late 2020, ONS machines are also able to connect to GitHub, and Git forms the basis of several version control platforms used in the ONS such as the ONS Gitlab platform. 

### Github at the ONS

The Office for National Statistics currently has several teams/divisions that use Git and Github. Some existing ONS Github organisations include:
* [Crime and Justice](https://github.com/ONS-centre-for-crime-and-justice)
* [Data Science Campus](https://github.com/datasciencecampus)
* [Big Data Team](https://github.com/ONSBigData)

The Centre for Crime and Justice (ONS) has recently collaborated using Git to automate analytical processes and produce *"Nature of crime"* statistical tables. The code used is also published on Github. You can read more about their [experiences using Git](https://gss.civilservice.gov.uk/blog/the-nature-of-rap/).

In general, ONS based programmers and developers are encouraged to open source the code behind their analysis and outputs.
>*"Make all new source code open and reusable, and publish it under appropriate licences. Or if this isn’t possible, provide a convincing explanation of why this can’t be done for specific subsets of the source code."*
>
> --- [Government Service Manual](https://www.gov.uk/service-manual/service-standard/point-12-make-new-source-code-open)

An [unofficial best practice guide](https://github.com/best-practice-and-impact/ons-github-post) for using Github describes the benefits of open source code for the ONS, security considerations when publishing code in the open, and providing an appropriate license alongside your code so users know how they can use, modify or redistribute your work.

## Use of Git at DESTATIS (German Federal Statistical Office)

Can't speak for internal use within DESTATIS, but doesn't look like they have any public GitHub repositories. There are a few GitHub repositories (eg. Datenguide https://github.com/datenguide/datenguide) for using DESTATIS data. 

## Use of Git at Statistics New Zealand (StatsNZ)
https://github.com/StatisticsNZ

Statistics NZ have 27 repositories on Github (albeit several empty ones). There are three general themes to their repositories:

1.  Publish code which links to available resources on their main website. E.g. They have utilised Github to publish code which was used to generate their software data portal (see [StatsNz](https://www.stats.govt.nz/experimental/covid-19-data-portal)).
2.  House code for functions they have developed to assist in their analysis or visualisation (usually in R).
3.  Share code they have used for data analysis on Statistics NZ data sets. In this case they only upload data if there is agreement from stakeholders. Otherwise they just include the methods and flag in the 'ReadMe' file that the data is partially available or unavailable.


# How are statistical or ML research organisations using public GitHub repositories?
* :coffee: create R pakckages for multiple purposes and for each project there are multiple contributors
    - each repository is a package which contains: a series of R scripts/functions in a folder; toy datasets; a showcase bio etc...
* :tea: store html files which are used in iframe on their website
    - e.g. The iteractive figure (iframe) in https://www.stats.govt.nz/experimental/covid-19-data-portal used the html files in [data_portal](https://github.com/StatisticsNZ/data_portal)
    
### Example-Vowpal Wabbit
It is a machine learning system which pushes the frontier of machine learning with techniques such as online, hashing, allreduce, reductions, learning2search, active, and interactive learning.

Their github page (https://github.com/VowpalWabbit/vowpal_wabbit) provides instructions for installing with a package manager, dependencies, building and tutorials. For example, you can find instructions for installing the package that builds Vowpal Wabbit locally for explicit use within python. There are also some examples of R code demonstarting the use of the package.

## UN BigData
To assist NSOs in taking full advantage of the big data wave, the United Nations Committee of Experts on Big Data and Data Science for Official Statistics (UN-CEBD) developed a cloud-service ecosystem (the United Nations Global Platform) in 2017, enabling international collaboration in data innovation. 

### Services
The [UNGP services](https://code.officialstatistics.org/unglobalplatform?sort=name_desc) available can be sorted into two buckets: Methods Services and Developer Services. 

Methods Service allows members of the platform to find, use and publish methods and algorithms in the cloud. It is a library of trusted statistical methods and algorithms, allowing (through the cloud native infrastructure and APIs) members of any international organisation to share and implement the same algorithms. 

Developer Service provides an environment for code developers to explore data, develop analytics and build applications securely. It provides Jupyterhub notebooks and GitLab workspaces over the web. It supports R, Python, Julia and more, and offers scalable ingestion of big data through parallel computing.

#### Regional Hubs for Big Data
There are [four physical hubs](https://unstats.un.org/bigdata/regional-hubs.cshtml) located in China, Rwanda, Brazil and the United Arab Emirates. These hubs have a number of goals including:

* :globe_with_meridians: Strengthening ties and promoting cooperation between producers of official statistics in the Region

* :raising_hand: Training and fostering the interest of young statisticians on the use of Big Data in Official Statistics

* :book: Supporting research on the use of Big Data and Data Science
Broadening the thematic scope of research on the use of Big Data in Official Statistics to gain experience in handling and processing this type of data; improving the accuracy and robustness of the results; developing protocols for incorporation of new data sources into the portfolio of Statistics Institutes in the Region.

* :airplane: Organizing and hosting seminars and conferences.
    
    
# Are there guidelines for how GitHub is used by these organisations?
Pretty much everything StatsNZ posted on GitHub are covered by:
* :crown: Crown Copyright(c), Statistics New Zealand on behalf of the New Zealand Government
In addition, if those are R.packages, they are also under:
* :school: MIT License
* :rocket: [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)


