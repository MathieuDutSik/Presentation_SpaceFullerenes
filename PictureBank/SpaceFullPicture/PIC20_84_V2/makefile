PNG = $(wildcard *.png)
PDF = $(patsubst %.png,%.pdf, $(PNG))
EPS = $(patsubst %.png,%.eps, $(PNG))


%.pdf: %.png ; convert $< $@

%.eps: %.png ; convert $< $@

all: $(PDF) $(EPS)
clean:
	rm -f $(PDF) $(EPS)
