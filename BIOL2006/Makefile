# main operations
all: documents

clean:
	rm pdf/* -rf

# make documents
documents: pdf/week-1.pdf pdf/week-2.pdf pdf/week-3.pdf

pdf/week-1.pdf: src/week-1.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-1.Rmd')"
	mv src/week-1.pdf pdf/

pdf/week-2.pdf: src/week-2.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-2.Rmd')"
	mv src/week-2.pdf pdf/

pdf/week-3.pdf: src/week-3.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-3.Rmd')"
	mv src/week-3.pdf pdf/


