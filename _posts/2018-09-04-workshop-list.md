---
title: Workshops for PySangamam 2018
author: PySangamam
layout: blog
permalink: /blog/2018/09/04/announcing-workshops/
categories: [Announcement]
tags: [announcement]
date: 2018-09-04
excerpt_separator: <!--more-->
active: blog
---

While the talks and posters are the main agenda of the conference. We
do realize people would like try things out hands-on, by interacting
with experts in the field. So, as part of PySangamam 2018, we have the
following workshops scheduled. 

1. Day 1, Afternoon: Computer Vision Through the Ages
2. Day 2, Forenoon: Concurrent Programming in Python
3. Day 2, Afternoon: Introduction to Pandas & Scaling Pandas for large Datasets

Each workshop can accomodate a maximum of 60 attendees. Attendees can
sign-up for the workshop, during the registration process on Day 1.
Also an attendee can take up only 1 workshop, this to ensure that
there is fair sharing of available seats.

#### **Workshop Details**

Detailed description of the workshop, and information about the
speakers are provided below.

<!--more-->

##### **1. Computer Vision Through the Ages**

**Time**

Day 1: 3:00 PM to 5:30 PM

**Pre-requisites**

  * Knowledge of basic probability
  * Vector algebra - vectors, matrices, matrix multiplication
  * Idea of convolutions would be a bonus, but not necessary

**Software Requirements**

  * Docker CE 16.0 and above

**Content Outline**

 1. What is computer vision?  (15 min)
    * Teaching computers to see. Difference from image processing.
    * Image and video representations in computers (pixels, colour spaces).
    * Why is computer vision hard?
    * Examples of different computer vision problems (detection,
    	 segmentation, shape from X, etc).
2. Computer Vision through the ages (30 min)
   * The generic pipeline (hand engineered feature approach).
   * Gradient Based Methods (HOG, HAAR).
   * Scale invariant Feature Matching Algorithms (SIFT and SURF).
   * Other tasks with classical Computer vision.
   * Issues with classical computer vision.
3. Rise of learning methods (15 min)
   * Youtube cats, training on CPUs.
   * SAIL - the era of GPUs.
   * In a nutshell, ML+ NN = DL.
   * Alexnet and the impact of Imagenet.
4. The Deep Learning Era in flow (45  min)
   * Introduction to Machine Learning, benefits of end-to-end solutions.
   * Using ML algorithms for Computer vision tasks (Hello world (MNIST with keras)).
   * Feed forward neural networks for MNIST classification.
   * Introduction to Convolutional Neural Networks (CNNs).
   * Using CNNs for Image Recognition .
5. Concept of Transfer Learning (30 min)
   * Why transfer learn; Less data? Not always a problem.
   * Concept of Bottlenecks.
   * A hands on example.
   * Practitioner advice; Closing comments.

Speaker: **Varun Sundar**

I'm python junkie by heart and passionate about using machine
intelligence to impact our surroundings. As a third year undergraduate
in the Indian Institute of Technology Madras, and as a part of the
Computer Vision and Intelligence group, I have been grateful to have
been a part of a lively peer group. When not scratching my head over
tensorflow's various confusing API's, I enjoy watching tennis and an
occasional trek.

Expertise on subject of the talk: Our blog articles may be found at
http://iitmcvg.github.io . We organise sessions on computer vision and
Deep learning regularly at IIT Madras. The repository for the same
(session content history) may be found here:
https://github.com/iitmcvg/Content.

Speaker: **Lokesh Kumar**

Lokesh is a 3rd-year student at IIT Madras. He currently co-heads the
CVI group, CFI. He uses Python for Computer Vision, Deep Learning, and
Language Analysis. In DeTect technologies, he has worked on automating
the chimney and stack inspections using Computer Vision and on
on-Board vision-based processing for drones. His interest in python
began during his stay at IIT Madras, from institute courses to CVI
projects like face recognition, hand gesture control of bots, etc.

##### **2. Concurrent Programming in Python**

This Python programming workshop provides insight on how to develop
concurrent programs on Python.
  
This workshop will focus on creating generators and co-routines using
Python 2 and Python 3 and also on the new `async` and `await` feature
introduced since Python 3.5.

**Time**

Day 2: 10:30 AM to 1:00 PM

**Pre-requisites**

  * Participants are expected to basic Python syntax and semantics.

**Software Requirements**

  * Python 3.6 and above

**Content Outline**

  - Concurrency Vs Parallelism: Choosing generator/coroutines Vs Threads/Processes
  - Introduction to generators
  - Generators as Iterables
  - Creating Generators using the `yield` statement
  - Co-routines
  - Examples:
      - Creating multitasking Greenlets using co-routines
      - Creating concurrent execution pipelines using co-routines
  - Creating co-routines in Python 3.5 using `async` definitions
  - Using `await` expressions
  - Realword examples of frameworks using concurrency patterns:
      - gunicorn
      - vibora
      - sanic
      - aiohttpd
      - gevent
      - twistedmatrix
      
  - Threads and Processes (*subject to time availability)
     - Multithreading using Thread class
     - All about Python GIL
     - Circumventing GIL limitations with `cython` and `numba`
     - Multiprocessing using Process class
     - Threads Vs Process: design choices and trade-offs

Speaker: **Chandrashekar Babu**

FOSS Technologist and corporate trainer, with 22+ years of technology
experience on Linux and other Free/Open Source Software (FOSS).

I am passionate about two things in life - to learn something new,
without any barrier; and then to train what I learn to others :-). I
spend a lot of time in learning new technologies, new trends and
devote a lot of time in front my computer - installing and playing
around with various free/open source software, toy operating systems,
learning new libraries, tools, programming languages and at times
reading articles, books and journals related to the same.

LinkedIn: [https://www.linkedin.com/in/chandrashekarbabu/](https://www.linkedin.com/in/chandrashekarbabu/)

##### **3. Introduction to Pandas & Scaling Pandas for large Datasets**

Pandas is a multi purpose data analytics tool which can be used for
simple, complex and time series aggregations. We have been using
pandas for all our data science and few of our data transformation
pieces for a long time now. We will teach the basics and advanced
aggregations with Pandas. We will also teach newer ways to scale
pandas for solving medium size data engineering problems.

**Time**

Day 2: 3:00 PM to 5:30 PM

**Pre-requisites**

    * Basic Python concepts

**Software Requirements**

    * Anaconda (Python 3.6)

**Content Outline**

1. Basics
   * Very quick introduction to pandas and jupyter notebook
   * Pandas Series
   * Pandas Dataframe
   * Reading multiple formats and creating
   * Simple dataframe operations
2. Aggregations & Advanced Indexing
   * Group bys in pandas world
   * Simple & complex aggregations
   * Pivots & multi indexes
3. Time Series 
   * Time series data introduction
   * Time series operations on dataframe
4. Visualization
   * Basic visualizations with dataframe
5. Optimizing & Scaling
   * Optimizing size of dataframe
   * Thinking in terms of vectorized operations
   * Introduction to Dask
   * Introduction to numba

This session is heavily inspired from [Alexander Hendorf's Data
Wrangling with pandas
session](https://github.com/alanderex/pydata-pandas-workshop).

Speaker: **Raghotham Sripadraj**

Raghotham Sripadraj is Principal Data Scientist at Treebo
Hotels. Previously, co founder and data scientist at Unnati Data
Labs. Drawing on his deep love for data science and his passion for
teaching, Raghotham has conducted workshops and given talks at a
number of data science conferences around the world. Apart from
getting his hands dirty with data, he loves traveling, pink floyd, and
masala dosas.

Speaker: **Jasjot Singh Mann**

Jasjot Singh Maan is a Data scientist at Treebo Hotels. He is mostly
found working on various datasets to draw insights for business.

Speaker: **Chaitanya Sangani**

Chaitanya Sangani is a Data Scientist at Treebo Hotels. Building data
products by the day, scraping data by the night.
