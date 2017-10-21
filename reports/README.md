# Project Reports

There are 3 project "progress reports" and one final report.
They will be written inside this sub directory in RMarkdown. 

## Compiling the PDF from command line

To compile a PDF version of one of the reports you can run the following command with any rmd file

Rscript -e 'library(rmarkdown);render("ProjectReport1.rmd", "pdf_document")'
