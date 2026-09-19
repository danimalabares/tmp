.PHONY: all clean

LECTURES := lecture-12 lecture-13

all: $(addsuffix .pdf,$(LECTURES))

%.pdf: %.tex
	latexmk -pdf -interaction=nonstopmode -halt-on-error -outdir=build $<
	cp build/$@ $@

clean:
	latexmk -C -outdir=build $(addsuffix .tex,$(LECTURES))
