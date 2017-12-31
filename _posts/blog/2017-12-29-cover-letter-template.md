---
layout: post
title: "How to Write Your Next Letter Using Markdown"
excerpt: "Focus on Your Letter Centent by Writing in Markdown and Converting to a PDF Using Pandoc."
categories: blog
tags: [Useful Resources, Pandoc, Markdown, Reproducibility]
comments: true
share: true
date: 2017-12-29T15:08
---

[Markdown](https://en.wikipedia.org/wiki/Markdown) and [RMarkdown](http://rmarkdown.rstudio.com) are great tools for writing scientific documents and manuscripts. Markdown is advantageous over platforms like Microsoft Word because it only uses a simple text file, it allows the writer to focus on content and not formatting, and it can be incorporated easily into reproducible science workflows (Markdown is a sort of code). My colleagues and myself have really enjoyed using Markdown in [our own work](https://github.com/SchlossLab/Hannigan_CRCVirome_mBio_2017), although the documents have primarily been research manuscripts. As I was preparing these types of manuscripts for submission to journals, I wanted to include a Markdown cover letter to accompany my Markdown manuscript. In this blog post I want to present the resulting cover letter Markdown template that I came up with and used.

I went through two steps to get the template together. The *first* was searching around and getting a base template on which I could build. This always makes the process of coding anything a lot faster and easier, although I unfortunately lost the original source, so I'm leaving out an important citation. The *second* step was re-writing portions of the [Latex](https://www.latex-project.org) template (the template used for formatting the Markdown file). I modified the template to be highly customizable within the Markdown file, without the need to further modify the complicated template code. I also included an executable shell script to automatically render the final PDF using Pandoc. The resulting PDF will include a header with author information and institute logo, the current data, a signature, and affiliation(s), all of which are easily specified in the Markdown text (remember to include back-slashes before special characters like parentheses). An example of the resulting document is included below, as well as the Markdown text used to create that document.

```markdown
---
size: 11pt
draft: no
head:
    address: '123 Research Ave, Science Building 2'
    city: Cambridge
    state: MA
    zip: 02114
    phone: '\(121\) 555-2234'
    fax: '\(999\) 555-6565'
    email: 'hannigan@gmail.com'
    dept: "Microbiology & Bioinformatics"
sig:
 include: yes
 sign: yes
 name: 'Geoffrey Hannigan, PhD'
 post: Bioinformatics Scientist
 secondpost: Distinguished Second Appointment
---

\today

To the editors of Science:

We submit for your review: "The role of the microbiome in health and disease"
by Geoffrey Hannigan and colleagues. We believe this work to be especially
well suited for publication in Science and highly relevant to a broader
scientific readership as well as the general public.

Our lab strives to set high standards of reproducibility and transparency,
while generating and publishing high quality data. As such, all analysis
work-flows, scripts, and datasets have been made publicly available for other
researchers to utilize.

The data presented in this manuscript are original and the manuscript is not
under consideration elsewhere. A preprint version of this manuscript has been
made available through BioRxiv.

We thank you for your consideration and look forward to your response.
```

<img src="../../../images/ExampleCL.png"  align="center" width="100%">

The resulting template is now available as a GitHub repository for anyone to use. You should be able to simply pull the repository, change the example files to meet your needs, and render the manuscript. I do rely a lot of user feedback with these things though, so if you find ways to make it easier to use, please let me know by creating an *issue* on the GitHub page. Additionally, please feel free to let me know what you think about this topic and blog post in the comment section below. Happy writing friends!

[**GO TO THE MARKDOWN REPOSITORY**](https://github.com/Microbiology/PandocAcademicCoverLetter)
