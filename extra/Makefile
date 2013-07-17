pdf: notas_de_aula

ereader:
	-sed -i '20s/^/% /' paper_size.tex
	-sed -i '23,24s/^% //' paper_size.tex
	-make
	-sed -i '20s/^% //' paper_size.tex
	-sed -i '23,24s/^/% /' paper_size.tex

tablet:
	-sed -i '20s/^/% /' paper_size.tex
	-sed -i '27,28s/^% //' paper_size.tex
	-make
	-sed -i '20s/^% //' paper_size.tex
	-sed -i '27,28s/^/% /' paper_size.tex

notas_de_aula: notas_de_aula.tex
	latexmk -pdf notas_de_aula
