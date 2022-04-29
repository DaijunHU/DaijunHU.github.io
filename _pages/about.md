---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a PhD student at the Department of Mechanical Engineering at National University of Singapore. Prior to joining NUS, I got Bachelor and Master degree at Beihang University. My research in NUS is to address the critical issues in metal additive manufacturing by computational modeling method, including residual stress, cracking, dislocation dynamics and so on. 

Reseearch interests
======
1. Additive manufacturing
2. Crystal plasticity
3. Fracture and fatigue
4. Residual stress

Publications
======
Daijun Hu, Nicolò Grilli, Lu Wang, Min Yang, Wentao Yan, [Microscale residual stresses in additively manufactured stainless steel: Computational simulation](https://www.sciencedirect.com/science/article/abs/pii/S0022509622000394), Journal of the Mechanics and Physics of Solids, Volume 161, 2022, 104822 

Daijun Hu, Yingchun Shan, Tian He, Xiandong Liu, Xiaofei Wan, [Research on simulation method of impact resistance of composite wheels made of long glass fiber reinforced thermoplastic introducing anisotropic property](https://www.sciencedirect.com/science/article/abs/pii/S026382231930354X), Composite Structures, Volume 223, 2019, 110965.

Daijun Hu, Yingchun Shan, Tian He, Xiandong Liu, [Analysis on effect of injection residual stress on impact resistance of composite wheel made of long glass fiber reinforced thermoplastic](https://www.tandfonline.com/doi/abs/10.1080/13588265.2020.1757583), International Journal of Crashworthiness 26 (5), 515-525

Nicolò Grilli, Daijun Hu, Yushu Dewen, Fan Chen, Wentao Yan, [Crystal plasticity model of residual stress in additive manufacturing using the element elimination and reactivation method](https://link.springer.com/article/10.1007/s00466-021-02116-z), Computational Mechanics, Volume 69, 825–845, 2022. 

Daijun Hu, Yingchun Shan, Xiandong Liu, Weihao Chai, Xiaoyin Wang, [Uncertainty optimization design of vehicle wheel made of long glass fiber reinforced thermoplastic](https://asmedigitalcollection.asme.org/IMECE/proceedings-abstract/IMECE2018/V013T05A062/276683), ASME International Mechanical Engineering Congress and Exposition 52187, 2018.

Yuting Liu, Daijun Hu, Xiandong Liu, Yingchun Shan, Hongzhou Lu, [An Analysis on the Limit of Lightweighting Existedin Automotive Structural Design](http://www.qichegongcheng.com/EN/10.19562/j.chinasae.qcgc.2019.08.006), Automotive Engineering, Volume 41 No.8, 2019.





Hobbies
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
