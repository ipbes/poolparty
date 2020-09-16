# Advanced definitions

## **Categorizing**

On the other hand, “**tags**” and “**categories**” are concepts that tend to have different meanings: it’s not so much what they are, or even how they are organized, but rather how they are used. **Categorizing** can also be called grouping or classifying. In using categories and tags for managing content, the challenge is to decide to what degree of classification to use the categories and to what degree to use the tags. PoolParty can also categorize contents by means of its categorization service or by using the add-on module Semantic Classifier that combines machine learning algorithms with semantic knowledge graphs. It should be said that, unfortunately, add-on module Semantic Classifier is not available under current UNEP's PoolParty license.

## **Auto-tagging**

**Auto-tagging** is a fuzzy expression often used with diverse connotation in different scenarios. Tagging refers not only to generate or extract tags from content but it can also be meant to “glue” the tags themselves to the content in order to attribute meaning and context to it; the prefix auto stands for automatic, i.e. somehow computer-assisted. In most of the cases, auto-tagging is employed in its first acceptation but, sometimes, the boundary between the two meanings is not very clear.

PoolParty, besides its text mining and extraction features that allow getting tags for content, also integrates into any Enterprise Information System \(EIS\), via APIs; so, in principle, obtained tags could be “glued” to the corresponding contents into the particular EIS, according to that EIS' rules. Moreover, PoolParty PowerTagging is a unified integration approach to semantically enrich EIS, that provide advanced search features inside those systems, with existing integrations for MS SharePoint and Drupal, among others; PoolParty bundle “Semantic Integrator” is a more general unified integration approach for connecting data from different sources, that provides a unified metadata layer based on semantic web standards, allowing to create integrated views over different data sources. It should be said that, unfortunately, neither PowerTagging nor Semantic Integrator options are available under current UNEP's PoolParty license, because they are at the core of PoolParty's semantic concept tagging solutions.

## **Indexing and auto-indexing**

**Indexing** is the process of producing an **index**; in turn, an index is a kind of target file \(, which has the function of providing access to information in or about some source contents by deriving symbols \(usually, words, numbers, etc.\) from the source contents or by assigning symbols about the source contents, thereby providing users access from a known order of symbols \(e.g. A-Z, chronologic, etc.\) to an unknown place of information. **Auto-indexing** is another vague expression that intrinsically involves the use of computers, but it always means to automatically generate/update an index through a computerized process.

## **Tagging vs. Indexing**

One important way in which **tagging** and **indexing** differ is that **tagging** involves any kind of designation about a piece of content, what it is or what it is about, whereas **indexing** is restricted to descriptive labels for what content is about. **Tagging** can include content type, date, creator, source, audience, location, rights, keywords, etc., whereas **indexing** is for the subjects of the content.  In this sense, **tagging** is sort of the modern word for cataloging or the assignment of metadata. To some extent, **tagging** and **indexing** might be essentially the same thing: if we are concerned with just the descriptive labeling of content and no other metadata, that might be called **tagging** or it might be called **indexing**; in this case, the difference is more nuanced, and to a certain extent it is historical.

## **Knowledge graph**

A **knowledge graph** is a model of a knowledge domain created by subject-matter experts with the help of intelligent machine learning algorithms. It provides a structure and common interface for all of your data and enables the creation of smart multilateral relations throughout your data repositories; structured as an additional virtual data layer, the knowledge graph lies on top of your existing databases, data sets, text documents, web pages, emails, SMS, voice calls, etc., to link all your data, structured or unstructured, together at scale. With a semantic knowledge graph, terms and strings are no longer used to build ambiguous metadata, instead, a semantic layer on top of all content and data assets works like a multi-dimensional index. A knowledge graph represents a domain on a metalevel and de­fines which metadata should be used to enrich available data repositories; it signi­ficantly increases data quality and allows to discover new insights due to extensively linked data.

A knowledge graph is a fabric of concepts, classes, properties, relationships and entities. Knowledge graphs typically cover multiple domains, various levels of granularity, data from multiple sources and various degrees of structure. It functions as background knowledge for various applications \(e.g. question answering, data integration and machine learning\). A knowledge graph is a highly efficient way of aligning back-end data management with smart end-user applications. A knowledge graph acquires and integrates information into a knowledge base \(e.g., an ontology\) and applies a reasoner \(reason or inference engine\) to derive new knowledge. The fluidity of the structure also allows for your knowledge graph to grow organically each time new data is introduced.

Knowledge graphs are crucial for PoolParty's functions that represent and store data and make them available in other applications effectively this way. Making data intelligent should be a priority for any organization. While many large organizations have teams of data scientists helping them ensure that they are getting intelligent data \(losing time and money re-creating knowledge that, in fact,  they already have\), PoolParty Semantic Suite provides a comprehensive platform with all of the tools required to create the most complete Knowledge Graph for your domain: starting from building up taxonomies and ontologies, to large-scale organization Knowledge Graphs that are generated with a mixture of text mining and machine learning algorithms. Implementing a Knowledge Graph in combination with AI and Machine Learning algorithms will help put context and rationale in data. This will enable you to not only discover deeper and more subtle patterns, but also to make decisions smarter and faster.

## **URI**

A **Uniform Resource Identifier** \(**URI**\) is a string of characters that unambiguously identifies a particular web resource. The most common form of URI is the **Uniform Resource Locator** \(**URL**\), frequently referred to informally as a web address. URI can be a name, locator, or both for an online resource, while a URL is just the locator. URLs are a subset of URIs. That means all URLs are URIs. It doesn't work the opposite way though. Not all URIs are URLs because a URI could be a name instead of a locator. In PoolParty, all resources \(projects, concept schemes, concepts, etc.\) are uniquely identified by URI.

The special thing about URIs is they are public identifiers. Everyone can use them and enrich own information with data through links to other data resources \(e.g. translations from GEMET, chemical information from CHEBI\) and participate in building the semantic web of data.

The technical challenge to an organization is to administrate stable, unique URIs. Vice versa, it is difficult to find linked data with stable URIs \(e.g. GEMET, ENVO, SDGIO\). Example: SDGIO \(Sustainable Development Goals Interface Ontology\) - The SDGIO aims to provide a semantic bridge between 1\) the Sustainable Development Goals, their targets, and indicators and 2\) the large array of entities they refer to. It will import classes from numerous existing ontologies and map to vocabularies such as GEMET to promote interoperability. New classes will be minted and defined where no external class exists.

The use cases for InforMEA providing thesauri with stable URIs are: 1\) Visualization of InforMEA resources \(potentially linked to within the semantic web\); and 2\) Re-use of InforMEA data resources in affiliated systems \(selected concepts of the LEO glossary can be used in GPE, Judicial Portal, EROL, as well as their translations, definitions, hierarchical/associative relations\).

## **SKOS**

[**SKOS**](https://www.w3.org/2004/02/skos/), \(stands for **Simple Knowledge Organization System**\), is an area of work developing specifications and standards to support the use of **knowledge organization systems** \(**KOS**\) such as thesauri, classification schemes, subject heading lists and taxonomies within the framework of the Semantic Web. In PoolParty, SKOS is used for representing relationships such as “broader”, “narrower” or “related”, or properties such as labels, definitions or scope notes for a concept.

## **RDF**

Knowledge graphs use knowledge representation formalisms as [RDF](http://www.w3.org/RDF/) \(Resource Description Framework\). In PoolParty context, following RDF model, concepts, its attributes or properties, and relationships between them are stored as a graph, where each concept is a node and edges represent properties and relations connecting these nodes in that graph. RDF paradigm uses URIs extensively.

Those MEAs more familiar with semantic technology will have their vocabulary already available in RDF, which is the most complete metadata file in context of thesaurus management. RDF is a pre-requisite of interoperability. InforMEA supports linked data by providing its thesauri in RDF.

* RDF is a framework for describing resources on the web
* RDF is designed to be read and understood by computers
* RDF is not designed for being displayed to people
* RDF is written in XML
* RDF is a part of the W3C's Semantic Web Activity
* RDF is a W3C Recommendation
* RDF query language is SPARQL, a semantic query language for databases, that is able to retrieve and manipulate data stored in RDF format.

In context of Poolparty, RDF contains thesaurus metadata such as related concepts, linkages between projects or to external linked open data resources \(e.g. DBpedia\), collection details \(e.g. the collection Agriculture and Land includes a selection of InforMEA thesaurus relevant for this topic\), and attributes relevant for auto-tagging.

## **SWC**

[**SWC**](https://www.w3.org/2004/02/skos/), \(stands for **Semantic Web Company**\), is a technology provider headquartered in Vienna \(Austria\) and is involved in international R&D projects, which continuously impact product development. It has been a pioneer in the Semantic Web for over a decade.  It is the leading provider of graph-based metadata, search, and analytic solutions and globally acknowledged as the leading and most innovative Linked Data technology provider. It is the company behind PoolParty Semantic Suite.

## **Semantic search**

**Semantic search** is, in a nutshell, “search with meaning”. This “meaning” can refer to various parts of the search process: understanding the query \(instead of just finding matches of its components in the data\), understanding the data \(instead of just searching it for such matches\), or representing knowledge in a way suitable for meaningful retrieval. PoolParty represents knowledge using knowledge graphs.

Identifying keywords is no longer enough; now, it is needed to understand what those keywords mean, provide rich information that contextualizes those keywords, and clearly understand searcher’s intent. Semantic text mining and indexing on the basis of knowledge models, and machine learning, are the basis for semantic search \(unless lexical search where the search engine looks for literal matches of the query words or variants of them, without understanding the overall meaning of the query\). Semantic search provides more meaningful search results by evaluating and understanding the search phrase and finding the most relevant results in a website, database or any other data repository.

## **Semantic indexing**

**Semantic indexing** is the process of generating a **semantic index**: an index constructed taking advantage of implicit high-order structure in the association of terms with documents \(a so-called “semantic structure”, i.e., a statistical correlation structure in the way in which individual words appear in documents; the adjective “semantic” implies only the fact that terms in a document may be taken as referents to the document itself or to its topic\). Semantic search uses semantic indexing.

## **Semantic Web and Linked Data**

**Semantic Web**, or **Web of Data**, is a web of data that can be processed or directly or indirectly by machines. The Semantic Web isn't just about putting data on the web. It is about making links, so that a person or machine can explore the web of data; with [**linked data**](http://linkeddata.org/), when you have some of it, you can find other, related, data. The development of the Semantic Web is a long-term project driven by the inventor of the World Wide Web Tim Berners-Lee and the W3C \(World Wide Web Consortium\). While much of the World Wide Web is made up of human-oriented texts, the Semantic Web is an attempt to provide information on the Web in a standard format that machines can easily process it to do useful things. In other words, the Semantic Web is the extension of the World Wide Web as a network of documents into a network of data, machine-readable, individual statements. Machine logical reasoning is intended to generate additional knowledge from this data. Foundation for linked data is interoperability through a standardization into **RDF**. On the other hand, [**Linked Data**](http://linkeddata.org/), a set of best practices for publishing and connecting structured data on the Web, provides the means to reach the goal of making grow the Semantic Web. In summary, [**Linked Data**](http://linkeddata.org/) is simply about using the Web to create typed links between data from different sources as diverse as databases maintained by two organizations in different geographical locations, or simply heterogeneous systems within one organization that, historically, have not easily interoperated at the data level. Technically, [**Linked Data**](http://linkeddata.org/) refers to data published on the Web in such a way that it is machine-readable, its meaning is explicitly defined, it is linked to other external data sets, and can in turn be linked to from external data sets. Like the web of hypertext, the web of data is constructed with documents on the web; however, unlike the web of hypertext, where links are relationships anchors in hypertext documents written in HTML, for data the links between arbitrary things described by the Resource Description Framework \(RDF\). Essentially, the Semantic Web marks a move from a global web of human-readable documents \(web pages\), to a global web of machine-readable documents; so that machines can automatically interpret the meaning of data on the web; what to do with it, and how to represent it.

## **PoolParty Linked Data**

PoolParty makes an extensive use of the concepts above, by allowing [publish **PoolParty projects as linked data**](https://help.poolparty.biz/pp/user-guide-for-knowledge-engineers/advanced-features/linked-data-management-overview/linked-data-and-custom-scheme-publishing-with-poolparty/publishing-poolparty-projects) to the Semantic Web and also [enriching concepts with additional facts from the Semantic Web](https://help.poolparty.biz/pp/user-guide-for-knowledge-engineers/advanced-features/linked-data-management-overview/linked-data-enrichment-with-poolparty/lookup-data-from-the-semantic-web).

### **Linked Open Data \(LOD\) Cloud**

Additionally, similar concepts published in the [**Linked Open Data \(LOD\) Cloud**](http://www.lod-cloud.net/) \(a project to bootstrap the Web of Data by identifying existing data sets that are available under open licenses, converting these to RDF according to the [Linked Data principles](http://linkeddata.org/), and publishing them on the Web\) can be linked into PoolParty projects. By default, there are available eight [**Linked Data Sources in PoolParty**](https://help.poolparty.biz/pp/user-guide-for-knowledge-engineers/advanced-features/linked-data-management-overview/linked-data-enrichment-with-poolparty/available-linked-data-sources-in-poolparty) from [LOD](http://www.lod-cloud.net/).

