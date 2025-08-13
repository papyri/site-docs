# About papyri.info

## Prototype

Under leadership of Roger Bagnall and with funding from the [Andrew W. Mellon Foundation](http://www.mellon.org/) and the [National Endowment for the Humanities](http://www.neh.gov/), in  2006/07, [Columbia University Libraries](http://library.columbia.edu/) developed specifications for a 'Papyrological Navigator,' (PN) in order to demonstrate that multiple digital papyrological resources could be co-displayed in a scholarly web resource. In the following year a prototype PN was released. In 2007/08, with further support from the Mellon Foundation, a Duke-led team launched 'Integrating Digital Papyrology', whose three phases ran through 2012. The goals were to migrate the DDbDP from SGML to [TEI](http://www.tei-c.org/index.xml) [EpiDoc](http://sourceforge.net/p/epidoc/wiki/Home/) XML, and from betacode to Unicode; to map DDbDP texts and HGV metadata to corresponding APIS images and catalog records, and to convert both HGV and APIS data to EpiDoc; to enhance the Papyrological Navigator; to create a version controlled, transparent and auditable, multi-author, web-based, real-time, tag-lite, editing environment, which--in tandem with a new editorial infrastructure--would allow the entire community of papyrologists to take editorial control of core disciplinary data. In 2009 the new PN and Papyrological Editor (PE) were moved to [NYU's Institute for the Study of the Ancient World](http://isaw.nyu.edu/), which was the seat of production until July 2013.

## Release

In 2010 the new [papyri.info](http://papyri.info) was released to production (see [J. Sosin's presentation](http://www.stoa.org/archives/1263) to the 26th Intl Papyrological Congress), featuring the new PE and a completely redesigned PN.

## Stewardship

In July 2013 the [Duke University Libraries](http://library.duke.edu/), again with the generous support of the Mellon Foundation, launched the [Duke Collaboratory for Classics Computing](http://blogs.library.duke.edu/dcthree/) (DC3), a digital classics unit embedded in the Libraries. A core part of their mission is the maintenance and enhancement of the [papyri.info](http://papyri.info) toolset and community.

## Moving Parts

See the [top level data flow](https://github.com/papyri/documentation/blob/master/system_level/TopLevelDataFlow.md). The PN supports browse and faceted search of the constellation of papyri.info resources. It relies on an RDF triple store ([Apache Jena](http://jena.apache.org/)) to manage the relationships between documents from different sources and [Apache Solr](http://lucene.apache.org/solr/) for its search and faceting capabilities. The PE (1) allows users to add new or change existing 'publications' in the PN, edit the EpiDoc, either via database-style form (for APIS, HGV, BP) or proxy EpiDoc syntax called Leiden+ (for DDbDP), (2) enables submission of all such edits to peer review, which may result in commission of such to the canonical repository, and (3) provides transparent version-control (via git) of all such edits, system-wide. This bundle of services is referred to as Son of Suda on Line (SoSOL), in homage to the [Suda On Line](http://www.stoa.org/sol) project and our colleague [Ross Scaife](http://en.wikipedia.org/wiki/Ross_Scaife).
