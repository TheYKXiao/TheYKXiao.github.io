---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am **Yongkang Xiao**, a Ph.D. candidate in **Health Informatics** at the University of Minnesota. My research focuses on **large language models, AI agents, graph learning, knowledge graphs, and biomedical AI**.

I am broadly interested in building intelligent systems that can reason over complex information, retrieve useful evidence, and generate reliable answers. My recent work explores **agentic reasoning**, **graph-structured memory**, and **long-context multi-hop question answering**, with the goal of helping language models move beyond passive text generation toward more grounded and interpretable reasoning.

Before my Ph.D., I received my M.S. degree in **Computer Science** from the University of Minnesota and my B.Eng. degree in **Chemical Engineering** from Tianjin University. My interdisciplinary background motivates my interest in developing AI methods for real-world scientific and healthcare applications.

Research interests
======

My research lies at the intersection of **natural language processing**, **machine learning**, **data mining**, and **biomedical informatics**. I am especially interested in the following topics:

- Large language models and AI agents
- Retrieval-augmented generation and long-context reasoning
- Graph-structured memory for agentic systems
- Knowledge graphs and graph neural networks
- Biomedical NLP and healthcare AI
- Link prediction and reasoning over biomedical knowledge graphs

Current research
------

My current research focuses on building AI agents with structured memory for complex reasoning tasks. In particular, I am working on methods that convert long documents into reusable graph-structured memory, where factual evidence is organized as typed triples with provenance information. At inference time, an agent can actively plan reasoning steps, retrieve relevant evidence chains, and generate grounded answers.

This line of work is motivated by a simple question: **how can we make language-model-based agents reason more reliably over long and complex contexts?**

Rather than treating long-context question answering as a single-pass generation problem, I am interested in decomposing it into memory construction, reasoning planning, evidence retrieval, and answer generation. This framework connects ideas from retrieval-augmented generation, knowledge graphs, multi-hop reasoning, and agentic AI.

Previous work
======

I have also worked on **biomedical knowledge graphs** and **graph neural networks**. My previous research studied how to improve link prediction in biomedical knowledge graphs by combining graph structure, textual representations from language models, and domain knowledge from biomedical ontologies.

More broadly, I am interested in methods that integrate **structured knowledge** and **language representations**. I believe this direction is important for building AI systems that are not only accurate, but also more interpretable, controllable, and useful in scientific domains.

Background
======

I am a Ph.D. candidate in Health Informatics at the University of Minnesota. I also received my M.S. degree in Computer Science from the University of Minnesota.

Before coming to Minnesota, I completed my undergraduate study in Chemical Engineering at Tianjin University. This background gives me a broad perspective across AI, computing, biomedical research, and engineering applications.

Skills and tools
------

I primarily work with **Python**, **PyTorch**, **Transformers**, **graph learning frameworks**, and modern LLM toolchains. I also have experience with knowledge graph construction, graph neural networks, retrieval systems, and large-scale experimental pipelines.

My research and development experience includes:

- LLM-based agents and reasoning pipelines
- Retrieval-augmented generation systems
- Knowledge graph construction and representation learning
- Graph neural networks for link prediction
- Biomedical data mining and NLP
- Model training, evaluation, and experimental analysis

Contact
======

I am always happy to discuss research ideas, collaborations, and opportunities related to AI agents, language models, knowledge graphs, and biomedical AI. Please feel free to reach out by email.

<!-- ---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
