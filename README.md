# Comparative data

This is a repository of comparative data useful for neuroanatomy and neuroscience more generally.

## How to contribute

If you find tabular data as a picture, you can use [http://www.onlineocr.net/](http://www.onlineocr.net/) to convert it to text. Other alternatives are [http://tesseract.projectnaptha.com/](http://tesseract.projectnaptha.com/) or using the Naphta extension for Chrome [https://projectnaptha.com/](https://projectnaptha.com/).

For data in scatter plots, bar plots and others, you can use [http://arohatgi.info/WebPlotDigitizer/app/](http://arohatgi.info/WebPlotDigitizer/app/).

For each data table, create a `.tsv` file and use the DOI of the paper where the data comes from as name for the `.tsv` file. DOI codes have symbols that are not allowed in a file name. Convert them to an acceptable name using [http://meyerweb.com/eric/tools/dencoder/](http://meyerweb.com/eric/tools/dencoder/).

Provide a correctly formatted `.tsv` file with the data (GitHub will let you know if there are any problems), and add further comments or legends in a file with the same DOI name plus `.ReadMe.md`.

Finally, to enjoy the fruit of your work, you can use [http://rawgraphs.io/](http://rawgraphs.io/) and pass a [https://rawgit.com](https://rawgit.com) link to the `.tsv` file to get beautiful d3 plots.

We recently started using [https://observablehq.com/](https://observablehq.com/) which lets you create interactive notebooks using JavaScript. 

## Data
* [Table S1 from Mota and Herculano-Houzel 2015](https://github.com/r03ert0/comparative-data/blob/master/10.1126%252Fscience.aaa9101_TableS1.tsv) Total surface area, thickness and folding index for 65 species
* [Table S9 from Lewitus et al 2013](https://github.com/r03ert0/comparative-data/blob/master/10.1371%252Fjournal.pbio.1002000_TableS8.tsv) Neurone number and gyrification index for 25 species
* [Figure 2 from Herculano-Houzel et al 2013](https://github.com/r03ert0/comparative-data/blob/master/10.3389%252Ffnana.2013.00035_Figure2TopLeft.tsv) Number of neurones and volume of 18 cortical regions of the mouse
* [from Lewitus et al 2013](https://github.com/r03ert0/comparative-data/blob/master/10.3389%252Ffnhum.2013.00424.tsv) Brain weight, neurone density, astrocyte density, grey matter thickness, ventricular volume and gyrification index for 66 species.
* [Table from Burger et al. 2019](https://github.com/r03ert0/comparative-data/blob/master/10.5061%252Fdryad.2r62k7s.tsv). An interactive plot of this data can be found at [https://observablehq.com/@katjaq/comparative-data-brushable](https://observablehq.com/@katjaq/comparative-data-brushable)
* [Table 2 from Isler et al 2008](https://github.com/r03ert0/comparative-data/blob/master/10.1016%2Fj.jhevol.2008.08.004_Table2.tsv) Differences between ECV of wild and captive primates in our compilation.
* [Table 7 from Isler et al 2008](https://github.com/r03ert0/comparative-data/blob/master/10.1016%2Fj.jhevol.2008.08.004_Table7.tsv) Least-squares regressions for ln(ECV) versus ln(Body mass) within different primate species.
* [Tree from Isler et al 2008](https://github.com/r03ert0/comparative-data/blob/master/10.1016%2Fj.jhevol.2008.08.004_Tree.nex) Phylogenetic tree of primates (176 species, Nexus format).
* [Table S1 from Isler et al 2008](https://github.com/r03ert0/comparative-data/blob/master/10.1016%2Fj.jhevol.2008.08.004_TableS1.tsv) Endocranial volumes and body mass data (individual specimens).
* [Table S2 from Isler et al 2008](https://github.com/r03ert0/comparative-data/blob/master/10.1016%2Fj.jhevol.2008.08.004_TableS2.tsv) Endocranial volumes and body mass data (species means).
* [Table S3 from Isler et al 2008](https://github.com/r03ert0/comparative-data/blob/master/10.1016%2Fj.jhevol.2008.08.004_TableS3.tsv) Data on basal metabolic rate, gestation and lactation length.

## References

* Burger et al (2019). The allometry of brain size in mammals. [http://dx.doi.org/10.1093/jmammal/gyz043](http://dx.doi.org/10.1093/jmammal/gyz043)
* Herculano-Houzel et al (2013). Distribution of neurons in functional areas of the mouse cerebral cortex reveals quantitatively different cortical zones. [http://dx.doi.org/10.3389/fnana.2013.00035](http://dx.doi.org/10.3389/fnana.2013.00035)
* Lewitus et al (2013). Conical expansion of the outer subventricular zone and the role of neocortical folding in evolution and development. [http://dx.doi.org/10.3389/fnhum.2013.00424](http://dx.doi.org/10.3389/fnhum.2013.00424)
* Lewitus et al (2014). An Adaptive Threshold in Mammalian Neocortical Evolution. [http://dx.doi.org/10.1371/journal.pbio.1002000](http://dx.doi.org/10.1371/journal.pbio.1002000)
* Mota and Herculano-Houzel (2015). Cortical folding scales universally with surface area and thickness, not number of neurons. [http://dx.doi.org/10.1126/science.aaa9101](http://dx.doi.org/10.1126/science.aaa9101)
* Isler, K., Christopher Kirk, E., Miller, J. M. A., Albrecht, G. A., Gelvin, B. R., & Martin, R. D. (2008). Endocranial volumes of primate species: scaling analyses using a comprehensive and reliable data set. [https://doi.org/10.1016/j.jhevol.2008.08.004](https://doi.org/10.1016/j.jhevol.2008.08.004)

