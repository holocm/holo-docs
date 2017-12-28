all: ad.png ad.jpg

ad.%: main.pdf
	mutool draw -w 1920 -h 1080 -o $@ $< 1

main.pdf: main.tex
	xelatex main

