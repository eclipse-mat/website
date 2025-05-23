---
title: "Memory Analyzer (MAT)"
date: 2025-01-10T10:00:00+02:00
#headline: "The Community for Open Innovation and Collaboration"
#tagline: "The Eclipse Foundation provides our global community of individuals and organizations with a mature, scalable, and business-friendly environment for open source software collaboration and innovation."
hide_page_title: true
#hide_sidebar: true
#hide_breadcrumb: true
#show_featured_story: true
layout: "single"
#links: [[href: "/projects/", text: "Projects"],[href: "/org/workinggroups/", text: "Working Group"],[href: "/membership/", text: "Members"],[href: "/org/value", text: "Business Value"]]
#container: "container-fluid"
---

# Memory Analyzer (MAT)

The Eclipse Memory Analyzer is a fast and feature-rich **Java heap analyzer** that helps you find memory leaks and reduce memory consumption.

Use the Memory Analyzer to analyze productive heap dumps with hundreds of millions of objects, quickly calculate the retained sizes of objects, see who is preventing the Garbage Collector from collecting objects, run a report to automatically extract leak suspects.

![MAT](images/mat_thumb.png)

## News

- 10 January 2025, **Memory Analyzer version 1.16.1 released**

    Memory Analyzer 1.16.1 Release is now available for [download]( {{< ref "download/" >}} ).
    This is a service release with a fix for one issue introduced with the 1.16.0 release - [Heapdump indexed on pre-1.16 fails to open on 1.16](https://github.com/eclipse-mat/mat/issues/89). We recommend using this version instead of 1.16.0 to avoid re-parsing already indexed heapdumps.

- 20 December 2024, **Memory Analyzer version 1.16.0 released**

    Memory Analyzer 1.16.0 Release is now available for [download]( {{< ref "download/" >}} ). Check the [New and Noteworthy](1.16.0/noteworthy.html) page for an overview of new features and fixes. 
- 8 May 2024, **Memory Analyzer moved to Github**

    The Memory Analyzer code repository has moved from the Eclipse Git servers to Github - https://github.com/eclipse-mat/mat.
    With this move, the project also switched from using the Eclipse Bugzilla to using Github Issues on the MAT Github project.
    We are really happy about the move, however, it might take some time to update all places pointing to the old repository at Eclipse. Please bear with us while we do the transition and give us feedback if you see places we've missed to update!
