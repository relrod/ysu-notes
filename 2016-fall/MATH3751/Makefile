latex:
	latexmk -output-directory=out -aux-directory=out -pdf -pdflatex="pdflatex --shell-escape %O %S" notes.tex

open:
	xdg-open out/*.pdf &

clean:
	rm -rf out
