

all:
	- Rscript -e "files <- grep('Rmd', list.files(), value=TRUE); library(rmarkdown); sapply(files, render, 'html_document'); sapply(files, render, 'pdf_document')"

