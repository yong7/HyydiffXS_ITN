#------------------------------------------------------------------------------
# Makefile to make PubCom standard references.
#------------------------------------------------------------------------------

BASENAME = PubCom_BibTeX

.PHONY: clean cleanpdf

PubCom_BibTeX:
	make -f ../../doc/Makefile run_latexmk BASENAME=$(BASENAME)

clean:
	make -f ../../doc/Makefile clean
	
cleanpdf:
	-rm $(BASENAME).pdf

cleanall: clean cleanpdf
	