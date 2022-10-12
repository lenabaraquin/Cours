.PHONY : all clean print bib
all: main.pdf

main.pdf : main.tex
	pdflatex main.tex 

clean: 
	rm *.log *.toc *.aux *.bbl *.blg *.xml *.bcf

print: main.pdf
	evince main.pdf

bib: main.tex biblio.bib
	biber main

