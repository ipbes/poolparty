# MEA corpora

## MEA has transferred its taxonomy into a PoolParty project. Now, what?

A taxonomy by itself is not enough expressive to understand how the contents are to be best tagged in order to search them. PoolParty, based on statistics about concepts and terms extracted from a corpus of documents representative of the MEA’s knowledge domain, can help to extend, enhance and improve thesauri and content tagging. In a nutshell, PoolParty needs to “learn”, or better understand the information contained in your documents, before providing good suggestions to improve your taxonomy and to tag your documents. By feeding PoolParty with a corpus of documents representative of your information, you will get better suggestions from PoolParty. • “

## How a corpus can provide benefits to MEA thesauri?”

###  Corpus Management 

The corpus management functionality in PoolParty supports you in extending thesauri with relevant terms derived from contents such as documents, web sites, RSS feeds or DBpedia resources matching the domain of your thesauri. Concepts, terms and phrases are extracted from those contents, which then are matched against the concepts in thesauri and subsequently scored.

![](../.gitbook/assets/image%20%2826%29.png)

###  Create a Corpus 

Hence, you need to create a corpus in an adequate manner to obtain the best results.

![](../.gitbook/assets/image%20%2832%29.png)

Note that the corpus language has to be defined during its creation.

![](../.gitbook/assets/image%20%2831%29.png)

## How to decide what to include in corpora for MEA thesauri?” 

### Multiple corpora 

Since in PoolParty you can have multiple corpora in the same project, and the MEAs knowledge domain comprehends scientific, legal and governance subjects, it could be coherent and reasonable to consider three corpora, one corpus by subject. 

###  Corpus Analysis 

Once you have created a corpus using the above procedure, you can start corpus analysis. The so-called corpus analysis is based on algorithms of the extraction model that identifies relevant concepts by frequency, relevance and several parameters. The corpus analysis also produces, among others, the following outputs: Corpus Quality, Extracted Concepts List and Extracted Terms List. Corpus Quality indicates the quality of suggested terms; Extracted Concepts List contains all concepts from the thesaurus that have been detected in the uploaded documents and it allows to assess the concepts that have been included in thesauri; Extracted Terms List shows terms which have been extracted from the documents in the corpus and which are not yet part of the thesaurus and it is a source of candidate concepts, new alternative labels, etc. In particular, you should: 

* Inspect statistics about corpus analysis 
* Compare the Extracted Concepts List against the concepts you have defined in thesauri, basically to see if some of the concepts are irrelevant because they are never used or almost not used. 
* Check the Extracted Terms List to wonder if some terms should be added as new concepts to refine or improve thesauri. 

### Corpus quality

The quality of extracted terms depends strongly on the provided corpus. A corpus with a larger number of small contents will provide better results than a corpus with a small number of large contents \(In our experience, 50 to 60 PDF documents was a good choice\). The contents \(meeting documents, decisions, publications, legal documents, scientific documents\) should be selected as a representative sample of the domain, content set or topic your thesauri should represent. 

### Multilanguage projects 

As it is expected in MEAs activity, it is highly probable that it is desired to use several languages in a project. You should avoid selecting content for corpus analysis that contains several languages in the same document or across documents. If you want to use PoolParty corpus management functionality with different languages, you should include corpus versions corresponding to those languages. For instance, a “Scientific Corpus” with English contents, a “Cuerpo Científico” with Spanish contents, etc.

## Getting Super Powers

Becoming a super hero is a fairly straight forward process:

```
$ give me super-powers
```

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

Once you're strong enough, save the world:

{% code title="hello.sh" %}
```bash
# Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```
{% endcode %}



