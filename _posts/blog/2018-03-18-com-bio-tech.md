---
layout: post
title: "Three Technologies With a Future In Computational Biology"
excerpt: "An overview of three technologies poised to make big impacts on the field of computational biology."
categories: blog
tags: [Topic Review, Programming, Reproducible Research]
comments: true
share: true
date: 2018-03-18T17:15
---

## Introduction

Computational biology is an exciting and diverse sub-field of biology that includes designing algorithms, exploring the human genome, making sense of the human microbiome. Even outside "computational biology", all sorts of biologists are using computational approaches more and more, including performing analysis in R and processing data using custom Python scripts. At the heart of these computational applications are many powerful and wide-reaching technologies including programming languages (R and Python), code management tools (GitHub and BitBucket), and others. Because it's always good practice to strive for the best in all aspects of our research, I want to spend this post reviewing some very powerful and promising technological tools that are poised to make large positive impacts on computational biology, as well as the field of biology in general.

## 1. Docker

[Docker](https://www.docker.com) is a wildly popular computing platform that allows users to build specialized virtual environments ([containers](https://www.docker.com/what-container)) that run a program of interest, regardless of the operating system or permissions. Do you want to run a Linux-only program on a Windows machine? Docker allows for that by enabling you to run the program in a temporary Linux environment (the container). Want to run a program on your high performance compute cluster but don't want to deal with root access and system administrators? Go ahead and run it as a Docker container. Want to easily port your software with its associated reference databases? Containers can contain data in addition to the programs, so go ahead and include the reference in the same place.

<img src="https://tr4.cbsistatic.com/hub/i/r/2016/10/18/831f017c-ee68-4bd6-8a5c-ab31b4d35d6d/resize/770x/1cedcf2f03388a9720835a628a8a9765/dockerhero.jpg"  align="right" width="50%">

Essentially Docker provides researchers total control over the programs they are running by allowing them to run those programs in small virtual environments that they completely control. Because each container image is custom built on top of a bare-bones operating system like [Ubuntu](https://www.ubuntu.com), the processing is incredibly light-weight and efficient (unlike virtual machines). In addition to Docker, there is a server-friendly sister platform called [Singularity](http://singularity.lbl.gov), which provides an efficient and secure way to use Docker in a high performance computing environment.

I predict Docker is going to impact how we think about and conduct the computational processes around our biological research. A group of biologists have already started a project called BioContainers, which provides container images for many common biological analysis tools. Developers are continuing to make their programs available as Docker images as well, making usage as easy as typing `docker pull` instead of installing myriad dependencies and navigating permission issues. I expect to see this more and more in biological research, and you should definitely check it out. It could probably enhance your own research as well.

## 2. Julia

[Julia](https://julialang.org) has been an up-and-coming programming language over the years. Julia could be described as a powerful analytical language, similar in many ways to R and even Python. Julia is open source and offers simple syntax, insane speed and efficiency, a [notebook environment](https://github.com/JuliaLang/IJulia.jl) (Jupyter interactive environment), nice data visualization tools, and a growing set of resource packages. Its increased adoption in some pockets of machine learning and biological research, in addition to the other offerings, make it poised to become a go-to language for biologists in the near future. This is a language worth reading about and incorporating it into your own work.

<figure>
  <div style="vertical-align:middle; text-align:center">
  <img src="https://biojulia.net/Contributing/latest/assets/logo.png"  align="middle" width="50%">
  </div>
</figure>

## 3. Reproducible Documents

Us biologists have been observing an ever-growing enthusiasm for reproducible research, especially around the code we use in our published work. Every year more papers are publishing their code, and each year more journals are requiring code to be published with manuscripts. Not only does publishing code allow research results to be reproduced, but it also empowers others to implement similar analytical approaches. Apart from the altruistic enticements, reproducible code practices facilitate faster and more efficient research, increase confidence in the quality of the research, and provide cleaner work environments with less confusion.

This is really more of a theme than a technology, but it made the list because the unifying **Reproducible Research** "platform" coming out of the [Pat Schloss lab](http://www.riffomonas.org/reproducible_research/), [protocols.io](https://www.protocols.io), and others, is a technological resource that is ready to make a big impact on how biologists perform their research. I highly recommend checking this out and implementing some reproducible research practices in your projects.

## Conclusions

Docker, Julia, and the reproducible research platforms are not really new, but are all starting to improve the way computational and other biologists are doing their research. They are poised to make even larger impacts in the near future. These are technologies that are worth reading about, and even incorporating into research projects.

Did I leave something out, get something wrong, or do you have a question? Leave a comment below! I always love hearing from readers! And as always, thanks for reading!

