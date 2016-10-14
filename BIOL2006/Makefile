# main operations
all: documents

clean:
	rm pdf/* -rf

# make documents
documents: pdf/week-1-questions.pdf pdf/week-1-solutions.pdf pdf/week-2-questions.pdf pdf/week-2-solutions.pdf pdf/week-3-questions.pdf pdf/week-3-solutions.pdf pdf/week-4-solutions.pdf pdf/week-5-solutions.pdf pdf/week-6-solutions.pdf pdf/week-8-solutions.pdf

pdf/week-1-solutions.pdf: src/week-1-solutions.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-1-solutions.Rmd')"
	mv src/week-1-solutions.pdf pdf/

pdf/week-2-solutions.pdf: src/week-2-solutions.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-2-solutions.Rmd')"
	mv src/week-2-solutions.pdf pdf/

pdf/week-3-solutions.pdf: src/week-3-solutions.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-3-solutions.Rmd')"
	mv src/week-3-solutions.pdf pdf/

pdf/week-4-solutions.pdf: src/week-4-solutions.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-4-solutions.Rmd')"
	mv src/week-4-solutions.pdf pdf/

pdf/week-5-solutions.pdf: src/week-5-solutions.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-5-solutions.Rmd')"
	mv src/week-5-solutions.pdf pdf/

pdf/week-6-solutions.pdf: src/week-6-solutions.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-6-solutions.Rmd')"
	mv src/week-6-solutions.pdf pdf/

pdf/week-8-solutions.pdf: src/week-8-solutions.Rmd src/preamble-latex.tex
	R -e "rmarkdown::render('src/week-8-solutions.Rmd')"
	mv src/week-8-solutions.pdf pdf/

pdf/week-1-questions.pdf: src/week-1-questions.pdf
	cp src/week-1-questions.pdf pdf/week-1-questions.pdf

pdf/week-2-questions.pdf: src/week-2-questions.pdf
	cp src/week-2-questions.pdf pdf/week-2-questions.pdf

pdf/week-3-questions.pdf: src/week-3-questions.pdf
	cp src/week-3-questions.pdf pdf/week-3-questions.pdf
