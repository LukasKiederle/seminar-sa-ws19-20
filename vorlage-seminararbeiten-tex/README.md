# Small intro for using latex template:

## Installation and usage of the checked in code
1. Install IDE TexStudio (https://www.texstudio.org/).
[Here](https://github.com/m-entrup/LaTeX-Vorlagen/wiki/TeXstudio-einrichten) is a link for setting up TexStudio
If you need help. Contact me please :).

2. Open the **thesis.tex** file with TexStudio. 

3. Compile the code and verify that you have every extension needed and the pdf is created without issues. (Warnings are ok)

## Generell infos
* You will mainly work in the: 
  * chapters.tex for chapter content
  * abstract.tex for the abstract
  * thesis.tex for adding new packages if needed
* Don't check in all files. The gitignore should exclude all generated files by latex
* Every time you change something you have to compile again
* If you compile and run into some issues do this:
  * Problem with sources: The code didnt compile because of äöü or so. The easiest way to fix this is to deleted the autogenerated bib file
  * Other Problems: Use google :)
* The most common used commands like section or listing items are already in the code. If you have further issues feel free to contact me

