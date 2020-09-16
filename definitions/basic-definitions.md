# Basic definitions

## **Concept**

A **concept** is a general notion or idea. It is not a word nor a definition, but a conception. Concepts in PoolParty are designated by labels

## **Label**

A **label** is a descriptive word or phrase. A concept may be designated by several different labels that are considered as synonymous. Usually, for each language considered, one of these labels designating the same concept is chosen as the **preferred label**; the others play the role of **alternative labels** or even **hidden labels** \(for further internal use in PoolParty\).

## **Tag**

A **tag** is a descriptive word or phrase applied to a person, group, etc., as a label or identifier assigned to content. In the PoolParty context, the difference between a label and a tag is more related to how and where they are used: a label is used in connection with designating a PoolParty **concept**, while a tag is attached as a keyword to blog posts, news releases, unstructured documents, web pages or any other content, grouped under some content management system \(like M-Files or DotNetNuke\) in order to make it easier to find, use or understand.

## **Controlled vocabulary**

A **controlled vocabulary** is a carefully selected list of words and phrases, which are used to tag units of information \(document or work\) so that they may be more easily retrieved by a search. Controlled vocabularies reduce ambiguity inherent in normal human languages where the same concept can be given different names and ensure consistency. A controlled vocabulary ensures that the same words and phrases are used for content annotation by different users in a collaborative environment. Taxonomies, thesauri and ontologies are types of controlled vocabularies.

## **Taxonomy**

A **taxonomy** is a classification of things or concepts, including the principles that underlie such classification; it is a hierarchical structure or order of terminologies of a knowledge subject. It is one of the simplest variants of controlled vocabulary as it contains only denominations that are organized into a hierarchical structure.

## **Thesaurus**

A **thesaurus** is a taxonomy with added non-hierarchical relationships between concepts and other properties to each concept. It is a controlled and structured vocabulary in which concepts are represented by labels, organized so that relationships between concepts are made explicit.

## **Ontology**

An **ontology** encompasses a representation, formal naming and definition of the categories, properties and relations between the concepts, data and entities that substantiate one, many or all domains of discourse. Most ontologies describe individuals \(instances or objects\), classes \(sets, collections, concepts, classes in programming, types of objects or kinds of things\), attributes \(aspects, properties, features, characteristics or parameters that individuals and classes can have\) and relations \(ways in which classes and individuals can be related to one another\); they also can include function phrases \(complex structures formed from certain relations that can be used in place of a single phrase in a statement \), restrictions \(formally stated descriptions of what must be true in order for some assertion to be accepted as input\), rules \(statements in the form of an if-then or antecedent-consequent sentence that describe the logical inferences that can be drawn from an assertion in a particular form\), axioms \(assertions, including rules, in a logical form that together comprise the overall theory that the ontology describes in its domain of application\) and events \(the changing of attributes or relations\). PoolParty developers considered that thesauri hit the sweet spot between expressive semantics and ease of handling, hence it has been designed to be a tool that makes creating and maintaining them straightforward.

## **Project**

A **PoolParty project** is a container used to hold one or more concept schemes \(thesauri\). The [PoolParty's graphical user interface](https://help.poolparty.biz/pp7/poolparty-quick-start-guide/overview-of-the-poolparty-gui) shows the project level at the top of the [Hierarchy Tree](https://help.poolparty.biz/pp/poolparty-overview/poolparty-s-ui/poolparty-s-hierarchy-tree).

## **Concept Scheme**

A **concept scheme**, in PoolParty is at the highest level in the project’s taxonomy, under the project level in the [Hierarchy Tree](https://help.poolparty.biz/pp/poolparty-overview/poolparty-s-ui/poolparty-s-hierarchy-tree) \(**color-coded in purple**\). In PoolParty, concept schemes are equated with thesauri.

## **Top Concept**

A **top concept** is a concept at the highest level, under a concept scheme or thesaurus in the [Hierarchy Tree](https://help.poolparty.biz/pp/poolparty-overview/poolparty-s-ui/poolparty-s-hierarchy-tree) \(**color-coded in dark green**\). Other concepts are placed at several levels under a top concept level in the [Hierarchy Tree](https://help.poolparty.biz/pp/poolparty-overview/poolparty-s-ui/poolparty-s-hierarchy-tree).

## **Translation Lists**

A **translation list**  contains all concepts that do not have a preferred label in the respective language.

## **Collections**

PoolParty offers the possibility to group concepts as unordered lists of concepts \(skos: Collections\) or ordered lists of concepts \(swc: OrderedCollection\).

## **Relation**

In the PoolParty context, **relations** can be resulting \(and should\) be added between concept schemes or concepts. There are different types of relations: **hierarchical relations** and **associative relations**. **Hierarchical relations** stand for parent/child relationships, i.e., broader/narrower relationships; **associative relations** refer to symmetric relationships that state that two concepts are related in some sense.

## **Mapping**

A relation is classified as a **semantic relation** or as a **mapping** **relation** depending on the location of respective related items. Semantic relations \(shortened as **relations**\) are said of those established between concepts belonging to the same concept scheme or thesaurus, while mapping relations \(shortened as **mappings**\) involve concepts from foreign concept schemes or [linked data](http://linkeddata.org/). In the PoolParty's jargon, the semantic relations are the so-called **Broader Concepts** \(parent concepts\) / **Narrower Concepts** \(child concepts\) hierarchical relations and the **Related** associative relations; the mapping relations are named in an analogous manner just adding the adjective "matching":  the **Broader Matching Concepts** / **Narrower Matching Concepts** hierarchical relations and the two \(instead of only one kind\) **Exact Matching Concepts** / **Close Matching Concepts** associative relations.

## **Corpus**

In linguistics, a **corpus** \(plural corpora\) or **text corpus** is a set of texts \(i.e. different documents in PDF, Word, etc.\), related to project’s knowledge domain, that is used in PoolParty to do statistical analysis, checking occurrences and extracting words and phrases, which then are matched against the concepts in the thesaurus in order to extend or refining it. In PoolParty, you can have several corpora in the same project.

## **Term**

A **term**, in PoolParty context, is a word or phrase resulting from text mining in corpus analysis that doesn’t match any existing concept label in the thesaurus. A term can become a concept by adding it to your taxonomy. The quality of extracted terms depends strongly on the [quality](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/advanced-features/corpus-management-overview/analyse-documents-in-your-document-corpus/corpus-quality) of provided corpora.

## **Tagging**

**Tagging** is a process of labelling information \(attaching a **tag**\) made to support resource discovery for users; this can be done in a manual or an automatically \(computer-assisted\) way. Tags tend to be a brief label indicating what something is about; they can be very specific or relatively broad. \(Information professionals might prefer to call them “index terms”\). PoolParty can propose tags for labelling automatically via text mining, but it doesn’t mean necessarily that those tags are actually assigned to that text \(as could be the case of a Word document tag or, for instance, a text document into a particular content management system like Drupal or M-Files\).

