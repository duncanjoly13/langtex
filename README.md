# langtex
LaTeX project for comprehensive display of inter-lingual relationships

Sources: wikipedia.org (I went through https://en.wikipedia.org/wiki/List_of_language_families#By_number_of_languages and followed each linked-subpage until the end (at the time of writing: Niger-Congo > North Volta > Gur > Bwa > Bwamu))

I will likely split the LaTeX code into smaller files at some point, maybe by language branch (e.g. North Volta languages from the Niger-Congo family would be in one file). For now, to build the PDF yourself, you must navigate to the project directory and then run ```pdflatex --enable-write18 --extra-mem-bot=10000000 --synctex=1 main.tex```. This is because the generation of the PDF requires too much power for the default build process. THIS MAY ONLY WORK ON MIKTEX.

Please discuss any questions you have here: https://github.com/duncanjoly13/langtex/discussions
