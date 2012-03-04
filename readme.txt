=== Enhanced Publication ===
Contributors: zuotian, tatum.cc
Tags: academic, res-comms, semantic web, rdf, surf
Requires at least: 3.3
Tested up to: 3.3
Stable tag: 1.0

Convert your WordPress site into an enhanced publication.

== Description ==

The primary function of the Enhanced Publication plugin is to describe a WordPress site as an OAI-ORE aggregated publication (an enhanced publication).
In this structure, we convert WordPress pages into book chapters and use various other plugins to facilitate and describe reference lists, authors and editors, and attachments.
You can access the aggregation rdf at `http://yoursite/feed/aggregation-rdf/`.

For visualizing the content object relationships, we employ [SURF](http://surffoundation.nl)'s
[InContext Visualiser](http://wiki.surffoundation.nl/display/vp/4.3+'InContext'+Visualiser).

This combination of Web site and publication objects was not readily compatible with any single ontology.
We therefore selected a list of related ontologies to describe the full content of the aggregation.
For example, the following list of ontologies were used in creating a new ontology that includes objects such as a single book chapter,
among other chapters in an edited volume, as a published text with multiple authors, an abstract, figures, and a reference list.

* RDF: Resource Description Framework Ontology;
* OAI-ORE Vocabulary for Resource Aggregation;
* DCTerms: Dublin Core Metadata Ontology;
* FOAF: Friend of a Friend Ontology;
* FRBR: Functional Requirements for Bibliographic Records Ontology;
* SWAN: Provenance, Authoring and Versioning in scientific discourse Ontology;
* RES: Academic Researchers Ontology;
* BiRO: Bibliographic Reference Ontology;
* FaBiO: FRBR-aligned Bibliographic Ontology;
* PRISM: Publishing Requirements for Industry Standard Metadata Ontology;
* ESCAPE-Display: Vocabulary for describing inverse relationship of FOAF.


= Enhanced Bibliplug =
Though not required, we recommend that you use this plugin with [Enhanced bibliplug](http://wordpress.org/extend/plugins/enhanced-bibliplug/)
for reference management to enrich your chapter content.

= CoAuthors Plus =
[CoAuthors Plus](http://wordpress.org/extend/plugins/co-authors-plus/) is a great plug to manage multiple authors for a single post
(which, in our case, a single chapter). This plugin takes advantage of CoAuthors Plus, and we encourage you use them together.

= Included packages =
[semsol-arc2](http://arc.semsol.org/ "semsol-arc2") version 2011-12-1 for RDF serialization.
[InContext Visualiser](http://wiki.surffoundation.nl/display/vp/4.3+'InContext'+Visualiser) verion 1.1 for RDF visualization.


== Installation ==

= Install =

1. Extract `enhanced-publication.zip` files and upload `enhanced-publication` folder to the `/wp-content/plugins/` directory. Or, you can install the plugin using WordPress "Install Plugins" admin interface.
2. Activate the plugin through the 'Plugins' menu in WordPress.

= Setup =

1. Go to Settings -> Enhanced Publication -> Visualization, and follow the instruction to set up the InContext visualization.
2. Start adding chapters to your site, and watch your visualization grow.

Note: you may need to clear brower cache if you don't see your changes showing up in the visualization.

You are done!

== Screenshots ==
1. Visualization
2. Settings page


== Changelog ==

= 1.0 =
Initial release.