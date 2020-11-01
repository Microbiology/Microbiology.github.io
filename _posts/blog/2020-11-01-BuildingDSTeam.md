---
layout: post
title: "Five Key Considerations When Building A Data Science Team"
excerpt: "Building a data science team is hard. Here we explore what may lead to success."
categories: blog
tags: [Data Science, Strategy]
comments: true
share: true
date: 2020-11-01
---

## Introduction

At this point it's a familiar problem. Companies, organizations, and other groups have continued to grapple with how to extract more value from their data, and leveraging information more effectively. Here enters [data science](https://en.wikipedia.org/wiki/Data_science), the broad field dedicated to extracting information and insight from data using statistics, engineering, subject matter expertise, etc. The increasing availability of data and computing power has been a major driver for the field in recent years, and data science departments have continued to pop up in organizations and companies.

While most groups see value in data science, many have [struggled to extract a return on their data science investment](https://www.wired.com/story/companies-rushing-use-ai-few-see-payoff/). This has therefore continued to be an intense area of discussion and exploration across industries, with everyone trying to understand how data science can be more effectively used to create value. As a result, discussions have been moving away from general sentiments around "let's just hire some data scientists", to more strategic and informed actions. I have likewise been conversing and thinking around this fascinating challenge, and aim to organize some of those thoughts here (note that this is certainly not a complete list). In this post, we will explore what it takes to build and empower data science teams, and highlight some of the many resources available on this topic. Of course there are other important topics here, such as how we can effectively leverage an existing data science team, and what projects we should be focusing on, but we will focus on those in other posts.

## 1. Define "Data Scientist" Before Building

When having a discussion, it's often helpful to define our terms (ask Voltaire) and the data science space is no different. As many of us know, the terms "data science" and "data scientist" are often ambiguous. It seems as if you can ask ten people to define "data science" and get about ten different answers. In the context of building a data science team, it's therefore critical to define the data science skills, goals, and ambitions so that everyone can be united and work toward the same vision.

As the Harvard Business Review and others have articulated well, there are [many types of data scientists and data roles](https://hbr.org/2018/11/the-kinds-of-data-scientist), and it's important to understand who is required when building a data science team. We can ask ourselves whether the requirements are focused on statistics, engineering databases, engineering graphic user interfaces, software engineering, or  driving research that requires expertise in a subject matter (e.g. chemistry). Most often an effective team will require members of diverse backgrounds to work together, so the right combinations will be important.

![](../../../images/netlifx-ds-skill-examples.jpg)

*Example illustration for some different types of data science skill sets to consider when building a team. [Netflix source.](https://netflixtechblog.com/notebook-innovation-591ee3221233)*

## 2. Strategize Around Data Science Structure & Team Integration

In addition to thinking about the composition of the team, it's equally important to think about where they will be in the larger organization (university, company, or other type of group). I think Accenture does a nice job of presenting the [different options for implementing data science (what they call an analytics organization structure)](https://www.accenture.com/us-en/~/media/accenture/conversion-assets/dotcom/documents/global/pdf/industries_2/accenture-building-analytics-driven-organization.pdf). To simplify the landscape, these options offer varying degrees of coordination, flexibility, and resourcing. In an unappealing *decentralized model*, the resources will be allocated to parochial and potentially ineffective initiatives while in a more appealing *centralized*, *center of excellence*, or *federated model*, the teams can be more effectively aligned with organizational strategies while remaining flexible and collaborative. There are a lot of ways to draw out how our teams will fit into the bigger picture, and this is an important consideration with a lot of components, so we need to remember to spend some time on this.

![](../../../images/AccentureExamples.jpeg)

*Options for organizing data science teams within a larger organization. [Accenture source.](https://www.accenture.com/us-en/~/media/accenture/conversion-assets/dotcom/documents/global/pdf/industries_2/accenture-building-analytics-driven-organization.pdf)*

## 3. Invest in Organized & Accessible Data

The more obvious aspect of building a data science team is hiring people with relevant expertise, but ensuring they have the tools they need can be an after thought. I've had many conversations with people from various research groups/organizations that have experienced hiring data science teams, only to have them asking for proper infrastructure and data access. It's therefore critical to anticipate investing in, and supporting the needs of, data science teams which will include **computing infrastructure** and **access to data**.

This also ties into the point around team skills. For example, having some data engineers on a team can be really helpful for working through databasing problems and streamlining areas like statistics. Having managers to help with governance and compliance can also be helpful. Of course there is no one-size-fits-all formula, but spending some time thinking this through can really help a data science group thrive.

## 4. Establish A Collaborative Analysis Infrastructure

**Collaboration** and **transparency** are key to any scientific endeavor, including data science. This is especially true at an organizational level. It's important to think about how members of a data science team will share their results with each other, how they will share results outside of their group, and how they will evaluate the work of their teammates (e.g. code review). The Netflix data science folks articulate this well and [identify frameworks resources such as Jupyter Notebooks for facilitating transparency and collaboration](https://netflixtechblog.com/notebook-innovation-591ee3221233).

![](../../../images/netflix-example-scheme.jpg)

*Example flowchart for building an effective analytic platform to empower data science teams. This diagram includes the notebooking tools, compute platforms, sharing resources, and databases. [Netflix source.](https://netflixtechblog.com/notebook-innovation-591ee3221233)*

[Jupyter notebooks (similar to R Markdown and notebooks)](https://jupyter.org) are tools that allow analytical data scientists to incorporate *contextual language* (such as introductions or interpretations) with the *analytical code* (including rendered figures, tables, etc). This type of notebook environment can be integrated with coding tools like git, computing resources like AWS, organizational databases for each and reproducible data access, and notebook sharing tools (see the Netflix blog post for details). Integrating all of these tools together can really streamline the work of a data science team, sort of like providing a team of builders with power tools. Implementing a strong infrastructure goes a long way in ensuring the success of a data science team.

## 5. Be Agile & Keep Improving

As we have mentioned above, there is no one-size-fits-all solution to building an effective data science teams. That being said, there is one practice that can likely help improve the odds of successfully implementing a data science team (or probably any type of team), and that is to remain Agile. [Agile is a development philosophy](https://en.wikipedia.org/wiki/Agile_software_development) that encourages frequent feedback and improvements on projects. To remain Agile while building and maintaining a data science group means we should continue to get feedback from team members and collaborators, figure out what's working and what's not, and change course as needed. We can't be afraid to experiment and try new things, not just at the start but continually. If anything, this type of mindfulness will improve our odds at building a successful team.

## Conclusions

Many organization have been building out data science teams, and as mentioned above, they have been met with varying success. In this post, we explored what it might take to build a successful data science team, and we identified five key areas of consideration. Of course this is not a complete list, and there are many other important components to building successful data science teams. However a brief review of existing literature leads us to focusing on at least 1) defining data science roles, 2) strategizing on team integration, 3) investing in adequate resources, 4) building out a notebook analysis infrastructure, and 5) remaining Agile through the process.

As always, I definitely encourage interested reads to check out the linked material above, because we are only scratching the surface in this post. And of course, please let me know if you have any questions, comments, or concerns in the comment section below.

