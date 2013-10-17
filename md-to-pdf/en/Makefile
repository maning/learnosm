SOURCE_FILE_NAME =  0300-01-01-essc-foreword.md 0200-12-30-introduction.md 0200-12-29-start-osm.md 0200-12-28-portableapps.md 0200-12-28-start-josm.md 0200-12-27-josm-plugins.md 0200-12-26-beginner2.md 0200-12-25-gps-1.md 0200-12-14-gpsessentials.md 0200-12-24-papers.md 0200-12-23-phase3-beginner.md 0200-12-21-editing-with-josm.md 0200-12-20-arerial-imagery-considerations.md 0200-12-19-intermediate.md 0200-12-15-tasking-manager.md 0200-12-17-conflict-resolution.md 0200-12-16-quality-assurance.md 0200-11-30-cc0-license.md

BOOK_FILE_NAME = material

PDF_BUILDER = pandoc
PDF_BUILDER_FLAGS = \
	--latex-engine xelatex \
	--template ../common/pdf-template.tex \
	--listings

lgutrainmat.pdf:
	 $(PDF_BUILDER) $(PDF_BUILDER_FLAGS) $(SOURCE_FILE_NAME) -o $(BOOK_FILE_NAME).pdf

clean:
	rm -f */$(BOOK_FILE_NAME).pdfmake



