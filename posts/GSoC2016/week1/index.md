---
title: Google Summer of Code 2016: Week 1
date: 2016-04-24
published: true
author: Abhishek Singh
mathjax: on
tags: GSoC 2016, Peragro AT, AIRS,
---

As per the proposal, this week was dedicated for requirements gathering. I had a meeting with sueastside just before the starting of this week where we discussed on few details of the project. Later had a quick chat with Botanic on #peragro (irc) about
Vector Space Model implementation (VSM) using elastic search. 

Work done during this week includes:

* Understanding the requirement for the project clearly.
* Setting up test standarads
* Coming up with test specifications to test deployed product
* Learned more about elastic search and Kibana
* Creation of dataset
* Explored Essential toolkit by musicbrainz community

After a disscussion on #peragro channel we agreed to use `Essentia` toolkit as a feature extractor for our AIR system.
It gives both low level and high level feature descriptors for audio. More information about the music descriptor returned by essentia can be found [here](http://essentia.upf.edu/documentation/streaming_extractor_music.html#music-descriptors)

AcousticBrainz is another good resource to get both low level and high level descriptors of music. It is also open source. During the initial phase I will be using the descritors from the `AcousticBrainz` for building VSM system using elastic search.
On top of that search api(s) will be written. In this way there will be something to demonstrate at the end of each phase. Later, essentia toolkit will be integrated in the system for extracting feature. Extracted features will be feed to the elasticsearch
for indexing.
