---
title: Open Data, Challenges towards implementation, and possible solutions.
author:
- name: Ian Mulvany
  affiliation: eLife Sciences, Sage
  email: ian@mulvany.net
date: January 2014
abstract: Arguments in favour of Open Data in research are becoming overwhelming. There are calls a national [@RCKUOpen] and international levels [@Moedas2015, @RSOpen]. Here I will set out a working definition of Open Data and briefly discuss the key challenges preventing Open Data becoming standard practice. I will attempt to draw some general solutions from field specific examples.
---

# Open Data is ...
Open Data is Findable, Accessible, Interoperable and Reusable [@Wilkinson2016]. Making data available is key to support reproducibility, but by far the greatest benefit comes when data can be built upon, and in so doing can truly assist with the advancement of knowledge. In addition, one re-use of a data set effectively halves the cost per use of that data.

# How should we speak of the challenges for Open Data?
[@Goodman2014] lay out ten rules for the care and feeding of scientific data. Were all of these rules to be adhered to by all researchers, we would have as good an Open Data ecosystem as we could wish for. In this light then, let us look at what might be preventing us from adopting the key practices from these rules!

```
The 10 tips can be grouped by broader topics, and I think there may be a lot of value in
doing that.
```

# Sharing data, and why we don't.
This is an almost unwritten rule from [@Goodman2014] and that is to share your data. The general lack of willingness of researchers to do this is the greatest challenge. I will return to this point at the end of the paper, and consider it in the light of the other challenges discussed.

# Challenge: competence in working with data  

```
familiarity with tools and practices removes the fear of using those tools, and participating
in those practices. Good data management and husbandry becomes easier when we have a research community equipped to do a good job of data sharing.
```

## Rule 1. Love Your Data, and Help Others Love It, Too
[This rule](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003542#s2) talks about the need to create data that is well described and well documented. Where the data is available, it's usefulness is strongly hindered if no one other than the data creator knows how to use that data.  

A number of potential challenges stand in the way of making this happen. Keeping track of what the researcher did can be complicated. Some data is hyper-hetrogeneous, bringing together multi-varied data across many dimensions, in such a way that only the researcher who created that data set understands how to unpick it.

* use field specific standards where they exist
* where new formats are created, make them interoperable - OpenOMERO
* work on standardisation bodies - See W3C open Annotation group as a good example of this for the humanities
* Some data practices are specific, but the core practices are generic, and in the move from paper lab notebooks to digital data, we can take lessons from the software world
* ensure there is training in data management, support initiatives like Data Carpentry, Software Carpentry, point researchers towards online learning resources (e.g. data science courses), work on supporting a scientific data science online resource

## Rule 3. Conduct Science with a Particular Level of Reuse in Mind
The [thrid rule](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003542#s4)
researchers sometimes create entirely new data formats that are only of particular use in certain contexts

How do we deal with very large data? [@CERN-DATA]

### False privacy fears
Privacy concerns are real, but often the conversation gets dominated by this concern, where most data is not affected by this conversation.


### New tools create new data formats
Especially in microscopy (see OMERO as a solution to this)

## Rule 4. Publish Workflow as Context

### Heterogeneous data
A research question may need to pull together data from very different sources, and perhaps only the researcher understands how to combine the data



# Challenge: Infrastructure for openness [@Geoffrey2015]

```
intent for data sharing must be matched by infrastructural support
```


## Rule 2. Share your data online with a Permanent identifier
The data under the desk phenomenon is well known.

* Big data has a home, Astronomy, Particle Physics, Genomics  
* Highly specific data has a home  
* Hetrogenous "data under the desk" data have no natural home, but there are not options -- Figshare, Zenodo, DataDryad, Github
	* Challenge here is in making researchers aware of the existence of these resources, and encouraging them to use them.
* The greatest challenge is in large data with no natural home (large scale social science data), and data coming from fields whose technical capability is outstripping the level of experience of those fields for dealing with that data. Currently this is an acute problem in microscopy, and is becoming an increasing problem for conectomics [@Lichtman2014].
* [Registry of Research Data Repositories](http://www.re3data.org) lists over 1500 research data repositories. The journal Scientific Data also maintains a more [curated list](http://www.nature.com/sdata/policies/repositories).
* example subject specific repositories   
* Scientific data repository list   

### Data owned by corporations
Large data at google  and Facebook scale are owned by companies like google and Facebook. Work that builds on this data cannot be reproduced (this is an edge case).
s

## Rule 6. Publish Your Code (Even the small bits)

## Rule 8. Foster and use data repositories

* This also helps with data formats, as it requires standarsiation of your data

### Lack of infrastructure
needs to be dealt with on a subject by subject basis, also libraries may play a role in the future


# Challenge: The incentives for openness

```
without credit there will be no shift in culture
```

## Rule 5. Link Your Data to Your Publications as Often as Possible

## Rule 7. State How You Want to Get Credit

## Rule 9. Reward Colleagues Who Share Their Data Properly

### Lack of credit
This is the biggest problem, researcher led grants, and personal impact statements can help


# Challenge: The culture of Openness

```
If we achieve a cultural shift within a field, this question does not even exist,
the hardest, and most influential, changes are cultural ones
```

### Rule 10. Be a Booster for Data Science


## Some Solutions

* encourage high profile journals to advocate for open data
* require data management plans
* celebrate those who share well, create social pressure for data sharing

# Summary of solutions

```
to be completed 
```

---
