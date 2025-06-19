---
permalink: /
title: "Brif Bio:"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a computational and theoretical physicist, specializing in soft matter physics and biophysics, with extensive experience in developing analytical models, multiscale simulation methodologies, and deep learning approaches to investigate complex phenomena in soft and biological systems. My research focuses on the physics of phase transitions, emergent behavior in disordered soft systems, and the mechanics of interfaces and confined systems. I study a range of problems, including liquid-liquid phase separation in viscoelastic and elastic media, aging dynamics of biomolecular condensates, polymer gels, wetting phenomena in industrial formulations, and the structural and rheological behavior of intrinsically disordered proteins through multiscale MD and deep generative modeling.

My work combines coarse-grained molecular dynamics, continuum and field-theoretic modeling, and statistical mechanics with deep learning techniques. I develop and implement scalable algorithms for simulating and analyzing interfacial and mesoscopic dynamics, with a particular emphasis on tracking evolving morphologies, characterizing pattern formation, and parameterizing physical models based on free energy functionals. I have also explored fluctuation-driven shape dynamics in lipid tubules and polymer confinement in complex geometries.

Beyond research, I am passionate about scientific communication and mentoring. I have actively contributed to teaching during my PhD, currently mentor junior researchers, and maintain open-access tutorial repositories on GitHub. I am committed to collaborative research, mentoring, and advancing computational tools for the soft matter and biophysics community. 

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
