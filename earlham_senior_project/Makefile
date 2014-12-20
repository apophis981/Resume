all: main

main:
	latex final_paper
	bibtex final_paper
	latex final_paper
	latex final_paper
	dvipdf final_paper.dvi 

clean:
	rm -f *.aux *.bak *.dvi *.log *.toc *.pdf *.blg *.bbl
