---
date: 2020-06-13T11:00:59-04:00
description: "A large scale network analysis of twitter data using PySpark Graphframe and AWS lambda"
featured_image: "/images/brett-jordan-ulRlAm1ITMU-unsplash.jpg"
tags: 
    - "Data Science"
    
title: "Who are the top Influencers that spread Misinformation about COVID on Twitter?"
---

How is misinformation about coronavirus spread on Twitter? In my research project, I aim to answer this question by taking advantages of large-scale computing tools such as PyWren and PySpark GraphFrames. The project can be broken down into two parts. The first part is collecting tweets using PyWren by mapping a scraper across a list of queries about misinformation. The second part of the project involves running large-scale network analysis of the retweet network of users who retweet misinformation using GraphFrames.

{{< figure src="/images/Picture2.png" >}}

[Link to Github Repository](https://github.com/VivianQian19/Twitter-Misinformation-Network)