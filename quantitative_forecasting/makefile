include config.mk

.SUFFIXES: .kg .eps .png

all: $(IMG)
	pdflatex forecasts.tex
	latex2rtf forecasts.tex
	pandoc -s -o forecasts.md forecasts.tex
	pdflatex slides.tex

.eps.png:
	convert -chop 0x180 $< $@
	rm $<

.kg.eps:
	kg -l ./$< -e '.x(0)' >$@

clean:
	rm -f *.aux *.log *.out *.snm *.nav *.toc

.PHONY: puttit clean
