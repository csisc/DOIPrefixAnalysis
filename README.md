# DOI Prefix Analysis
List of CrossRef DOI prefixes augmented with semantic information about their holders from Wikidata

## Data Collection
This project collects the [list](https://www.crossref.org/06members/51depositor.html) of [Digital Object Identifier](https://www.doi.org/) prefixes corresponding to journal publishers as revealed by the *[CrossRef](https://www.crossref.org/)* bibliographic database as of 17 January 2022 (98,420,414 DOIs). This dataset includes the number of journals and publications corresponding to every DOI prefix. Then, we use *[OpenRefine](https://openrefine.org/)*, a data cleaning and reconciliation software, for aligning the publisher names of the best 200 DOI prefixes to their corresponding items in *[Wikidata](https://www.wikidata.org)*, an open and collaborative multilingual and multidisciplinary knowledge graph. The alignment of publishers to Wikidata items will be later used to enrich the list of DOI prefixes with detailed information about the publishers, mainly the *type*, *country*, *year of creation*, and *year of end of work* of every institution. As well, this matching will be used to identify the publishers indexed in the [Beall's List](https://en.wikipedia.org/wiki/Beall%27s_List) of [predatory publishing institutions](https://en.wikipedia.org/wiki/Predatory_publishing). The output is finally curated by the two first authors to fill the gaps in data and verify the information automatically added from Wikidata to our dataset.

## To cite the work
Turki, H., Fraumann, G., Hadj Taieb, M. A., & Ben Aouicha, M. (2022). Digital Object Identifiers (DOIs) for whom? 
The Digital Divide in Scientometrics and the Publishing Industry. *Frontiers in Research Metrics and Analytics* (Forthcoming).

