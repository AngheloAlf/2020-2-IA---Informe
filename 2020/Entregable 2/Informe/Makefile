# https://tex.stackexchange.com/a/459470

all:
	!( : | pdflatex -halt-on-error --jobname=201473062-4-AngheloCarvajal-Ent2 main.tex | grep '^!.*' -A200 --color=always )
	bibtex 201473062-4-AngheloCarvajal-Ent2
	!( : | pdflatex -halt-on-error --jobname=201473062-4-AngheloCarvajal-Ent2 main.tex | grep '^!.*' -A200 --color=always ) 
	!( : | pdflatex -halt-on-error --jobname=201473062-4-AngheloCarvajal-Ent2 main.tex | grep '^!.*' -A200 --color=always )


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
	rm -f *.aux *.bbl *.blg *.fdb_latexmk *.fls *.log *.out
