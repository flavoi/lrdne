# Nome del file principale da compilare
SOURCE = lrdne.tex 

# Destinazione del file prodotto
DESTINATION := $(shell echo $(DESTINATION))

make:
	pdflatex $(SOURCE) -output-format=pdf
	cp lrdne.pdf $(DESTINATION)/La\ ricerca\ di\ nuovi\ eroi.pdf
	make clean

clean:
	rm -rf  $(TARGET) *.class *.html *.log *.aux *.out *.glo *.glg *.gls *.ist *.xdy *.1 *.pyg *.xml *.bcf
