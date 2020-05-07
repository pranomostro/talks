include config.mk

.SUFFIXES: .kg .eps .png

all: $(IMG)
	pdflatex forecasts.tex
	latex2rtf forecasts.tex
	pandoc -s -o forecasts.md forecasts.tex

.eps.png:
	convert -chop 0x180 $< $@
	rm $<

.kg.eps:
	kg -l ./$< -e '.x(0)' >$@

clean:
	rm -f $(IMG)

.PHONY: puttit clean
