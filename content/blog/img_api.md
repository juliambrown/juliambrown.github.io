---
author: "Julia Brown"
title: "Colleting data from IMG"
date: 2023-01-20
description: "Wrangling JGI's API"
thumbnail: ""
keywords: ['DNA','Bioinformatics', 'Getting Data']
type: blog
---

I recently started a project with collaborators whose data was sequenced at JGI, and available through the IMG. Their project was stalled because they could not get all of the data they'd sequencenced from JGI downloaded onto our on-site servers for tailored bioinformatics analyses.

The scale of the project is not enormous given how much sequencing is done these days, 17 metagenomes, but they wanted to have both reads, assembled contigs and assembly QC information, such as read coverage profiles per contig.  This amounts to more than a terabyte of data... way too much to download to a local machine, so manual downloading was out of the question. 

IMG suggests using a globus endpoint for downloading data, but our institution does not have an Globus account. My colleagues were feeling frustrated and out of options.

More soon on how we solved this...