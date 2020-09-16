# General suggestions and recommendations

  
Make the correct use of test and production servers. The test server is intended to be used for staging projects, while the production server hosts projects that should not be modified in that context.

Don’t work in parallel in two related projects without the minimum workflow coordination.

Since in PoolParty, all resources \(projects, concept schemes, concepts, etc.\) are uniquely identified by URIs, it is crucial providing projects with well-formed and stable URIs to accomplish the aims depicted in the Introduction. Nonetheless, because of their instability while on the test server, don’t invest much time in URIs until the project is going to be in production. Please refer to information management experts within your organization to discuss [URI pattern and configuration and discuss options available in Poolparty](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/basic-features/uri-management-overview/advanced-uri-settings).

Being certain of having included in a corpus a set of contents representative of your knowledge domain, and having reached a [green status after the corresponding corpus analysis](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/advanced-features/corpus-management-overview/analyse-documents-in-your-document-corpus/corpus-quality), you should assess the relevance of concepts you have placed in thesauri.

* Use the [Extracted Concept List](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/advanced-features/corpus-management-overview/analyse-documents-in-your-document-corpus/extracted-concepts-list) to see how relevant concepts are.
* For an individual concept, examine its [Similar Terms](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/advanced-features/corpus-management-overview/analyse-documents-in-your-document-corpus/extracted-concepts-list/extracted-concepts-use-the-similar-terms-list) to identify synonyms \(alternative labels\) and new narrower concepts which can be added to a concept.
* Verify the [Extracted Term List](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/advanced-features/corpus-management-overview/analyse-documents-in-your-document-corpus/extracted-terms-list/extracted-terms-use-the-similar-terms-function) to disambiguate or dismiss terms. This helps you to further enhance/refine your thesauri as you could use terms as synonyms or as new concepts you had not considered earlier.

[Blacklist Concepts and Terms](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/advanced-features/corpus-management-overview/analyse-documents-in-your-document-corpus/blacklist-concepts-and-terms) to exclude them from being extracted or included in corpus analysis.

Use [PoolParty Linked Data-based translate function](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/basic-features/managing-your-thesauri/translating-labels-in-multilingual-thesauri) for translating the preferred labels of concepts in multilingual thesauri.

Be aware that you may have to redo [corpus analysis](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/advanced-features/corpus-management-overview/analyse-documents-in-your-document-corpus/blacklist-concepts-and-terms), translations, mappings, or any new add after making changes on a project in the test server and then move it to the production server.

Use the [InforMEA PoolParty Tagging Assessment Dashboard](http://dpoolparty.brsmeas.org/BRS-InforMEA_PP-Dashboard/index.html) to evaluate new or existing tagging in your CMS. By now, you can review InforMEA documents and web pages against the different thesaurus projects like LEO and BRS. It is planned in the next dashboard version to extend the review to any document, either from the local computer or from a content repository.

