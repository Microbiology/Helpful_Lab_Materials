#! /bin/bash

echo Running Pandoc...
pandoc \
	--latex-engine=xelatex \
	--template=cltemplate.tex \
	-s ./coverletter.md \
	-f markdown \
	-t latex \
	-o ./coverletter.pdf
echo Done
