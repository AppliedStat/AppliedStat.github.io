---
permalink: /
title: "Welcome to Professor Park's Web"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Current Position
======
* Director of Applied Statistics Laboratory
* rofessor of Industrial Engineering at Pusan National University


Education
======
* Ph.D in Statistics, Pennsylvania State University
* M.S. in Mathematics, University of Texas at Austin
* B.S. in Mechanical Engineering, Seoul National University



Work Experience
======
* 2017 - 2019: Chair of [Industrial Engineering](ie.pusan.ac.kr) at [Pusan National University](pusan.ac.kr)

* 2015 - : [Full Professor](https://drive.google.com/file/d/0B-GVxDJZNtwYblN3NTFYakJHTXc/view) with tenure in [Department of Industrial Engineering](ie.pusan.ac.kr) at [Pusan National University](pusan.ac.kr)

* [CUSG Outstanding Professor](https://drive.google.com/open?id=0B-GVxDJZNtwYVG9jZDJJSGFNNU0)  recognized by Clemson University Student Government

* Assistant / Associate / [Tenure-granted Professor](https://drive.google.com/open?id=0B-GVxDJZNtwYUGg3ZjNGeHU5QTQ) of [Mathematical and Statistical Sciences](https://www.clemson.edu/science/departments/math-stat/) at [Clemson University](https://www.clemson.edu/) (2001-2015)


Biography
======
Chanseok Park was born and reared in Cheong Ju City (淸州市), South Korea.

After completing Yoido High School in Seoul, 
he started college as engineering student in the Department of Mechanical Engineering 
at Seoul National University and obtained a B.S. degree 
under the guidance of Late Professor Taik Sik Lee (南軒 李澤植) in February 1987. 
He then received his M.A. in Mathematics 
under the supervision of Professor Ayanendranath Basu 
from the University of Texas at Austin, 
and his Doctorate in Statistics 
under the supervision of Late Professor Bruce G. Lindsay from the Pennsylvania State University.

He is at present a tenured full professor of 
[Industrial Engineering](http://ie.pusan.ac.kr) at 
[Pusan National University](http://pusan.ac.kr)
(부산대학교 산업공학과), Busan, Republic of Korea (South Korea). 
He is also a Director of the 
[Applied Statistics Laboratory (응용통계연구실)](https://sites.google.com/view/appliedstatlab) 
in the department where he leads the applied statistics group, teaches statistics courses, and conducts various research on quality and reliability engineering, competing risks model, robust inference, solid mechanics, etc.  He also served from 2017 to 2019 as chair of the department at Pusan National University.

Before joining Pusan National University, he was a faculty member of Mathematical Sciences at Clemson University, Clemson SC, USA from 2001 to 2015. He was an assistant professor from August 15, 2001 until he was promoted to the tenured associate professor at Clemson University on August 15, 2007.

He has been on the editorial board of Journal of Probability and Statistics and International Journal of Quality Engineering and Technology. His research interests include engineering statistics, robust inference, reliability, competing risks model, statistical computing and simulation, acoustics, and solid mechanics.





A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a P Packages or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

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
