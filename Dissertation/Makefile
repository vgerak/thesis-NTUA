.PHONY: FORCE default clean distclean

FILE=thesis

default: $(FILE).pdf

%.pdf: %.tex FORCE
	latexmk -pdf -f -e '$$pdflatex=q/xelatex %O %S/' $<

clean:
	$(RM) *.{dvi,aux,log,toc,lof,lol,lot,dlog,bbl,blg,idx,out,tpt,svn,synctex.gz}
	$(RM) *.{nav,snm,vrb,fls,fdb_latexmk} *~ *.bak
	$(RM) Chapters/*.aux

distclean: clean
	$(RM) $(FILE).{dvi,ps,pdf}
