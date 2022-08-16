[![DOI](https://zenodo.org/badge/467110288.svg)](https://zenodo.org/badge/latestdoi/467110288)

# RiskGONE materials

Private repository with info about the RiskGONE materials

* [RiskGONE guidance](identifiers_and_guidance.md)
  * [the RiskGONE ERM identifiers](identifiers_and_guidance.md#the-nanomaterials)
  * [the RiskGONE Literature study ERM identifiers](RiskGONE_Literature_NM.md)
* [General info on the ERM identifiers](https://nanocommons.github.io/identifiers/)

## Creating a PDF

Creating a PDF or Word file of the guidance requires to convert the Markdown
input into PDF. This can be done with [Pandoc](https://pandoc.org/):

```shell
pandoc -o identifiers_and_guidance.pdf -f markdown -t html5 identifiers_and_guidance.md
pandoc -o identifiers_and_guidance.docx -f markdown -t docx identifiers_and_guidance.md
```
