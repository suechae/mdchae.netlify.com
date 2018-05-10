all:
	Rscript -e "rmarkdown::render('index.Rmd', output_format = 'pdf_document', output_file = 'cv.pdf', encoding = 'UTF-8')" \;
	Rscript -e "rmarkdown::render('index.Rmd', output_format = 'github_document', output_file = 'README.md', encoding = 'UTF-8')" \;
	cat cv-header.md README.md > ../content/cv.md

github:
	Rscript -e "rmarkdown::render('index.Rmd', output_format = 'github_document', output_file = 'README.md')"

pdf:
	Rscript -e "rmarkdown::render('index.Rmd', output_format = 'pdf_document')"

