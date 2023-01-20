---
author: "Julia Brown"
title: "How do I get the data: IMG"
date: 2023-01-20
description: "Wrangling IMG's API"
thumbnail: ""
keywords: ['DNA','Bioinformatics', 'Getting Data']
type: blog
---

I recently started a project with collaborators whose data was sequenced at JGI, and available through the IMG. Their project was stalled because they could not get all of the data they'd sequencenced from JGI downloaded onto on site storage for tailored bioinformatics analyses.

The scale of the project was not enormous given how much sequencing is done these days, 17 metagenomes, but they wanted to have both reads, assembled contigs and assembly QC information, such as read coverage profiles per contig (.sam files). This amounted to more than a terabyte of data... way too much to download to a local machine, so manual downloading was out of the question. Given the way that IMG's interface is set up, and the amount of time it takes to download large files such as fastq data, local downloads would've taken forever.

IMG suggests using a [Globus](https://www.globus.org/) endpoint for downloading data, but our institution does not have an Globus account. My colleagues were feeling frustrated and out of options.

More soon on how we solved this...