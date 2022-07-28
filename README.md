# Hackathon_project

[[line1
line2]
https://github.com/TNMDCollaborationWeek/Challenges)](https://github.com/TNMDCollaborationWeek/Challenges

## Resources
https://www.youtube.com/watch?v=RGOj5yH7evk

https://www.youtube.com/watch?v=USjZcfj8yxE


## Git command line cheat sheet

Check git status

```git status```

To see differences with previous

```git diff```

To add a file to the staging area

```git add <filename>```

To stage a commit

```git commit -m "meaningful message about changes"```

To push to remote repo

```git push```


# Office for National Statistics (ONS)
## Git at the ONS
Although there doesn't appear to be official usage/guidelines for using Git/Github at the ONS, an introduction to Git course can be found on their [learning hub](https://learninghub.ons.gov.uk/course/view.php?id=532). As of late 2020, ONS machines are also able to connect to GitHub, and Git forms the basis of several version control platforms used in the ONS such as the ONS Gitlab platform. 

## Github at the ONS
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

### Use of git at DESTATIS (German Federal Statistical Office)

Can't speak for internal use within DESTATIS, but doesn't look like they have any public GitHub repositories. There are a few GitHub repositories (eg. Datenguide https://github.com/datenguide/datenguide) for using DESTATIS data. 

### Statistics New Zealand (StatsNZ)
https://github.com/StatisticsNZ

#### How are statistical or ML research organisations using public GitHub repositories?
* :coffee: create R pakckages for multiple purposes and for each project there are multiple contributors
    - each repository is a package which contains: a series of R scripts/functions in a folder; toy datasets; a showcase bio etc...
* :tea: store html files which are used in iframe on their website
    - e.g. The iteractive figure (iframe) in https://www.stats.govt.nz/experimental/covid-19-data-portal used the html files in [data_portal](https://github.com/StatisticsNZ/data_portal)
    
#### Are there guidelines for how GitHub is used by these organisations?
Pretty much everything StatsNZ posted on GitHub are covered by:
* :crown: Crown Copyright(c), Statistics New Zealand on behalf of the New Zealand Government
In addition, if those are R.packages, they are also under:
* :school: MIT License
* :rocket: [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)