all:
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex


install-dependencies:
	tlmgr install babel-spanish
	tlmgr install hyph-utf8
	tlmgr install abstract
	tlmgr install mdframed
	tlmgr install etoolbox
	tlmgr install zref
	tlmgr install needspace
	sudo apt-get install texlive-fonts-extra


clean:
	rm -f *.aux *.bbl *.blg *.fdb_latexmk *.fls *.log *.out *.pdf
