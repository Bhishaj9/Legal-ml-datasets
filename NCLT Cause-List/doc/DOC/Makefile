SHELL := /bin/bash

all:
	latexmk -pdf instructionManual.tex

trial:
	latexmk -pdf codebook_trial.tex

clean:
	rm -f *.{aux,log,nav,out,snm,synctex.gz,tex~,toc,dvi,bbl,blg,glo,gls,acr,glg,alg,acn,ist,bak,lot,lof,fls,run.xml,bcf,fdb_latexmk,ptc,fdb_latexmk}

squeaky:
	make clean
	-rm *.pdf
