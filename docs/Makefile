all: pdf github blog

github:
	Rscript -e "rmarkdown::render('index.Rmd', output_format = 'github_document', output_file = 'README.md', encoding = 'UTF-8')" \/;

pdf:
	Rscript -e "rmarkdown::render('index.Rmd', output_format = 'pdf_document', output_file = 'cv.pdf', encoding = 'UTF-8')"

blog:
	cat cv-header.md README.md > ../content/blog/cv.md
