MAIN=book.tex

.PHONY: all
all:
	xelatex $(MAIN)
	makeindex $(MAIN:%.tex=%.idx)
	xelatex $(MAIN)

clean:
	rm -f *.aux
	rm -f *.ind
	rm -f *.idx
	rm -f *.ilg
	rm -f *.log
	rm -f *.toc
	rm -f *.out