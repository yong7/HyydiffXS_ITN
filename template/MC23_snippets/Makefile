#------------------------------------------------------------------------------
# Makefile to make EXOT templates document
#------------------------------------------------------------------------------

BASENAME = MC23_snippets

.PHONY: clean cleanpdf

MC23_snippets:
	make -f ../../doc/Makefile run_latexmk BASENAME=$(BASENAME)

clean:
	make -f ../../doc/Makefile clean
	
cleanpdf:
	-rm $(BASENAME).pdf

cleanall: clean cleanpdf
	