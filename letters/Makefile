all: build

build: clean
	docker run --rm -t -v $$(pwd):/source schickling/latex pdflatex main.tex

clean:
	rm -f *.aux
	rm -f *.log
	rm -f *.pdf
