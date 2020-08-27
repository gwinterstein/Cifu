# Cifu: a frequency lexicon for Hong Kong Cantonese

This repository offers a lexical database for Hong Kong Cantonese. Each entry in the lexicon includes the following information:
- the term in Chinese characters
- a Jyutping romanization of the term
- the frequency of the term (occurence counts and per million words) in four different genres: Written, Spoken adult, Spoken child and Child directed speech
- a count of the strokes in each character in the term (as a measure of the character complexity)
- 6 measures of the Neighborhood Density of each entry (distinguishing whether insertion/deletion are allowed when searching for neighbors and the genre from which frequencies are retrived to calculate the Neighborhood Density: Written, Spoken Adult or their average).

The repository also includes some of the resources used for creating Cifu:
- a Jyutping romanization dictionary, adapted from yeDict (https://writecantonese8.wordpress.com/2012/02/04/cantonese-cedict-project/)

Details about the construction of Cifu can be found in the following paper (please cite if you use Cifu in your research):

Lai, Regine and Winterstein, Grégoire (2020) "Cifu: a Frequency Lexicon of Hong Kong Cantonese", in Proceedings of The 12th Language Resources and Evaluation Conference, Marseille: European Language Resources Association, p. 3062--3070.

Available here: http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.375.pdf

Cifu is a registered language resource with the ISRLN (321-291-722-262-7):
http://www.islrn.org/resources/321-291-722-262-7/
