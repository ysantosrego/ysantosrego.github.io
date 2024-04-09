---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a _maranhense_ mathematician hailing from Upaon-Açu, an island in northeastern Brazil. 
Currently, I am a Lecturer at the University of Lincoln, where I am a member of the [Charlotte Scott Research Centre in Algebra](https://algebra-lincoln.org/). 

Prior to joining the [School of Mathematics and Physics](https://www.lincoln.ac.uk/smp/) here in Lincoln, I was a _wissenschaftlicher Mitarbeiter_ in the group of [Petra Schwer](https://www.geometry.ovgu.de/) at the Otto-von-Guericke-Universität Magdeburg. I got my PhD from the Universität Bielefeld, advised by [Kai-Uwe Bux](https://www.math.uni-bielefeld.de/~bux/). Before that I got my Master's degree from the Universidade Estadual de Campinas (Unicamp) supervised by [Dessislava Kochloukova](https://www.ime.unicamp.br/~desi/), and my Bachelor degree from the Universidade de Brasília (UnB). In Brasília I was also a member of the groups [PETMat-UnB](https://mat.unb.br/pet/) and [Theory of Computation](https://mat.unb.br/~ayala/TCgroup/index.html) under the guidance of [Mauro Rabelo](https://mat.unb.br/index.php/pessoas/docentes/52-mauro-luiz-rabelo) and [Maurício Ayala-Rincón](http://www.mat.unb.br/ayala/), respectively. 

Research interests
======
I am an algebraist by training and a topologist/geometer in spirit, which means I work in group theory. That is, my research concerns properties of spaces and of their symmetries (such as [reflections](https://www.mathsisfun.com/geometry/symmetry-reflection.html)). The fun part is that the term "space" can be interpreted quite broadly, from a [hairy ball](https://www.jstor.org/stable/2320587?origin=crossref&seq=2#metadata_info_tab_contents) to a comic-book-like multiverse known as [Bruhat--Tits building](https://hal.science/file/index/docid/94363/filename/_04a5_Euclidean_buildings_Grenoble_.pdf), from fundamental [geometric shapes](https://mathworld.wolfram.com/PlatonicSolid.html) to model spaces describing the [motion of a robot](https://www.ensta-bretagne.fr/jaulin/paper_cameleon.pdf).

In this area one can investigate a wide variety of problems. For example, regarding the space we could ask whether there exist serious obstructions in it (such as holes of various dimensions), whether it is curved somehow, what happens when we move "forever" (e.g., "periodically" or "towards infinity"), or whether we can describe what happens over time with an object moving in the given space under certain rules.

As for the symmetries themselves, we might want to know for instance how many there are, whether we can describe them in a simple fashion, how they transform objects in the given space, whether there are points left unchanged by the symmetries, or about the relationship between given sets of symmetries of (not necessarily distinct) spaces.

In more technical terms, my work (so far) lies in combinatorial/geometric group theory and related topics from topology. I have particular interest in cohomological and topological finiteness conditions, Reidemeister classes, and algorithmic questions. As such, I am very fond of geometric, topological, cohomological, combinatorial, and algorithmic aspects of groups and spaces on which they act.

Groups that I like include (but are not limited to) linear groups (algebraic and Lie groups, their (S-)arithmetic counterparts, Coxeter groups, ...), R. Thompson's groups and their relatives, and locally compact (including profinite) groups. In the topological realm I also enjoy things like [knots and links](https://www.ams.org/publications/journals/notices/201705/rnoti-p461.pdf) (and more generally spatial graphs) and questions about low-dimensional spaces.

As a former member of the group of Theory of Compuation in Brasília, I am also interested in formal methods in mathematics and proof assistants. From time to time I am also puzzled by Costas arrays.


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
