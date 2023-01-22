---
author: "Julia Brown"
title: "Getting data: IMG"
date: 2023-01-20
description: "Wrangling IMG's API"
thumbnail: "/IMG_0625.jpeg"
keywords: ['DNA','Bioinformatics', 'Data acquisition']
type: blog
draft: false
---

I recently joined a project where progress was stalled because my collaborators were having trouble downloading their data from IMG, where it had been shared with them. 

IMG is a great resource for microbial genomics data. If you're looking to work with a large amount of data, downloading directly through their interface may not be possible. Download times are long, and data files are too big to be reasonably stored on a personal machine.

JGI's assembled a unified [genome portal](https://genome.jgi.doe.gov/portal/) for data downloads. To download large amounts of data directly to a storage server, there are two options as [outlined by IMG](https://genome.jgi.doe.gov/portal/help/download.jsf), are either to use a [Globus](https://www.globus.org/) endpoint for downloading data, or  their API. Globus requires a subscription, which we do not have at our institution. After a little bit of playing around and leaning into IMG's instructions, I was able to get everything we needed using the API.

All of the information required for using their API is available through their [API instructions](https://genome.jgi.doe.gov/portal/help/download.jsf#/api).

More soon on how we solved this...