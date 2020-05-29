---
layout: page
title: Projects
subtitle: Things I worked on
---

### Genomics Annotation Services

A fully operational software-as-a-service for genomics analysis served on AWS. 
[Demo](https://www.youtube.com/watch?v=k2kOfwSWX8w)

The software consists of multiple components, including a web app (an interface for users to upload files and check job status), an annotation service (a process by which a sequenced genome sample is analyzed to identify the location of genes and all of the coding regions in a genome, and determine what those genes do), and several utility programs such as notifying users via email when jobs are done, archiving files for free users from s3 to glacier, and restoring files for free users once they subscribe to become premium users. Utilized load balancers and auto-scalers for scaling purposes and performed load testing using Locust and simple scripts. 
