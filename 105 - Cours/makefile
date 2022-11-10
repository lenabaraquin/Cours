.PHONY : all clean print

all : cours.pdf

cours.pdf: cours.tex s1.tex
	pdflatex cours.tex

clean: 
	rm *.log *.toc *.aux

print: cours.pdf
	evince cours.pdf
