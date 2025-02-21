# Nombre del archivo principal (sin extensión)
MAIN = main

# Comandos
LATEXMK = latexmk
BIBTEX = bibtex
RM = rm -f
MV = mv

# Opciones
LATEXMK_OPTS = -pdf -interaction=nonstopmode -shell-escape

all: $(MAIN).pdf

# Compilación principal con manejo de bibliografía
$(MAIN).pdf: $(MAIN).tex biblio.bib reporte/*.tex preambulo.sty hdrftr.tex figs/*
	$(LATEXMK) $(LATEXMK_OPTS) $(MAIN)

clean:
	$(LATEXMK) -c
	$(RM) $(MAIN).bbl $(MAIN).blg $(MAIN).run.xml $(MAIN).synctex.gz

distclean: clean
	$(RM) $(MAIN).pdf

.PHONY: all clean distclean

