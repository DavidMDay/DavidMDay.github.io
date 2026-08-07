# Variables
SOURCE   = main.tex
JOBNAME  = strutt1933translation

# Default target
all: pdf

# Build target using latexmk
pdf: $(SOURCE)
	latexmk -pdf -jobname=$(JOBNAME) $(SOURCE)

# Continuous preview mode (useful while editing)
watch: $(SOURCE)
	latexmk -pdf -pvc -jobname=$(JOBNAME) $(SOURCE)

# Clean build artifacts but keep the final PDF
clean:
	latexmk -c -jobname=$(JOBNAME)

# Clean everything including the final PDF
cleanall:
	latexmk -C -jobname=$(JOBNAME)

.PHONY: all pdf watch clean cleanall

