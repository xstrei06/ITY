FILE=proj2
all:
	latex $(FILE).tex
	latex $(FILE).tex
	dvips -t a4 $(FILE).dvi
	ps2pdf $(FILE).ps
clean:
	rm -f $(FILE).aux $(FILE).dvi $(FILE).log $(FILE).ps $(FILE).out $(FILE).pdf
