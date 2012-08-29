NAME=projectplan

.PHONY: all run clean pack

all: $(NAME)

$(NAME): $(NAME).tex
	pdflatex $(NAME).tex

clean:
	rm -f *.log *.dvi $(NAME).pdf *.aux *~
