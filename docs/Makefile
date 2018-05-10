all:
	Rscript -e "rmarkdown::render('cv.Rmd', output_format = 'pdf_document')" \;
	Rscript -e "rmarkdown::render('cv.Rmd', output_format = 'github_document', output_file = 'cv.md')"
	
github:
	Rscript -e "rmarkdown::render('cv.Rmd', output_format = 'github_document', output_file = 'cv.md')"

pdf:
	Rscript -e "rmarkdown::render('cv.Rmd', output_format = 'pdf_document')"
