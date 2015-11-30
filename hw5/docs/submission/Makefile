TEX=$(wildcard *.tex)
PDF=Assignment5
BUILD=pdflatex
SRC=Assignment5

all: ${PDF}

${PDF}: ${TEX}
	${BUILD} ${SRC}
	${BUILD} ${SRC}

clean:
	rm -rf *.pdf *.aux *.log *.out *.glg *.glo *.gls *.ist *.lof *.lot *.toc *.xdy *.glsdefs

.PHONY: clean
