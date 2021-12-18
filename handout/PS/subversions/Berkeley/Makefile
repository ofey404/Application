finals := $(wildcard *-final.md)
pdfs := $(patsubst %.md,%.pdf,$(finals))

0:
	grep -zoP '## Main\s*\K[\s\S]*(?=\s*## EndMain)' 0.md | wc -w 

all: $(pdfs)

$(pdfs): $(finals)
	pandoc -f markdown -o $(patsubst %.md,%.docx,$<) -t docx $<
	libreoffice --headless --convert-to pdf:writer_pdf_Export  "-env:UserInstallation=file:///tmp/LibreOffice_Conversion_${USER}" $(patsubst %.md,%.docx,$<)
	rm -f $(patsubst %.md,%.docx,$<)

clean:
	rm *.pdf
