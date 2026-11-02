DECKS := plan lecture-23 lecture-24

.PHONY: all clean $(DECKS)
all: $(DECKS)

plan:
	cd $@ && pdflatex -interaction=nonstopmode -halt-on-error slides.tex
	cd $@ && pdflatex -interaction=nonstopmode -halt-on-error slides.tex

lecture-23 lecture-24:
	cd $@ && pdflatex -interaction=nonstopmode -halt-on-error $@.tex
	cd $@ && pdflatex -interaction=nonstopmode -halt-on-error $@.tex

clean:
	for d in $(DECKS); do for ext in aux log nav out snm toc vrb; do rm -f "$d/slides.$ext" "$d/$d.$ext"; done; done
