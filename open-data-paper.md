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

# Core Challenge One: Competence in Working with Data

This challenge is addressed by rules one, three and four:

- Rule 1. Love Your Data, and Help Others Love It, Too
- Rule 3. Conduct Science with a Particular Level of Reuse in Mind   
- Rule 4. Publish Workflow as Context  

Data that is well described and well documented and that follows good data format standards, is more likely to be interoperable with similar data. Such data is more useful than were it to follow these principles.

A number of potential issues stand in the way of making data of this quality.

- Basic researcher familiarity with good data practice is low  
- Keeping track of what the researcher did at the point of data capture can be complicated, requiring later reconstruction when tagging data    
- New scientific tools coming to market sometimes create proprietary data formats as output formats  
- researchers sometimes create custom data formats for their research (Figshare hosts over 100 distinct mimetypes)   
- Some data is heterogeneous, bringing together multi-varied data across many dimensions, in such a way that only the researcher who created that data set understands how to unpick it  

Most of these issues have all been successfully addressed in specific domains or communities.  

In order to imporve reseracher skillls with working with code, Software Carpentry has reached over 120,000 students [@wilson2016]. They conduct two day workshops instructing researchers on the basics of how to work with software. They have created a sister organisation whose aim is to do the same, but on the basics of data management - Data Carpentry. This is a ground-up effort that is being sustained by the good will of the communities within which these courses happen, and nicely demonstrates the appetite for improved skills amongst software and data intensive researchers.

Many fields have specific standards for data description, and these should be used where they exist. Most core disciplines have appropriate data repositories, but even in areas that are close, a lack of harmonisation of data standards can be an issue. Initiatives like the ISA TOOLs [@Sansone2012] initiative can help significantly with creating interoperable data standards in the life sciences, and this kind of data interoperability effort is a good example for other fields that are looking for similar interoperability.

With microscopy new microscopes have frequently created new data formats. To aid with instrument interoperability the microscopy community created the [OMERO](http://www.openmicroscopy.org/site/products/omero) framework, a set of standards and software tools, that supports interoperability across over 140 different image formats.

For keeping track of what happens at the point of data collection, creating smart tooling is an important advance. Also digital lab notebooks have a place to play in this. Google have created a digital lab notebook for the mass market with [Google Science Journal](https://makingscience.withgoogle.com/science-journal) and [Project Juypter](http://jupyter.org) offers a digital notebook that supports collaboration, computation, versioning and dissemination of scientific results. Tools can be configured to automatically annotate data at the point of data capture. [Rinocloud](https://rinocloud.com/) offers a service that can act as a digital hub bringing together data from multiple machines, into an auto-updated lab notebook.

Another route for creating compatible data is to make use of data standards bodies. The Open Annotation working group created a data format with a high degree of usage in the digital humanities, and ensured interoperability and openness of that data format through an open standardisation process that led the format becoming a World Wide Web Consortium standard.

Good data management practices is supported by good training and good community practice. Finding ways to introduce this training early ...

# Core Challenge Two: Appropriate Infrastructure for Open Data

This challenge is addressed by rules two, six, and eight:

- Rule 2. Share your data online with a Permanent identifier  
- Rule 5. Link Your Data to Your Publications as Often as Possible  
- Rule 6. Publish Your Code (Even the small bits)  
- Rule 8. Foster and use data repositories  

Data that has an identifier, a stable home, and is well curated is data is easily findable and accessible. This requires the existence of appropriate infrastructure [@Geoffrey2015] for that particular kind of data, be that technical infrastructure (for hosting and issuing of identifiers) or organisation and human infrastructure (for curation, annotation and preservation of the data).

It may be instructive to look at how high energy particle physics deals with it's data storage requirements. CERN [@CERN-DATA] outlines four levels of data preservation

1. retain only the publication that the data ended up generating  
2. preserve the data in a simplified format, this might be for outreach or training purposes
3. preserve the analysis software and specification of the data format
4. preserve the full reconstruction level data, and possibly some of the original data

It is understood that much of the primary data coming out of the detector will have to be discarded, and so their data preservation framework allows them to make decisions on what to keep based around the expected future uses of that kind of data.

It may be possible with emerging high resolution data sources to also find ways to make decisions around whether we can preserve certain artefacts that are of lower dimensionality of the original source data. For example in conectomics one begins with high resolution images of brain slices, and a full 3-D image of a brain can be on the order of petabytes of data, however the final network diagram showing the interconnection of the neuronal scaffolding of a brain will be many orders of magnitude smaller than the original images.

<!--  For bological samples, hightrougput sequencing  -->

Another issue to keep in mind about 70% of the lifetime cost is incurred on first write to disk, given the current rates at which the prices of long term data storage is dropping, so the question of which data sets do we need to make strategic decisions around will probably always be with us, but our view on the kind and size of what that data is will constantly be changing.  

In terms of numbers of data sets, most researchers producing data are not producing data at large scale. The questions around how they can create good identifiers for their data, and how they can find appropriate locations to deposit their data, are equally important as for those of large data.

For subject specific data there usually exists a subject specific repository. The [Registry of Research Data Repositories](http://www.re3data.org) lists over 1500 research data repositories. The journal Scientific Data also maintains a more [curated list](http://www.nature.com/sdata/policies/repositories).

For data that does not naturally find a home in one of these repositories there are also generic data repositories such as Figshare, Zenodo, DataDryad, Imeji and Github. Each of these will allow a researcher to post a public version of their data with an appropriate identifier. The main challenge here is in increasing awareness amongst researchers about the availability of tools like these.

There has been a growing interest in using peer to peer like systems for building data sharing infrastructures. Though not aimed at creating public repositories, tools like [dat data](http://dat-data.com) and [noms](https://github.com/attic-labs/noms) have the potential to significantly improve how researchers share and collaborate on data sets with each other.

There are two other infrastructure challenges that we might consider around data; privacy and ownership.

For any ...

Good infrastructure does exist for data in many domains of research (e.g. high energy physics, astronomy, genomics [@Benson2013, @Berman2000]), however there are emerging domains for whom lack of good infrastructure is becoming a critical problem (e.g. high throughput and resolution microscopy, conectomics [@Lichtman2014], computational social science). These domains share a common pattern where the tools used have reached new levels of sophistication and as a result data generation from these tools has expanded at a rate that is much faster than had been anticipated within their fields, leaving these fields in a momentary state of data crisis. A solution to these kinds of crises is to encourage the funding of data infrastructure, however whether this should be done on a project level, institution level, national level, or even international level remains an open and unresolved question. Building on many reports on the challenges of data infrastructure [@KnowledgeExchange2016] recommendations include taking into account the full research cycle when thinking about funding infrastructures, and to look to the US where the NSF has a dedicated program for the creation of shared [data-centric cyber infrastructure](http://www.nsf.gov/cise/aci/cif21/CIF21Vision2012current.pdf).

One last critical piece of infrastructure that is required for a healthy Open Data ecosystem is the ability to give credit to data. Within scholarly publishing this is done through enabling data citation. Over 2012 to 2015 a FORCE15 working group created the data citation principles ([@Altman2015]). All stakeholders in the scholarly enterprise should treat data as a first class citizen, and cite it appropriately. The standard XML used in scholarly publishing has also been updated to support data citation ([@mietchen2015]). Journals need to encourage good data citation practice, and need to ensure that data is acknowledged correctly. For example the open access journal [eLife](https://elifesciences.org) requires author list any novel data that they create in the course of writing their paper, along with giving credit to any previously published data that they used as part of their investigation.  


# Core Challenge Three: Creating a Supporting Culture for Openness

This is addressed by rules five, seven, nine and ten, and can be summarised by asking how we can ensure that the correct incentives are in place to support the sharing of open data.

- Rule 7. State How You Want to Get Credit  
- Rule 9. Reward Colleagues Who Share Their Data Properly  
- Rule 10. Be a Booster for Data Science  

Irrespective of how good data management skills are, or how sophisticated data hosting infrastructure is, unless there is a willingness on the part of the researcher to make their data open, then no data sharing will happen.

For the researcher they have to put time into making their data available, and they need to feel sure that this time would not be better used in helping their careers were they doing something else with that time, such as creating grant proposals, or working on new experiments. In some cases researchers may even have a misguided fear of sharing data in the belief that by do doing they will loose out on publishing potential results that they may have otherwise been able to obtain from the data set [@Sharing2016].

To overcome these fears researchers motivations to share data need to outweigh their misgivings towards data sharing.

There are two strategies that can be taken towards this. The first is to make data sharing mandatory in order to receive grants or to achieve publication. In so doing the researcher's search for the reward that they believe will benefit their career will require them to share their data, and we obtain an open data ecosystem by default. 

The second approach is to fairly reward data and software producers for their efforts on their own merits. This is more desirable, but significantly harder to do.

* require data management plans
* celebrate those who share well, create social pressure for data sharing  
* make data sharing mandatory, e.g. PLOS March 2014, Wellcome, Gates, Structural Biology.
* Change modes of assessment
* DORA  

# Summary of solutions



---
