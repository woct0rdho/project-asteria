.PHONY: all clean

all: main.pdf

main.pdf: *.tex *.bib
	xelatex main.tex
	bibtex main.aux
	xelatex main.tex
	xelatex main.tex

clean:
	rm *.aux *.bbl *.blg *.log *.out *.toc
