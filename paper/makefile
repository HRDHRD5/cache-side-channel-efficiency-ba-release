# compilation everything
all: compile_full

# TEX stuff
TEXTFILES = main.tex

compile_full:
	latexmk -lualatex -pdf -gg -cd  $(TEXTFILES)

compile:
	latexmk -lualatex -pdf -cd  $(TEXTFILES)

help:
	echo "available commands "
	echo "clean : removes some files from your disk warning calls rm with * on some regex "

clean:
	latexmk -cd -C $(TEXTFILES)