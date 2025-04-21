---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm a first year master student in Computer Science from [Columbia Engineering](https://www.engineering.columbia.edu/). I am very fortunate to be supervised by [Prof. Hod Lipson](https://www.hodlipson.com/) in [Creative Machines Lab](https://www.creativemachineslab.com/) from [Columbia University](https://www.columbia.edu/). Also, I am supervised by [Dr. Hao Wang](https://intellisys.haow.us/haowang/) in [Intellisys Lab](https://intellisys.haow.us/) from [Stevens Institute of Technology](https://www.stevens.edu/). 

My research interests include Trustworthy ML, Explanable AI and Computer Vision.

**I am looking for a PhD position in Fall 2026!!**


## 📚 Publications
### POLAR: Policy-based Layerwise Reinforcement Method for Stealthy Backdoor Attacks in Federated Learning  

**Kuai Yu**, Xiaoyu Wu, Peishen Yan, Yang Hua, Hao Wang, Tao Song, Linshan Jiang, Haibing Guan  

*Submitted to ICCV 2025, Under Review*  

We propose **POLAR**, a reinforcement learning-based method that formulates layer-wise selection for efficient and stealthy backdoor attacks in federated learning. POLAR dynamically adapts to defenses and balances attack success rate with stealthiness.

---

### W3FedPOSE: A Practical WEB3.0-Based Federated Learning Framework with Privacy, Ownership, Security, and Efficiency  

Peishen Yan, **Kuai Yu**, Yaozhi Zhang, Yulin Sun, Shuang Liang, Yang Hua, Tao Song, Linshan Jiang, Ningxin Hu, Mohammad Reza Haghighat, Bingsheng He, Haibing Guan  

*Submitted to The Web Conference 2024*  

We present **W3FedPOSE**, a practical federated learning framework that integrates Web3.0 technologies. It leverages blockchain and smart contracts for secure data ownership and access control, while introducing an explainable, incentive-driven algorithm for efficient and trustworthy collaboration.


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
