.PHONY: FORCE default clean distclean

FILE=thesis

default: $(FILE).pdf

%.pdf: %.tex FORCE
	latexmk -xelatex -8bit -shell-escape -pvc --synctex=1

clean:
	$(RM) *.{dvi,aux,log,toc,lof,lol,lot,dlog,bbl,blg,idx,out,tpt,svn,synctex.gz}
	$(RM) *.{nav,snm,vrb,fls,fdb_latexmk} *~ *.bak
	$(RM) Chapters/*.aux
