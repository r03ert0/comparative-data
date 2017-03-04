# Comparative data

This is a repository of comparative data useful for neuroanatomy and neuroscience more generally.

## How to contribute

If you find tabular data as a picture, you can use http://www.onlineocr.net/ to convert it to text. Another alternatives are http://tesseract.projectnaptha.com/ or using the Naphta extension for Chrome https://projectnaptha.com/.

For data in scatter plots, bar plots and others, you can use http://arohatgi.info/WebPlotDigitizer/app/.

For each data table, create a file where the name is the DOI of the paper where the data comes from. DOI codes have symbols that are not allowed in a file name. Convert them to an acceptable name using http://meyerweb.com/eric/tools/dencoder/.

Put a correctly formated `.tsv` file with the data (GitHub will let you know if there are any problems), and add further comments or legends in a file with the same name plus `.ReadMe.txt`.

Finaly, to enjoy the fruit of your work, you can use http://rawgraphs.io/ and pass a https://rawgit.com link to the `.tsv` file to get beautiful d3 plots.

## Data
* [Table S1 from Motta and Herculano-Houzel 2015](https://github.com/r03ert0/comparative-data/blob/master/10.1126%252Fscience.aaa9101_TableS1.tsv) Total surface area, thickness and folding index for 65 species
* [Table S9 from Lewitus et al 2013](https://github.com/r03ert0/comparative-data/blob/master/10.1371%252Fjournal.pbio.1002000_TableS8.tsv) Neurone number and gyrification index for 25 species
* [Figure 2 from Herculano-Houzel et al 2013](https://github.com/r03ert0/comparative-data/blob/master/10.3389%252Ffnana.2013.00035_Figure2TopLeft.tsv) Number of neurones and volume of 18 cortical regions of the mouse
* [from Lewitus et al 2013](https://github.com/r03ert0/comparative-data/blob/master/10.3389%252Ffnhum.2013.00424.tsv) Brain weight, neurone density, astrocyte density, grey matter thickness, ventricular volume and gyrification index for 66 species.

## References

* Lewitus et al (2013) Conical expansion of the outer subventricular zone and the role of neocortical folding in evolution and development. http://dx.doi.org/10.3389/fnhum.2013.00424
* Lewitus et al (2013) An Adaptive Threshold in Mammalian Neocortical Evolution. http://dx.doi.org/10.1371/journal.pbio.1002000
* Herculano-Houzel et al (2013) Distribution of neurons in functional areas of the mouse cerebral cortex reveals quantitatively different cortical zones. http://dx.doi.org/10.3389/fnana.2013.00035
* Motta and Herculano-Houzel (2015) Cortical folding scales universally with surface area and thickness, not number of neurons. http://dx.doi.org/10.1126/science.aaa9101
