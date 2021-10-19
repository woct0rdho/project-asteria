all: main.pdf

main.pdf: *.tex
	xelatex main.tex
	bibtex main.aux
	xelatex main.tex
	xelatex main.tex
