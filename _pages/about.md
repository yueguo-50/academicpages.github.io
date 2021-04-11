---
permalink: /
title: "Hi there!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to Yue Guo (郭月)'s webpage! I am a seconed year Ph.D. student in [Biomedical and Health Informatics Department](http://bime.uw.edu) at [the University of Washignton](https://www.washington.edu), advised by Prof. [Trevor Cohen](http://bime.uw.edu/faculty/trevor-cohen/). I am particularly interested in **Natural Language Processing** and **Machine Learning** in medical domain.

Before coming to UW, I was a postdoctoral researcher of the Department of Radiation Oncology and Molecular Radiation Sciences at Johns Hopkins University [School of Medicine](https://www.hopkinsmedicine.org/som/), supervised by [Todd McNutt](https://www.hopkinsmedicine.org/profiles/details/todd-mcnutt). I received my Master of Health Science (MHS) from [the Johns Hopkins Bloomberg School of Public Health](https://www.jhsph.edu), majoring in cancer Epidemiology. I got Bachelor of Medicine, Bachelor of Surgery (M.B.B.S) degree from [ Capital Medical University](http://www.ccmu.edu.cn).

Publications
======
Automated Lay Language Summarization of Biomedical Scientific Reviews.
Yue Guo, Wei Qiu, Yizhong Wang, Trevor Cohen.
In Proceeding of AAAI conference in Artificial Intelligence, 2021
<i class="fas fa-play-circle"></i>
[<i class="fab fa-twitter-square"></i>](https://homes.cs.washington.edu/~hapeng/)
<i class="fab fa-github"></i>
<i class="fa fa-fw fa-rss-square"></i>
<i class="fab fa-bitbucket"></i>

<i class="fab anticon-file-pdf"></i>
sd

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
