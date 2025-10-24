#------------------------------------------------------------------------------
# Makefile to make EXOT templates document
#------------------------------------------------------------------------------

BASENAME = MC16_snippets

.PHONY: clean cleanpdf

MC16_snippets:
	make -f ../../doc/Makefile run_latexmk BASENAME=$(BASENAME)

clean:
	make -f ../../doc/Makefile clean
	
cleanpdf:
	-rm $(BASENAME).pdf

cleanall: clean cleanpdf
	