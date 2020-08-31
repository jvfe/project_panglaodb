---
author-meta:
- "Jo\xE3o Vitor Ferreira Cavalcante"
- Tiago Lubiana Alves
bibliography:
- content/manual-references.json
date-meta: '2020-08-31'
header-includes: "<!--\nManubot generated metadata rendered from header-includes-template.html.\nSuggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html\n-->\n<meta name=\"dc.format\" content=\"text/html\" />\n<meta name=\"dc.title\" content=\"Analysing the extent of cell type information present in Wikidata\" />\n<meta name=\"citation_title\" content=\"Analysing the extent of cell type information present in Wikidata\" />\n<meta property=\"og:title\" content=\"Analysing the extent of cell type information present in Wikidata\" />\n<meta property=\"twitter:title\" content=\"Analysing the extent of cell type information present in Wikidata\" />\n<meta name=\"dc.date\" content=\"2020-08-31\" />\n<meta name=\"citation_publication_date\" content=\"2020-08-31\" />\n<meta name=\"dc.language\" content=\"en-US\" />\n<meta name=\"citation_language\" content=\"en-US\" />\n<meta name=\"dc.relation.ispartof\" content=\"Manubot\" />\n<meta name=\"dc.publisher\" content=\"Manubot\" />\n<meta name=\"citation_journal_title\" content=\"Manubot\" />\n<meta name=\"citation_technical_report_institution\" content=\"Manubot\" />\n<meta name=\"citation_author\" content=\"Jo\xE3o Vitor Ferreira Cavalcante\" />\n<meta name=\"citation_author_institution\" content=\"Bioinformatics Multidisciplinary Environment, Federal University of Rio Grande do Norte\" />\n<meta name=\"citation_author_orcid\" content=\"0000-0001-7513-7376\" />\n<meta name=\"citation_author\" content=\"Tiago Lubiana Alves\" />\n<meta name=\"citation_author_institution\" content=\"Computational Systems Biology Laboratory, University of S\xE3o Paulo\" />\n<meta name=\"citation_author_orcid\" content=\"0000-0003-2473-2313\" />\n<link rel=\"canonical\" href=\"https://jvfe.github.io/manuscript_panglaodb/\" />\n<meta property=\"og:url\" content=\"https://jvfe.github.io/manuscript_panglaodb/\" />\n<meta property=\"twitter:url\" content=\"https://jvfe.github.io/manuscript_panglaodb/\" />\n<meta name=\"citation_fulltext_html_url\" content=\"https://jvfe.github.io/manuscript_panglaodb/\" />\n<meta name=\"citation_pdf_url\" content=\"https://jvfe.github.io/manuscript_panglaodb/manuscript.pdf\" />\n<link rel=\"alternate\" type=\"application/pdf\" href=\"https://jvfe.github.io/manuscript_panglaodb/manuscript.pdf\" />\n<link rel=\"alternate\" type=\"text/html\" href=\"https://jvfe.github.io/manuscript_panglaodb/v/e9e294b629e94d0989c06a0c1659f499d3c1690e/\" />\n<meta name=\"manubot_html_url_versioned\" content=\"https://jvfe.github.io/manuscript_panglaodb/v/e9e294b629e94d0989c06a0c1659f499d3c1690e/\" />\n<meta name=\"manubot_pdf_url_versioned\" content=\"https://jvfe.github.io/manuscript_panglaodb/v/e9e294b629e94d0989c06a0c1659f499d3c1690e/manuscript.pdf\" />\n<meta property=\"og:type\" content=\"article\" />\n<meta property=\"twitter:card\" content=\"summary_large_image\" />\n<link rel=\"icon\" type=\"image/png\" sizes=\"192x192\" href=\"https://manubot.org/favicon-192x192.png\" />\n<link rel=\"mask-icon\" href=\"https://manubot.org/safari-pinned-tab.svg\" color=\"#ad1457\" />\n<meta name=\"theme-color\" content=\"#ad1457\" />\n<!-- end Manubot generated metadata -->"
keywords:
- markdown
- publishing
- manubot
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: Analysing the extent of cell type information present in Wikidata
...






<small><em>
This manuscript
([permalink](https://jvfe.github.io/manuscript_panglaodb/v/e9e294b629e94d0989c06a0c1659f499d3c1690e/))
was automatically generated
from [jvfe/manuscript_panglaodb@e9e294b](https://github.com/jvfe/manuscript_panglaodb/tree/e9e294b629e94d0989c06a0c1659f499d3c1690e)
on August 31, 2020.
</em></small>

## Authors



+ **João Vitor Ferreira Cavalcante**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0001-7513-7376](https://orcid.org/0000-0001-7513-7376)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [jvfe](https://github.com/jvfe)<br>
  <small>
     Bioinformatics Multidisciplinary Environment, Federal University of Rio Grande do Norte
  </small>

+ **Tiago Lubiana Alves**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0003-2473-2313](https://orcid.org/0000-0003-2473-2313)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [lubianat](https://github.com/lubianat)<br>
  <small>
     Computational Systems Biology Laboratory, University of São Paulo
  </small>



## Abstract {.page_break_before}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Intellegi quidem, ut propter aliam quampiam rem, verbi gratia propter voluptatem, nos amemus; Nec tamen ille erat sapiens quis enim hoc aut quando aut ubi aut unde? Duo Reges: constructio interrete. Non pugnem cum homine, cur tantum habeat in natura boni; Gloriosa ostentatio in constituendo summo bono. Me igitur ipsum ames oportet, non mea, si veri amici futuri sumus. Cur ipse Pythagoras et Aegyptum lustravit et Persarum magos adiit? Quae animi affectio suum cuique tribuens atque hanc, quam dico. Quis est autem dignus nomine hominis, qui unum diem totum velit esse in genere isto voluptatis? Qui si ea, quae dicit, ita sentiret, ut verba significant, quid inter eum et vel Pyrrhonem vel Aristonem interesset?

**Keywords**: wikidata, knowledge graph, cell type, ontology.


## Introduction

### Wikidata

[Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) is an open, freely editable, knowledge graph database within the [semantic web](https://www.w3.org/standards/semanticweb/) that stores knowledge across a multitude of domains,
such as arts, history, chemistry and biology, using an item-property-value linked data model. It is easy to use and edit, by both humans and machines, with a rich web user interface and wrapper packages available
in common programming languages such as R and Python. All the data within Wikidata is linked and inherently public domain, thus, it presents a great opportunity to make scientific data more FAIR (Findable, accessible, interoperable and reusable), as well as provides the necessary tools to curate and develop ontologies. 

**Put figure here illustrating the wikidata data model**

Several advances towards biological data integration and biological data analysis in Wikidata have been made before, yielding positive
results [@doi:10.1101/031971] [@doi:10.7554/eLife.52614] and showcasing it's potential for bioinformatics-related analyses, such as drug repurposing and ID conversion [@doi:10.7554/eLife.52614]. Wikidata has been proposed as a unified base to gather and distribute biomedical knowledge, with more than 50 000 human gene items indexed and hundreds of biomedical-related properties [@doi:10.1016/j.jbi.2019.103292]. However, as of August 2020, cell type information is still very scarse, with only 264 items being categorized as instances of cell types (Q189118), of those, only nine have a "Cell Ontology ID" (P7963)[@pmid:27377652] associated, and most have a varying amount of statements (Table @tbl:cell-counts).

| Cell type Item | Number of statements |
|:-------------:|:---------------:|
| red blood cell (Q37187) | 48 |
| myocyte (Q428914) | 18 |
| mesenchymal cell (Q66568500) | 2 |
Table: As of August 2020, Wikidata items regarding cell types have a varying amount of information, with most having very few statements.
{#tbl:cell-counts}


### PanglaoDB

[PanglaoDB](https://panglaodb.se/index.html) [@doi:10.1093/database/baz046] is a public database that contains data and metadata on hundreds of single-cell RNA sequencing experiments, providing extensive information on cell types, genes and tissues, as well as manually and community curated cell type markers (Table @tbl:panglao). It also provides a rich web user interface for easy data acquisition, including database dumps for bulk downloads.

|	|Mus musculus 	| Homo sapiens|
|:--:|:-------------:|:---------------:|
|Samples |	1063 | 305 |
|Tissues |	184  |74 |
|Cells 	| 4,459,768 | 1,126,580 |
|Cell Clusters| 8,651 | 1,748 |
Table: Database statistics for each species in PanglaoDB, as of 31st August 2020.
{#tbl:panglao}




## Objectives

Outline geral, apenas para me lembrar:

- Quantos tipos celulares são descritos na base? Quantos tem, no dia da análise, matches exatos? 

- Os que tem matches exatos verbalmente, os matches tão  minimamente bem anotados (Cell Ontology ID  + instance_of: cell type) 

- Os genes, espécies e orgãos tem cobertura no Wikidata? 

- Os aliases de genes tem cobertura no Wikidata?

Como categorizar cobertura? Match=True na reconciliação? Cutoff de score da reconciliação? 

Como verificar os aliases de genes? 
    - Pegar o altlabel [pela interface de serviço](https://www.mediawiki.org/wiki/Wikidata_Query_Service/User_Manual#Extensions)


## Methodology

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
