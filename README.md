
# Analysis Data Reviewer's Guide (ADRG) Extension for Quarto
This template is based on work from the R Consortium R Submissions Working Group. The example documents are directly from [Pilot 3](https://github.com/RConsortium/submissions-pilot3-adam) and [Pilot 4](https://github.com/RConsortium/submissions-pilot4-webR). The docx format is based on [an ADRG Word template](https://advance.phuse.global/display/WEL/Analysis+Data+Reviewer%27s+Guide+%28ADRG%29+Package) from [PHUSE](https://advance.phuse.global/display/WEL/Deliverables). 

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

Then, add the format to your document options. You have three differt formats to choose from: adrg-pdf, adrg-html, and adrg-docx:

```yaml
format:
  adrg-pdf: default
  adrg-html: default
  adrg-docx: default
```   

You can render to your desired format using the quarto R package quarto_render function:

```r
library(quarto)
quarto_render("adrg-pilot4.qmd", output_format = "adrg-pdf")
```

## Examples

Here is the source code for two example documents: 
- [adrg-pilot3.qmd](adrg-pilot3.qmd).
- [adrg-pilot4.qmd](adrg-pilot4.qmd).

