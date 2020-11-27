# Data Repository: The Textual History of Codex Sinaiticus Arabicus and its Family
The data to accompany Robert Turnbull's PhD thesis: The Textual History of Codex Sinaiticus Arabicus and its Family.

## Chapter 3 - D-Codex
Includes TEI, PDF, and Accordance User Bible files for:
* CSA: Codex Sinaiticus Arabicus (Sinai ar. NF Parch 8/27/28)
* N15<sup>+</sup>: Sinai ar. NF Parch 15/24/36/64
* S71<sup>+</sup>: Sinai ar. 71/Sinai ar. NF Parch 44

NB. These transcriptions have not be validated with a secondary independant transcription. The transcriptions are not intended for publication. They are provided to present the raw data for the numerical analysis. Any close textual study should be done using the D-Codex interface so the manuscript facsimile images can be used for comparison. Uncertain transcriptions are marked with question marks. Gaps in the PDF are marked by underbrackets. Narrow underbrackets $\underbracket(\ \ )$ represent one character and long underbrackets $\underbracket(\ \ \ \ \ \ )$ represent gaps of unknown length.

For the D-Codex Software Packages, see:
* https://github.com/rbturnbull/dcodex
* https://github.com/rbturnbull/dcodex_bible
* https://github.com/rbturnbull/dcodex_lectionary
* https://github.com/rbturnbull/dcodex_chrysostom

## Chapter 4 - Verse Metrics
The datasets used for the analysis in this chapter are:
* [Related_TP.csv](Chapter4/Related_TP.csv): The pairs of verse transcriptions from texts in the same family.
* [Unrelated_TP.csv](Chapter4/Unrelated_TP.csv): The pairs of verse transcriptions from texts different families.

For the code for this chapter see:
* https://github.com/rbturnbull/pairhmm
* https://github.com/rbturnbull/gotoh

## Chapter 5 - Jerusalemite Lectionary Headings
The tables presented in this chapter are reproduced here in in raw LaTeX.

## Chapter 6 - Lectionaries
TODO add Lectionary TEI/Accordance files

## Chapter 7 - Transmission History
This folder contains the input files for the phylogenetic analyses to investigate the transmission history of Arabic family B. This includes files for John 5–8 with both the Lewis Mk and Subyz models and with a strict clock and Random Local Clock (4 files).

For the D-Codex packages to do the Multiple Sequece Alignment, see:
* https://github.com/rbturnbull/dcodex_collation
* https://github.com/rbturnbull/gotoh

## Chapter 8 - The Textual Character of ar<sup>b</sup>
For this chapter, see the repository [CSA Textual Character](https://github.com/rbturnbull/csa-textual-character)

## Chapter 9 - The Place of ar<sup>b</sup> in the Wider Gospel Tradition
This folder contains the input files for the phylogenetic analyses to relate Arabic family B to the wider Gospel tradition using the UBS5 apparatus. This includes files for the 4 Gospels, both with the Lewis Mk and Subyz models and with a strict clock and Random Local Clock (16 files). This folder also contains the state reconstructions for the root and ar<sup>b</sup> as a PDF with for all runs.

For the software to use D-Codex to analyse textual variants, see:
* https://github.com/rbturnbull/dcodex_variants
