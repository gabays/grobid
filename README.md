# Automatic encoding of manuscripts catalogues with GROBID

Originally designed for dictionaries, we are trying to use GROBID with manuscripts catalogues.

## Credits

GROBID dictionaries is developped by Mohamed Khemakhem ([GitHub](https://github.com/MedKhem)).

More info on GROBID technoligies can be found [here](https://grobid.readthedocs.io).

Research on catalogues and training is carried by Simon Gabay.

## Corpus

Tests are carried on scans of the *Revue des autographes*, directes by Gabriel Charavay ([data.bnf](http://data.bnf.fr/10429866/gabriel_charavay/))

## Methodology

PDF are OCRised with [Transkribus](https://transkribus.eu). You can ask for our model.

The GROBID model is trained on four excerpts (three pages each) of the corpus (`toyData/dataset/dictionary-segmentation/corpus>PDF`).

## Files
Training data are available in `ToyData`

Samples of pdf and tools to manipulate them (`cpdf`) are in `TrainingTools`

## Paper

A first paper was presented at the TEI 2018 in Tokyo

```
@inproceedings{khemakhem:hal-01819505,
  TITLE = {{Automatically Encoding Encyclopedic-like Resources in TEI}},
  AUTHOR = {Mohamed Khemakhem, Laurent Romary, Simon Gabay, Hervé Bohbot, Francesca Frontini, Giancarlo Luxardo},
  URL = {https://hal.archives-ouvertes.fr/hal-01819505},
  BOOKTITLE = {{TEI 2018}},
  ADDRESS = {Tokyo, Japan},
  YEAR = {2018},
  MONTH = September,
  KEYWORDS = {Manuscripts auction catalogues, GROBID-Dictionaries, TEI, Dictionaries},
  PDF = {https://hal.inria.fr/hal-01819505/document},
  HAL_ID = {hal-01819505},
}
```

## Licence

Regarding `GROBID`, cf. [here](https://github.com/MedKhem/grobid-dictionaries).

Regarding the corpus: extracted data is CC-BY.  

<a rel="license" href="https://creativecommons.org/licenses/by/2.0"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/2.0/88x31.png" /></a><br />