# Nome del file principale da compilare
SOURCE = lrdne.tex 

# Destinazione del file prodotto
DESTINATION := $(shell echo $(DESTINATION))

make:
	pdflatex $(SOURCE) -output-format=pdf
	cp lrdne.pdf $(DESTINATION)/lrdne.pdf
	make clean

clean:
	rm -rf  *.class *.html *.log *.aux *.out *.glo *.glg *.gls *.ist *.xdy *.1 *.pyg *.xml *.bcf
