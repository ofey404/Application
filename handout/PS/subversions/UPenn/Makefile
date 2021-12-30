sources := $(wildcard *.md)
finals := $(wildcard *-final.md)
pdfs := $(patsubst %.md,%.pdf,$(finals))
docs := $(patsubst %.md,%.docx,$(sources))

all: $(pdfs)

$(pdfs): $(finals)
	pandoc -f markdown -o $(patsubst %.md,%.docx,$<) -t docx $<
	libreoffice --headless --convert-to pdf:writer_pdf_Export  "-env:UserInstallation=file:///tmp/LibreOffice_Conversion_${USER}" $(patsubst %.md,%.docx,$<)
	rm -f $(patsubst %.md,%.docx,$<)

1:
	grep -zoP '## Main\s*\K[\s\S]*(?=\s*## EndMain)' 1-*.md | wc -w 

0:
	grep -zoP '## Main\s*\K[\s\S]*(?=\s*## EndMain)' 0.md | wc -w 

clean:
	rm -f *.pdf
	rm -f *.docx