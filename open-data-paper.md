---
title: Open Data, Challenges towards implementation, and possible solutions.
author:
- name: Ian Mulvany
  affiliation: eLife Sciences, Sage
  email: ian@mulvany.net
date: January 2014
abstract: Calls in favour of Open Data in research are becoming overwhelming. They are at national [@RCKUOpen] and international levels [@Moedas2015, @RSOpen]. I will set out a working definition of Open Data and will discuss the key challenges preventing publication of Open Data becoming standard practice. I will attempt to draw some general solutions to those challenges from field specific examples.
---

# Open Data is ...
Open Data is Findable, Accessible, Interoperable and Reusable [@Wilkinson2016]. Making data available is key to support reproducibility, but by far the greatest benefit comes when data can be built upon, and in so doing can truly assist with the advancement of knowledge. In addition, one re-use of a data set effectively doubles the utility of that dataset.

# How should we speak of the challenges for Open Data?
[@Goodman2014] lay out ten rules for the care and feeding of scientific data. Were all of these rules to be adhered to by all researchers, we would have as good an Open Data ecosystem as we could wish for. Let us look at what might be preventing us from adopting the key practices from these rules! To streamline the discussion I have grouped the ten rules into three core challenges.

# Core Challenge One: competence in working with data

This challenge is addressed by rules one, three and four:

- Rule 1. Love Your Data, and Help Others Love It, Too
- Rule 3. Conduct Science with a Particular Level of Reuse in Mind   
- Rule 4. Publish Workflow as Context  

Data that is well described and well documented and that follows good data format standards, is more likely to be interoperable with similar data. Such data is more useful than were it to follow these principles.

A number of potential issues stand in the way of making data of this quality.

- Basic researcher familiarity with good data practice is low, and unfit tools are used  
- Keeping track of what the researcher did at the point of data capture can be complicated, requiring later reconstruction when tagging data    
- New scientific tools coming to market sometimes create proprietary data formats as output formats  
- researchers sometimes create custom data formats for their research (Figshare hosts over 100 distinct mimetypes)
- Some data is hyper-hetrogeneous, bringing together multi-varied data across many dimensions, in such a way that only the researcher who created that data set understands how to unpick it  

Most of these issues have all been successfully addressed in specific domains or communities.  

Software Carpentry has reached over 120,000 students [@wilson2016]. They conduct two day workshops instructing researchers on the basics of how to work with software. They have created a sister organisation whose aim is to do the same, but on the basics of data management.

Use field specific standards where they exist. Most core disciplines have well described data formats, and appropriate data repositories, but even in areas that are close, a lack of harmonisation of data standards can be an issue. Initiatives like the ISA TOOLs initiative can help significantly with creating interoperable data standards in the life sciences.

With microscopy new microscopes have frequently created new data formats. To aid with instrument interoperability the microscopy community created the [OMERO](http://www.openmicroscopy.org/site/products/omero) framework, a set of standards and software tools, that supports interoperability across over 140 different image formats.

For keeping track of what happens at the point of data collection, creating smart tooling is an important advance. Also digital lab notebooks have a place to play in this. Google have created a digital lab notebook for the mass market with [Google Science Journal](https://makingscience.withgoogle.com/science-journal) and [Project Juypter](http://jupyter.org) offers a digital notebook that supports collaboration, computation, versioning and dissemination of scientific results.

Another route for creating compatible data is to follow data standards bodies. The Open Annotation working group created a data format with a high degree of usage in the digital humanities, and ensured interoperability and openness of that data format through an open standardisation process that led the format becoming a W3C standard.

# Core Challenge two: A lack of infrastructure for openness

This challenge is addressded by questions two, six, and eight:

- Rule 2. Share your data online with a Permanent identifier  
- Rule 6. Publish Your Code (Even the small bits)  
- Rule 8. Foster and use data repositories  

 [@Geoffrey2015]

 - Some data is too large to share easily  
 - Some data is not publiclally availalbe

How do we deal with very large data? [@CERN-DATA]

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


* This also helps with data formats, as it requires standarsiation of your data

### Lack of infrastructure
needs to be dealt with on a subject by subject basis, also libraries may play a role in the future



# Core Challenge Three: Creating a supporting culture for openness

This is addressed by rules five, seven, nine and ten, and can be summarised by asking how we can ensure that the correct incentives are in place to support the sharing of open data.

- Rule 5. Link Your Data to Your Publications as Often as Possible  
- Rule 7. State How You Want to Get Credit  
- Rule 9. Reward Colleagues Who Share Their Data Properly  
- Rule 10. Be a Booster for Data Science  

## Some Solutions

* encourage high profile journals to advocate for open data
* require data management plans
* celebrate those who share well, create social pressure for data sharing  
* make data sharing mandatory PLOS March 2014.

# Summary of solutions



---
