# langtex
LaTeX project for comprehensive display of inter-lingual relationships

# my computer refuses to run the file anymore and I'm too busy with school to try to fix it (I already spent a few hours looking into the error)

Sources: wikipedia.org (I went through https://en.wikipedia.org/wiki/List_of_language_families#By_number_of_languages and followed each linked-subpage until the end (at the time of writing: Niger-Congo > North Volta > Gur > Bwa > Bwamu))

I will likely split the LaTeX code into smaller files at some point, maybe by language branch (e.g. North Volta languages from the Niger-Congo family would be in one file). For now, to build the PDF yourself, you must navigate to the project directory and then run ```pdflatex --enable-write18 --extra-mem-bot=10000000 --synctex=1 main.tex```. This is because the generation of the PDF requires too much power for the default build process. THIS MAY ONLY WORK ON MIKTEX.

I don't have a key on the PDF yet, so here it is:

*Red box = `d` = dead, extinct language.*

*Blue box = `u` = unsure, couldn't find number of speakers OR had fewer than 50k speakers before 2000.*

*Green box = `l` = living, documented as living after 2000 OR had more than 50k speakers before 2000.*

Please discuss any questions you have here: https://github.com/duncanjoly13/langtex/discussions
