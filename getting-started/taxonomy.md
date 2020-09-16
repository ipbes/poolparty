# Taxonomy

It is needed to have at least a taxonomy describing your knowledge domain to use PoolParty. So, there are two possible scenarios:

## MEA has a taxonomy, but not yet in PoolParty”

It is convenient to use Excel sheets to express the whole taxonomy or parts of it in the [PoolParty Excel format](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/basic-features/import-export-and-reporting-with-poolparty/poolparty-excel-import-export-overview/the-poolparty-excel-format). This a handy and easy way to put your taxonomy into PoolParty. Please note that the use of excel is practical for importing terms into PoolParty but does not allow you to relate terms \(concepts\) to each other.

## MEA does not even have a taxonomy

You first need to define\[SR2\]  your taxonomy. It is highly recommended that, to begin with, you create the taxonomy as simple as it could be, by including the main subjects in a hierarchical structure; later, with PoolParty aid, you will be able to extend, enhance and improve it.

## How can a taxonomy be represented using the PoolParty Excel format?

The majority of MEAs will choose the excel import, a limited view of their individual vocabulary, indicating the hierarchy, alternative labels, definitions and translations. The [PoolParty Excel format](https://help.poolparty.biz/pp7/user-guide-for-knowledge-engineers/basic-features/import-export-and-reporting-with-poolparty/poolparty-excel-import-export-overview/the-poolparty-excel-format) follows a strict template, that needs to be used for PoolParty. A sample of taxonomy representation in PoolParty Excel format could look like this:

![](../.gitbook/assets/image%20%2817%29.png)

Observe in the example above that, following the PoolParty Excel format rules, taxonomy subject’s column headers like “Classes”, “Top Categories”, “Sub Categories”, “Synonyms” and “Number Code” have become into “**scheme**”, “**concept**”, “**altLabel**” and “**notation**” \(case-sensitive\) column headers, respectively.

In correspondence, there is a mapping of items from a not clearly-established source format to the required PoolParty format:

* The level 1 item under “Classes” \(i.e., 1. Beverage\), becomes a **scheme** in the PoolParty Excel format.
* The lower-level items under “Classes”, “Top Categories” and “Sub Categories” \(e.g., 1.1 Alcoholic beverage, 1.2.1 Coffee or 1.2.2.1 Coconut milk\), all become a **concept** in the PoolParty Excel format and inherit their hierarchy from the preceding columns. Make sure that each concept and scheme is on a separate line.
* Each item in the list under “Synonyms” needs to be in a separate column headed as **altLabel** in the PoolParty Excel format. If you have a multilingual taxonomy, you will need to specify the language, e.g. **altLabel@fr** for French or **altLabel@ar** for Arabic; if you don’t specify the language, it is assumed the default language set in the PoolParty project.

{% hint style="info" %}
* The column headings in PoolParty Excel format are case sensitive.
* At the left of the red line, the columns are placed in a certain fixed order and that there is only a non-blank cell on each row; at the right of the red line, columns could appear in any order and  there are more than one non-blank cell in the same row.
* You don’t need to import the whole taxonomy at once using a single Excel import; you could \(and should\) use several Excel files to do partial imports at different levels of the taxonomy’s hierarchy. The PoolParty flexibility allows you to import just a sub-tree, that could be as simple as a list, into the taxonomy.
* You should follow strictly the rules for configuring such Excel sheets to be imported into PoolParty.
* Ensure you do not have hidden, non-printable characters in the sheets which could produce unexpected errors during and after an Excel sheet import. Make use of Excel functions to clean your data e.g. CLEAN\(\) or TRIM \(\).
{% endhint %}

{% hint style="warning" %}
 When using PoolParty Excel, you should keep in mind that **SKOS** **relations** **are not available in the Excel export**. Hence, if you export your project with defined concept mappings to Excel, you will not be saving those mappings and, if you try to re-import the project from that Excel export file as a new project, the resulting one will not contain the original mappings.

Importing relations only works with the [update import feature](https://help.poolparty.biz/display/doc/Add+Data+via+Excel). This is because relations can only be created between concepts that already exist in the taxonomy. This means that in order to import an Excel taxonomy that includes relations between concepts, one has to first import only the concepts involved and, in a second import, add the relations. If you need to update mappings using [**Excel import**](https://help.poolparty.biz/faq/faq-s/excel-import-export/how-can-i-import-relations-with-excel-import), you should observe the proper PoolParty Excel Format rules.
{% endhint %}

