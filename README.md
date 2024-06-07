
# Analysis Data Reviewer's Guide (ADRG) Extension for Quarto

This template is based on work from the R Consortium R Submissions Working Group. The example documents are directly from [Pilot 3](https://github.com/RConsortium/submissions-pilot3-adam) and [Pilot 4](https://github.com/RConsortium/submissions-pilot4-webR).

## Creating a New Article

To create a new article using this format:

```bash
quarto use template parmsam/quarto-adrg
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add parmsam/quarto-adrg
```

Then, add the format to your document options:

```yaml
format:
  adrg-pdf: default
  adrg-html: default
```    

## Examples

Here is the source code for two example documents: 
- [adrg-pilot3.qmd](adrg-pilot3.qmd).
- [adrg-pilot4.qmd](adrg-pilot4.qmd).

