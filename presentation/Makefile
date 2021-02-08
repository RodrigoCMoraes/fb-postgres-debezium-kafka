all: compile run

run: presentation.html
	xdg-open presentation.html

compile: presentation.md
	pandoc -t revealjs -s presentation.md -V theme=serif -o presentation.html
	sed -i 's/h1/h2/' presentation.html

clean: presentation.html
	rm presentation.html
