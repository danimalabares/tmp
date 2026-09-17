.PHONY: all clean

all: lecture-12.pdf

lecture-12.pdf: lecture-12.tex
	latexmk -pdf -interaction=nonstopmode -halt-on-error -outdir=build lecture-12.tex
	cp build/lecture-12.pdf lecture-12.pdf

clean:
	latexmk -C -outdir=build lecture-12.tex
